# Scenario
Packet Transmission in a Network Server

This model studies how data packets queue before being processed by a server. The aim is to analyze delays and system efficiency.


## Steps

1. ```git clone https://github.com/Newtonkamau14/packet-transmission ```




## Prerequisites

### Windows

Wireshark [https://2.na.dl.wireshark.org/win64/Wireshark-4.6.4-x64.exe]

ns3 [https://www.nsnam.org/releases/ns-allinone-3.29.tar.bz2]

### Linux


```
sudo apt update
```

```
sudo apt install wireshark -y

```

```
sudo usermod -aG wireshark $USER
```

```
sudo apt install ns3 -y
```

```
sudo apt install -y \
python3 python3-dev python3-pip \
libboost-all-dev \
libgsl-dev \
libxml2 libxml2-dev \
sqlite3 libsqlite3-dev \
libeigen3-dev \
cmake ninja-build git \
doxygen graphviz dia \
texlive texlive-latex-extra texlive-fonts-recommended dvipng latexmk \
sphinx-common python3-sphinx \
gir1.2-gtk-3.0 python3-gi python3-gi-cairo \
libharfbuzz-dev \
qtbase5-dev qtchooser qt5-qmake qtbase5-dev-tools
```

```
./ns3 configure \
--enable-examples \
--enable-tests \
--enable-python
```

```
./ns3 build
```