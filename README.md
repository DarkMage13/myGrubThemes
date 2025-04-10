This is my version of a Grub theme, originaly with Osage chan. Now it is with Shuvi from No Game No Life Zero.

To install first clone the repository
```
git clone https://github.com/DarkMage13/myGrubThemes
```
then copy the repository to this directory
```
sudo cp -r myGrubThemes /usr/share/grub/themes
```
after this modify the grub config file
```
sudo nano /etc/default/grub

sudo vim /etc/default/grub

sudo nvim /etc/default/grub
```
add this line
```
GRUB_THEME="/usr/share/grub/themes/myGrubThemes/theme.txt"
```
lastly update grub
```
sudo grub-mkconfig -o /boot/grub/grub.cfg  
```
