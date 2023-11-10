apt update -y
termux-setup-storage
pkg install wget -y
wget -O install-nethunter-termux https://offs.ec/2MceZWr
chmod +x install-nethunter-termux
./install-nethunter-termux
nh -r
nano /etc/resolv.conf
apt update 
apt install dbus-x11 -y
settings
nh kex

