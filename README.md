This guide shows what to do to get your GNOME to look like MacOS!

1. Enable "Show Hidden Files" in your file manager.																														

2. Install GNOME Extensions and GNOME Tweaks.

3. Detach your Dock so it floats like in MacOS and make it so it always shows!

4. Put the .themes and .icons folder in your home directory.

5. Go into GNOME Tweaks and do the following:

   Appearance > Applications: WhiteSur-Dark
                Cursor: MacOS
                Icons: Mkos-Big-Sur-Night
             
                Background
                Image: macos.jpg
             
6. Put 'apple.txt' and 'dock.sh' in to your home directory.

7. Open your terminal and write 'nano ~/.bashrc'

8. Than at the bottom, paste the following:
    
    neofetch --ascii 'apple.txt'
    
    gsettings set org.gnome.shell.extensions.dash-to-dock background-opacity 0.4

Done! Here are some extras you can do:

1. Go into your Terminal and write 'sudo hostnamectl set-hostname macos'

2. Reopen your terminal.

And that is it for the guide! Have fun :)
