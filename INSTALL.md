### [GRUB](https://gnu.org/software/grub/)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

```bash
git clone https://github.com/dracula/grub2.git
```

#### Install manually

Download using the [GitHub .zip download](https://github.com/dracula/grub2/archive/main.zip) option and unzip them.

#### Activating theme

1. Extract and move the dracula-grub2 folder to /boot/grub/themes/
2. Add or Edit the line in /etc/default/grub: `"GRUB_THEME=/boot/grub/themes/dracula-grub2/theme.txt"`
3. Run
    ```sudo update-grub```
   or
    ```sudo grub-mkconfig -o /boot/grub/grub.cfg```
   to update the theme 