# AçıkDepo

AcikDepo eklemek için:
```
sudo echo "deb [arch=amd64] https://depo.aciklab.org/ onyedi main" > /etc/apt/sources.list.d/acikdepo.list
sudo wget -qO - https://depo.aciklab.org/public.key | sudo apt-key add -
sudo apt update
```

Lightdm HVL Greeter yüklemek için:
```
sudo apt install lightdm-hvl-greeter
```
