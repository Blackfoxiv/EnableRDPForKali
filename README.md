sudo apt update && apt upgrade</br>
echo "deb http://http.kali.org/kali kali-rolling main non-free contrib" | sudo
tee /etc/apt/sources.list</br>
curl https://archive.kali.org/archive-key.asc | sudo apt-key add</br>
sudo apt update</br>
sudo apt install kali-linux-default</br>
sudo apt install kali-desktop-xfce</br>
sudo apt install xrdp</br>
sudo passwd myuser </br>
