---
title: "Homebrew Channel ve BootMii Yüklemesi"
---

{% include toc title="Table of Contents" %}

Eğer bu öğreticiye bağlı herhangi bir yardıma ihtiyacınız olursa lütfen [RiiConnect24’ün Discord sunucusuna katılın](https://discord.gg/rc24) (tavsiye edilen) ya da [support@riiconnect24.net üzerinden mail atın](mailto:support@riiconnect24.net).
{: .notice--info}

![HBC Logosu](/images/hbc.png)

Homebrew Channel, homebrew uygulamalarını başlatabileceğiniz yegane yerdir. BootMii ise, Wii'nizin NAND belleğini yedekleyip geri getirebilen bir yazılımdır. boot2 olarak yüklendiyse, sizi brick modundan da korur.

#### Talimatlar

1. Sahte bir uyarı ekranı göreceksiniz. Metin için 30 saniye bekleyin ve "Press 1 to continue" gözükünce 1 tuşuna basın. ![Sahte Ekran](/images/Wii/ScamScreen.png)

2. HackMii yükleyicisindeyken, Homebrew Channel ve BootMii'yi yükleyebileceksiniz. ![Sonuçlar](/images/Wii/Results.png)

3. ''Continue'' deyin, ardından ''Homebrew Channel'' seçeneğini seçin ve yükle tuşuna basın. ![Homebrew Channel’ı Yüklemek](/images/Wii/InstallHomebrewChannel.png)

4. Bittiğinde, ''Continue'' deyin. ![Homebrew Channel'ın Başarılı Olarak Yüklenmesi](/images/Wii/SuccessHBC.png)

5. Yüklendiğinde, BootMii'ye dönmek için geri dönün.
6. Eğer ana ekran BootMii'yi boot2 olarak yükleyebileceğinizi söylüyorsa, öyle yükleyin. Bu, sahip olabileceğiniz en iyi brick korumasıdır. Skip this step if the option doesn't show up, in that case your Wii is not one of the earlier models that supports it.
7. Install BootMii as IOS, even if you already installed BootMii as boot2 in the previous step. If you couldn't install BootMii as boot2, this will still allow you to create a NAND backup.

If you do not have an SD card, you cannot install nor use BootMii, and therefore will not be able to utilize any of the mentioned benefits. Ancak daha sonra istediğiniz zaman yükleyebilirsiniz.
{: .notice--warning}

![BootMii Yüklemesi](/images/Wii/InstallBootMii.png)

8. Tamamlandığı vakit, önce `Continue` seçeneğini, ardından Homebrew Channel'a çıkmak için `Exit` seçeneğini seçin.

#### Required Reading

You can now use the Homebrew Channel to launch homebrew apps. Open Shop Channel is a one-stop shop for downloading homebrew, which you will learn how to install further in this guide.

Here's a tip - when installing homebrew applications on your SD Card or USB drive, your folder structure should look like this:

💾 sd or usb:

┣ 📂 apps

┃ ┣ 📂 AppName1

┃ ┃ ┣ 📄 boot.dol / boot.elf

┃ ┃ ┣ 📄 icon.png

┃ ┃ ┗ 📄 meta.xml

┃ ┗ 📂AppName2

┃ ┃ ┣ 📄 boot.dol / boot.elf

┃ ┃ ┣ 📄 icon.png

┃ ┃ ┗ 📄 meta.xml

`AppName1` and `AppName2` are placeholder names. Do not nest multiple `apps` folders inside the `apps` folder itself.

[Continue to making a NAND Backup using BootMii](bootmii)<br> Making a NAND backup with BootMii at this point is highly recommended.
{: .notice--info}

If you couldn't install BootMii, continue to [installing Priiloader](priiloader).
{: .notice--info}

Tip: You can tell if a Wii has BootMii installed as boot2 if your disc drive flashes very briefly, only after the immediate flash that happens when you press the POWER Button.
{: .notice--info}
