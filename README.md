# chromebook-install-manjaro
Chromebook is a kind of great product. But to be honest, it still has some big problems, because it's so advanced that it can't works as good as we want in today's environment. Some new devices support linux-beta now, but most older devices miss this big chance. Althrough, we can use crouton to install a linux system, it works terrible on my device. So I want to install a really linux system--manjaro on my chromebook. Although it still has some problems such as the sounds and backlit keyboard, it makes my chromebook a really computer! So if you have the same thought, follow these tips and enjoy it!
1."Make a USB startup disk"
(1)Search manjaro and choose the kde-manjaro, download it. If it download fast, it will be a good news!
(2)Search rufus and download it on your windows computer.
(3)Insert USB-disk in your windows computer, 8 Gb is enough.
(4)Run rufus and choose the iso file, just follow the guide and enjoy a cup of water, you will get a warm USB-disk that can make a big difference.
2."Install seabios on chromebook"
(1)https://blog.tangbao.me/2015/12/acer-cb3-111-c670-install-linux/
(2)Some device can't run john's seabios, and chromebox's seabios maybe work. So if you can't install john's seaios, run:
cd; rm -f flash_chromebook_rom.sh;  curl -L -O https://mrchromebox.tech/firmware-util.sh && sudo bash firmware-util.sh. If you want to know more, search mrchromebox and you will find want you want.
3.Insert the USB disk on your chromebook,shutdown and start it, you will see the bios work. Choose "boot manager" and then choose USB-Device, it works! Now you have a powerful computer with linux system! Enjoy it!
