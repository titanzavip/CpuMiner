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
```

git clone https://github.com/glukolog/cpuminer-opt.git
cd cpuminer-opt
./autogen.sh
CFLAGS="-O3 -march=armv7l -mtune=cortex-a55" ./configure --with-curl --with-crypto
make -j2
./cpuminer --help

