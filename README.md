# rEFInd Theme
A rEFInd theme I put together for my MacBook Air. See [Credits](#credits) for the various elements I used.
## Install
```
sudo apt-add-repository ppa:rodsmith/refind
sudo apt update
sudo apt install refind git
sudo git clone https://github.com/abraha2d/refind-theme.git /boot/efi/EFI/refind/theme/
echo "include theme/theme.conf" | sudo tee -a /boot/efi/EFI/refind/refind.conf
```
## Credits
- lukechilds's Ambience rEFInd Theme
- sdbinwiiexe's rEFInd Next Theme
- brianlechthaler's rEFInd Banner
