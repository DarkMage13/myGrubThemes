This is my version of a Grub theme, originaly with Osage chan. Now it is with Shuvi from No Game No Life Zero.

To install first clone the repository
```
git clone https://github.com/Hitori-Laura/OsageChan_GRUB_theme.git
```
then copy the repository to this directory
```
sudo cp -r OsageChan_GRUB_theme /usr/share/grub/themes
```
after this modify the grub config file
```
sudo nano /etc/default/grub

sudo vim /etc/default/grub

sudo nvim /etc/default/grub
```
add this line
```
GRUB_THEME="/usr/share/grub/themes/OsageChan_GRUB_theme/theme.txt"
```
lastly update grub
```
sudo grub-mkconfig -o /boot/grub/grub.cfg  
```
