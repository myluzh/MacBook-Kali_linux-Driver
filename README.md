# MacBook-Kali_linux-Driver

*Tips:Only pass the test in MacBook Pro 2016/2017. Please test yourself for other models.*

## 1.WiFi

Source:https://gist.github.com/cristianmiranda/6f269797b62076c3414c3baa848dda67#fle-brcmfmac43602-pcie-txt

After testing, WiFi can access the Internet normally, but it can not be used for air ng (error adding monitor mode interface: command failed: operation not supported (- 95))
```
cd driver/wifi/
#run the following command as root or with sudo
cp brcmfmac43602-pcie.txt /lib/firmware/brcm/.
reboot
```

## 2.Audio
Source:https://github.com/davidjo/snd_hda_macbookpro.git

```
cd driver/audio/snd_hda_macbookpro/
#run the following command as root or with sudo
./install.cirrus.driver.sh
reboot
```
## 3.Touch Bar
There is no suitable driver for TouchBar at present. You can leave a message if you are willing to provide it.
It is recommended to install on-screen keyboard 'onboard' for models with TouchBar.
```
#run the following command as root or with sudo
apt-get install onboard
```
