# i3gaps-sid
I wanted to install i3 gaps on a debian testing machine.
My recommendation is to install debian stable minimal (no gui).
I used the expert method and the only thing in my:

/etc/apt/sources.list 

deb ftp://us.debian.org/debian/ testing main non-free contrib

After sudo apt update && sudo apt upgrade (takes a while)

sudo apt install git

git clone https://github.com/drewgrif/i3gaps-sid

cd i3gaps-sid

chmod +x install.sh nerdfonts.sh
./install.sh
reboot
log in using ly log in manager.

**DO NOT USE THE NERDFONTS.SH UNTIL YOU HAVE LOGGED INTO I3. 