---
title: "{% include toc title=\"Table of Contents\" %}\nSe você precisar de ajuda para qualquer coisa sobre este tutorial, por favor, junte-se ao servidor RiiConnect24 Discord (recomendado) ou envie-nos um e-mail para support@riiconnect24. net.\n{:. notice--info}\nUm dos recursos mais importantes do BootMii é a capacidade de fazer backup e restaurar o armazenamento Nand do seu Wii. Vamos repassar como executar um backup Nand. Você pode então restaurar a partir desse backup por qualquer razão. Recomendamos fazer um backup Nand regularmente ou antes de fazer algo arriscado para o seu console (e se você sabe o que está fazendo, você não terá que fazer nada arriscado).\n\nRequisitos\n\nUm cartão Sd com pelo menos 512MB de espaço livre\n\nInstruções\n1. Abra o The Homebrew Channel\n2. Pressione o Botão Home, selecione \"Launch BootMii\"\n\nNão é possivel navegar usando um controle remoto Wii. Você teria que usar os botões do seu console Wii ou um controlador GameCube conectado à porta 1. Para navegar entre as opções, pressione Power no seu Wii (ou no botão direito + Control Pad em um controlador GameCube). Tenha em mente que ao usar os botões wii, você só pode navegar para a direita, mas ao tentar passar pela última entrada, ele vai deformar você para o primeiro. Isso não é uma limitação nos Controladores GameCube; Você pode navegar pela esquerda e pela direita. Para selecionar uma opção, aperte Reset em seu Wii ou A no controle do GameCube.\n3. Pressione o botão de Options (o unico com as engrenagens)\n4. Pressione o botão de BackupMii (O unico com a seta verde) \nO Backup da Nand vai iniciar. Você pode assisistir o progresso na tela\nNão desligue seu Wii enquanto estiver fazendo o backup\n\"Bad Blocks\" são normais, Não se preocupe se você ver um em seu bckup da Nand\nApós essas etapas, verificará o backup. Embora seja recomendado, ele pode ser ignorado pressionando o botão Eject no seu Console Wii.\n5. Quando o backup estiver completamente pronto, saia da tela de backup da Nand pressionando qualquer botão. \n6. Para sair do BootMii, pressione o botão \"Back\" (o unico com a seta) e, em seguida, você pode pressionar o botão Menu Wii ou o botão Homebrew Channel para sair onde você quiser.\nPara restaurar a partir de um backup Nand em seu cartão Sd, você pode seguir estas instruções usando RestoreMii (o botão ao lado de BackupMii com uma seta vermelha).\n\n{:. notice--info}\n\nContinue para a instalação do Priiloader\nPriiloader adiciona um nível de proteção de tijolos, e recomendamos isso, especialmente se você só instalou bootMii como um Ios.\n{:. notice--info}"
---

{% include toc title="Table of Contents" %}

Se você precisa de ajuda sobre qualquer coisa deste tutorial, por favor entre [no servidor do Discord RiiConnect24](https://discord.gg/rc24) (recomendado) ou [mande um e-mail para support@riiconnect24.net (em inglês)](mailto:support@riiconnect24.net).
{: .notice--info}

![Logo BootMii](/images/bootmii.png)

Você irá precisar de um **cartão SD** para criar o backup da NAND utilizando o BootMii. If you do not have one, you can skip this page, although it is highly recommended to make a NAND backup if you can.
{: .notice--warning}

BootMii como boot2 é recomendado, mas apenas disponível para instalação em Wiis antigos. Otherwise, it can only be installed as an IOS.
{: .notice--info}

Um dos recursos mais importantes do BootMii é a habilidade de backup e restaurar a memória NAND do seu Wii. Nós iremos te mostrar como fazer o backup da NAND. You can then restore from that backup for any reason. É uma boa ideia que faça um backup da NAND regularmente ou antes de fazer algo arriscado no seu console (e se você sabe o que está fazendo, você não precisa fazer nada arriscado).

#### Requisitos
* Um cartão SD com pelo menos 512MB de espaço livre

#### Instruções
Se você instalou o BootMii como Boot2 na última etapa, será necessário iniciar o BootMii reiniciando o console. Pule as etapas 1-2 se esse for o caso.
{: .notice--info}
1. Inicie o Homebrew Channel.
2. Aperte o botão HOME e selecione "Launch BootMii".

    Não é possível navegar no BootMii utilizando o Wii Remote. Você deve utilizar os botões POWER e RESET do seu console, ou um controle de Gamecube conectado na porta 1. Para navegar entre as opções, pressione POWER no seu Wii (ou direita no D-Pad em um controle de Gamecube). To select an option, press RESET on your Wii or A on your GameCube controller.
    {: .notice--info}


    Se a tela ficar preta e a luz azul do disco estiver piscando, quer dizer que está faltando os arquivos BootMii no seu SD card. Baixe [este zip](https://static.hackmii.com/bootmii_sd_files.zip) e extraia-o para a raiz do seu cartão SD e tente novamente. Download [this zip file](https://static.hackmii.com/bootmii_sd_files.zip) and extract it to the root of your SD card, then try again.
    {: .notice--warning}

3. Select the Options button (the icon with the gears).
4. Select the BackupMii button (the icon with the green arrow, aka the first icon on your left).
- Um backup da NAND será iniciado. Você pode acompanhar o progresso na tela.
- "Bad Blocks" são normais. Não se preocupe quando você ver um em uma backup da NAND.
- Depois desta etapa, o backup irá ser verificado. Embora seja recomendado, você pode pular pressionando o botão EJECT no seu Wii.
5. Quando o backup for totalmente finalizado, saia da tela de backup da NAND pressionando qualquer botão.
6. Para sair do BootMii, pressione o botão voltar (aquele com a seta) e em seguida você pode pressionar o botão de Menu do Wii ou o Homebrew Channel para sair para onde deseja.

To restore from a NAND backup on your SD card, you can follow these instructions using RestoreMii (the icon with the red arrow, aka the second icon on your left). Isso é útil caso seu wii esteja com brick.
{: .notice--info}

To make sure you don’t lose the files, it's recommended to copy `nand.bin` and `keys.bin` from the root of your SD card to your computer.
{: .notice--info}

[Continue to Priiloader Installation](priiloader) Priiloader adds a level of brick protection, and we recommend it, especially if you were only able to install BootMii as IOS.
{: .notice--info}
