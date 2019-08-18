Pkg install ruby cowsay toilet figlet
pkg install neofetch
pkg install nano
gem install lolcat
cd ../usr/etc
nano bash.bashrc
clear
cowsay -f eyes Hello | lolcat
toilet -f standard Mr P1x31 -F gay
neofetch
date | lolcat
echo "=================================

#Nama:Mr P1x31
#Team:Mr P1x31

==================================" | lolcat

sleep 3

echo "[1]Hack Fb
[2]Bermain moon-buggy
[3]Telephone di termux
[4]N_Map
[5]Localozor ip
[6]Red_hawk
[7]Exit  " | lolcat
echo "[*] Pilih nomor = " | lolcat
read nomor

if [ $nomor = 1 ] || [ $nomor = 01 ]
then
clear
pkg install python2 git
pip2 install mechanize
git clone http://github.com/pirmansx/mbf
ls
cd mbf
python2 MBF.py
fi
if [ $nomor = 2 ] || [ $nomor = 02 ]
then
clear
pkg install moon-buggy
moon-buggy
fi

if [ $nomor = 3 ] || [ $nomor = 03 ]
then
clear
pkg install termux-api
termux-telephony-call nomornya
fi

if [ $nomor = 4 ] || [ $nomor = 04 ]
then
clear
apt install nmap
echo "ketik:nmap <host/IP target>" | lolcat
echo "ketik:nmap -p <host/IP target>" | lolcat
echo "ketik:nmap -sV <host/IP target>" | lolcat
echo "ketik:nmap -O <host/IP target>" | lolcat
fi

if [ $nomor = 5 ] || [ $nomor = 05 ]
then
clear
Apt install python git
git clone https://github.com/maldevel/IPGeoLocation.git
cd IPGeoLocation
chmod +x ipgeoLocation.py
pip install -r requirements.txt
python ipgeolocation.py -m
python ipgeolocation.py -t http://www.google.com
fi

if [ $nomor = 6 ] || [ $nomor = 06 ]
then
clear
apt update
apt install git
git clone https://github.com/Tuhinshubhra/RED_HAWK
cd RED_HAWK
chmod +x rhawk.php
apt install php
ls
php rhawk.php
fi
