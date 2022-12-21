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
apt update && apt upgrade
```
```
pkg update -y
```
```
pkg install wget -y 
```
```
pkg install curl -y
```
```
pkg install proot -y
```
```
pkg install tar -y
```
```
wget https://raw.githubusercontent.com/AndronixApp/Androni xOrigin/master/Installer/Ubuntu/ubuntu.sh -0 ubuntu.sh && chmod +x ubuntu.sh && bash ubuntu.sh
```
```
./start-ubuntu.sh su
```
```
cd
```
```
apt-get update && apt-get upgrade -y apt install git -y
```
```
apt install proot -y
```
```
apt-get install automake autoconf pkg-config libcur14-openssl-dev libjansson-dev libssl-dev libgmp-dev zlib1g-dev make g++
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

```
./cpuminer -a yespowerR16 -o stratum+tcp://hosname.org:port -O user:pass
```

```
apt update && apt upgrade
```
```
apt install git gcc g++ autogen nano
```
```
pkg install automake autoconf git
```
```
apt-get install build-essential automake autoconf pkg-config libcurl4-openssl-dev libjansson-dev libssl-dev libgmp-dev zlib1g-dev
```
```
git clone https://github.com/fireworm71/veriumMiner
```

#minotaur
```
git clone https://github.com/litecoincash-project/cpuminer-multi
```
```
cd veriumMiner
```
```
./autogen.sh
```
```
./configure CFLAGS=--with-crypto --with-curl
```
```
./build.sh
```
```
chmod +x cpuminer
```
```
nano mine.sh
```
```
./cpuminer -o stratum+tcp://stratum.poolsloth.com:3333 -u fireworm.donations -p x
```
```
chmod +x mine.sh
```
```
./mine.sh
```
```
./cpuminer -a minotaurx -o stratum+tcp://x11.eobot.com:5555 -u eobot.991010 -p x -t 4 -- -a = algorithm -- -o = pool -- -u = user -- -p = password -- -t = thread / cpu
```
```
./cpuminer -a minotaurx -o stratum+tcp://minotaurx.asia.mine.zergpool.com:7019 -u DRkNn7KAtpiRk2ySwtxKWHMHTLPndREFW9 --timeout 120 -p  c=DOGE,mc=AVN,ID=Mine-1 -t=7
```
