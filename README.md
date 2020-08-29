# AçıkDepo

AcikDepo eklemek için:
```
sudo echo "deb [arch=amd64] http://depo.aciklab.org/ onyedi main" > /etc/apt/sources.list.d/acikdepo.list
sudo wget -qO - http://depo.aciklab.org/public.key | sudo apt-key add -
sudo apt update
```

Lightdm HVL Greeter yüklemek için:
```
sudo apt install lightdm-hvl-greeter
```
