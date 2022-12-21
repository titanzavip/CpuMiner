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


# Ubuntu Start
```
apt update && apt upgrade
```
```
apt install git
```
```
git clone https://github.com/glukolog/cpuminer-opt.git
```
```
cd cpuminer-opt
```
```
./autogen.sh
```
```
CFLAGS="-O3 -march=armv7l -mtune=cortex-a55" ./configure --with-curl --with-crypto
make -j2
```
```
./autogen.sh
```
```
./configure CFLAGS="-O3 -march=armv8-a+crypto -mtune=cortex-a53" --with-curl --with-crypto
```
```
./autogen.sh
CFLAGS="-O3 -march=armv8-a+crypto -mtune=cortex-a53" --with-curl --with-crypto
make -j2
```
```
```
```
```
```
```
```
```
```
```
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
