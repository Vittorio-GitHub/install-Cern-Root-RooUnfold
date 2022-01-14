# ROOT

```bash
sudo apt-get update
sudo apt-get upgrade
```

## Dependencies

```bash
#obbligatori
sudo apt-get install dpkg-dev
sudo apt-get install cmake
sudo apt-get install g++
sudo apt-get install gcc
sudo apt-get install binutils
sudo apt-get install libx11-dev
sudo apt-get install libxpm-dev
sudo apt-get install libxft-dev
sudo apt-get install libxext-dev
sudo apt-get install libpng
sudo apt-get install libjpeg
sudo apt-get install python
sudo apt-get install libssl-dev
#opzionali
sudo apt-get install gfortran
sudo apt-get install libpcre3-dev
sudo apt-get install xlibmesa-glu-dev
sudo apt-get install llibglew1.5-dev
sudo apt-get install libmysqlclient-dev
sudo apt-get install libfftw3-dev
sudo apt-get install libcfitsio-dev
sudo apt-get install graphviz-dev
sudo apt-get install libavahi-compat-libdnssd-dev
sudo apt-get install libldap2-dev
sudo apt-get install python-dev
sudo apt-get install python-numpy-dev
sudo apt-get install libxml2-dev
sudo apt-get install libkrb5-dev
sudo apt-get install libgsl0-dev
sudo apt-get install r-base
```

## Release

Link: https://root.cern/install/all_releases/ e scarico quella desiderata, ad esempio la V6.24.06

Oppure:

```bash
wget https://root.cern/download/root_v6.24.06.Linux-ubuntu20-x86_64-gcc9.3.tar.gz
```

Estraggo il file scaricato e lancio **thisroot.sh**

```bash
tar -xzvf root_v6.24.06.Linux-ubuntu20-x86_64-gcc9.3.tar.gz
source root/bin/thisroot.sh
```

aggiungo in coda al file **.bashrc** (indicando il percorso di estrazione di root)

```bash
source /home/linus/Downloads/root/bin/thisroot.sh
```

## RooUnfold

```bash
sudo apt install git
```

```bash
# stesso percorso in cui ho estratto root
cd Downloads
git clone https://gitlab.cern.ch/RooUnfold/RooUnfold.git
cd RooUnfold
make
```
