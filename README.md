# AçıkDepo

AcikDepo eklemek için:
```
sudo echo "deb [arch=amd64] http://acikdepo.github.io/ onyedi main" > /etc/apt/sources.list.d/acikdepo.list
sudo wget -qO - https://raw.githubusercontent.com/acikdepo/acikdepo.github.io/master/public.key | sudo apt-key add -
sudo apt update
```

Lightdm HVL Greeter yüklemek için:
```
sudo apt install lightdm-hvl-greeter
```
