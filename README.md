# CpuMiner

```
termux-setup-storage
```
```
apt update && apt upgrade
```
```
pkg install proot-distro
```
```
proot-distro install ubuntu
```
```
proot-distro login ubuntu
```
# OS-INSTALLER
```
termux-setup-storage
```
```
apt update -y
```
```
apt upgrade -y
```
```
apt install git -y
```
```
git clone https://github.com/mantvmass/os-installer
```
```
cd os-installer
```
```
sh build.sh
```
Open Os
```
os-installer
```


# Ubuntu Start

```
apt-get update && apt-get upgrade -y
```
```
apt install git -y
```
```
apt install proot -y
```
```
apt-get install automake autoconf pkg-config libcurl4-openssl-dev libjansson-dev libssl-dev libgmp-dev zlib1g-dev make g++
```
```
apt-get install libcurl4-openssl-dev -y && apt-get install libssl-dev -y && apt-get install libjansson-dev -y && apt-get install automake -y && apt-get install autotools-dev -y && apt-get install build-essential -y && apt-get install nano -y
```
#Minotaurx 
```
git clone https://github.com/titanzavip/cpuminer-multi.git
```

```
git clone https://github.com/tpruvot/cpuminer-multi
```
```
cd cpuminer-multi
```
```
./build-linux-arm.sh
```
#Zergpool 
```
./cpuminer -a minotaurx -o stratum+tcp://minotaurx.mine.zergpool.com:7019 -u DRkNn7KAtpiRk2ySwtxKWHMHTLPndREFW9 --timeout 120 -p  c=DOGE,mc=LCC,ID=Miner01
```
#CoinminerZ
```
./cpuminer -a minotaurx -o stratum+tcp://sg-stratum.coinminerz.com:3511 -u CfXCaWXCKuCm6d8T4Kdx7Fq9cvqSe81YMA.Miner01 
```
#Doge
```
DRkNn7KAtpiRk2ySwtxKWHMHTLPndREFW9
```

#LCC
```
CfXCaWXCKuCm6d8T4Kdx7Fq9cvqSe81YMA
```
#Set-arm-cortex53
```
./configure CFLAGS="-O3 -march=armv8-a+crypto -mtune=cortex-a53" --with-curl --with-crypto
```
