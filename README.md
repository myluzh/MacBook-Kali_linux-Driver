# MacBook-Kali_linux-Driver

Tips:Only pass the test in MacBook Pro 2016. Please test yourself for other models.

1.wifi

source:https://gist.github.com/cristianmiranda/6f269797b62076c3414c3baa848dda67#fle-brcmfmac43602-pcie-txt


sudo cp wifi/brcmfmac43602-pcie.txt /lib/firmware/brcm

2.audio

source:https://github.com/davidjo/snd_hda_macbookpro.git


cd audio/snd_hda_macbookpro/

./install.cirrus.driver.sh

