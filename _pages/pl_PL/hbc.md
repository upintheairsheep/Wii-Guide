---
title: "Przejdź do instalacji Homebrew Channel oraz BootMii"
---

{% include toc title="Zawartość" %}

Jeżeli potrzebujesz pomocy z czymkolwiek dotyczącym tego poradnika, dołącz do [serwera RiiConnect24 na Discordzie (wsparcie dostępne po Polsku!)](https://discord.gg/rc24) lub napisz do nas na [support@riiconnect24.net](mailto:support@riiconnect24.net).
{: .notice--info}

![Logo HBC](/images/hbc.png)

Homebrew Channel jest miejscem, w którym możesz uruchamiać programy homebrew. BootMii jest programem dzięki któremu możesz wykonywać kopię zapasową oraz przywracać pamięć NAND Twojej Wii. Jeżeli BootMii jest zainstalowane jako boot2, zapewnia to całkowitą ochronę przed brickami.

#### Instrukcje

1. Zobaczysz ekran, który ostrzega przed oszustwami. Poczekaj 30 sekund na pojawienie się tekstu "Press 1 to continue" oraz naciśnij 1. ![Ekran z informacją o oszustwach](/images/Wii/ScamScreen.png)

2. Kiedy jesteś w instalatorze HackMii, możesz zainstalować Homebrew Channel oraz BootMii. ![Wyniki](/images/Wii/Results.png)

3. Naciśnij kontynuuj oraz wybierz Homebrew Channel, następnie wybierz "Install". ![Zainstaluj Homebrew Channel](/images/Wii/InstallHomebrewChannel.png)

4. Po ukończeniu, naciśnij na "Continue". ![Sukces podczas instalacji Homebrew Channel](/images/Wii/SuccessHBC.png)

5. Po zainstalowaniu, naciśnij "Back" oraz przejdź do "BootMii".
6. Jeżeli na ekranie wyświetli się informacja o możliwości zainstalowania jako boot2, zrób to. Oferuje to najlepszą możliwą ochronę przed brickiem. Skip this step if the option doesn't show up, in that case your Wii is not one of the earlier models that supports it.
7. Install BootMii as IOS, even if you already installed BootMii as boot2 in the previous step. If you couldn't install BootMii as boot2, this will still allow you to create a NAND backup.

If you do not have an SD card, you cannot install nor use BootMii, and therefore will not be able to utilize any of the mentioned benefits. Zawsze możesz zainstalować go kiedy indziej.
{: .notice--warning}

![Instalacja BootMii](/images/Wii/InstallBootMii.png)

8. Po zakończeniu wybierz `Continue`, a następnie wybierz `Exit` aby przejść do Homebrew Channel

#### Wymagane czytanie

Teraz możesz użyć kanału Homebrew, by uruchamiać aplikacje Homebrew. Open Shop Channel jest punktem pobierania aplikacji Homebrew, który potem się dowiesz jak tam instalować dalej w tym poradniku.

Taka wskazówka - kiedy instalujesz aplikacje Homebrew na twojej karcie pamięci lub dysku USB, twoja struktura folderów powinna wyglądać tak:

💾 karta pamięci lub usb:

┣ 📂 apps

┃ ┣ 📂 NazwaAplikacji1

┃ ┃ ┣ 📄 boot.dol / boot.elf

┃ ┃ ┣ 📄 icon.png

┃ ┃ ┗ 📄 meta.xml

┃ ┗ 📂NazwaAplikacji2

┃ ┃ ┣ 📄 boot.dol / boot.elf

┃ ┃ ┣ 📄 icon.png

┃ ┃ ┗ 📄 meta.xml

`NazwaAplikacji1` i`NazwaAplikacji2` są nazwami zastępczymi. Nie zagnieżdżaj kilku `folderów` aplikacji w środku w tym samym folderze`apps`.

[Kontynuuj robienie kopii zapasowej używając BootMii](bootmii)<br> Zrobienie kopii zapasowej pamięci NAND jest teraz bardzo zalecana.
{: .notice--info}

Jeśli nie mogłeś zainstalować BootMii, to kontynuuj [instalowanie priiloader](priiloader).
{: .notice--info}

Tip: You can tell if a Wii has BootMii installed as boot2 if your disc drive flashes very briefly, only after the immediate flash that happens when you press the POWER Button.
{: .notice--info}
