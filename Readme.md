### Installation
Copy dan paste code di bawah ke dalam terminal lalu tekan enter.

Update Repo Debian 10

  ```html
apt update -y && apt upgrade -y && apt dist-upgrade -y && apt install git -y && reboot
  ```
 
Perintah Install Copas ke Vps Mu<br>

  ```html
apt install -y wget screen && apt update -y && apt upgrade -y && apt install lolcat -y && gem install lolcat && apt install sudo -y && apt install socat -y && sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && git clone https://github.com/miftah06/SCV1 && cd SCV1 && wget https://raw.githubusercontent.com/miftah06/SCV1/master/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
``` 

Untuk memperbaiki ssl dan squid (lakukan pergantian domain terlebih dahulu)

  ```html
apt reinstall stunnel -y && apt reinstall stunnel4 -y && apt reinstall squid -y && apt reinstall shadowsocks -y
``` 
