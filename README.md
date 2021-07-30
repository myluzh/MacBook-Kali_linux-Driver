# MacBook-Kali_linux-Driver

*Tips:Only pass the test in MacBook Pro 2016. Please test yourself for other models.*

## 1.wifi
source:[https://gist.github.com/cristianmiranda/6f269797b62076c3414c3baa848dda67#fle-brcmfmac43602-pcie-txt]()


```
cd driver/wifi/
#run the following command as root or with sudo
cp brcmfmac43602-pcie.txt /lib/firmware/brcm/
```

## 2.audio
source:[https://github.com/davidjo/snd_hda_macbookpro.git]()

```
cd driver/audio/snd_hda_macbookpro/
#run the following command as root or with sudo
./install.cirrus.driver.sh
reboot
```
