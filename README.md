## ⚡ INSTALL TOOL ON TERMUX

```
pkg update
pkg upgrade

pkg install python
pkg install git

pip install requests
pip install bs4
pip install futures
pip install mechanize
```

## 🚀 DOWNLOAD & RUN

```
rm -rf BNB
cd
git clone https://github.com/ASIF-KHAN0-320-420/BNB.git
cd BNB
python Asif.py
```








# PYCDC Installation — Termux

## Basic Setup

- `pkg update`
- `pkg install git cmake make clang`
- `git clone https://github.com/zrax/pycdc.git`
- `cd pycdc`

## Original PYCDC — Full Installation

- `pkg update && pkg upgrade -y`
- `pkg install git clang cmake make -y`
- `git clone https://github.com/zrax/pycdc.git`
- `cd pycdc`
- `cmake -B build`
- `cmake --build build`
- `cp build/pycdc $PREFIX/bin/`
- `cp build/pycdas $PREFIX/bin/`

## Package Repair

- `pkg update -y`
- `pkg upgrade -y`
- `apt --fix-broken install -y`
- `pkg install python python-ensurepip-wheels -y`
- `pkg install cmake libarchive jsoncpp libuv rhash -y`

## Original PYCDC — Build and Use

- `cd ~`
- `git clone https://github.com/zrax/pycdc.git`
- `cd pycdc`
- `cmake -B build`
- `cmake --build build`
- `cp build/pycdc build/pycdas $PREFIX/bin/`
- `pycdc /sdcard/file_decoded.pyc > /sdcard/file_normal.py`

## Python Package Removal / Repair

- `dpkg --remove --force-depends python3.13`
- `dpkg --configure -a`
- `apt --fix-broken install -y`
- `pkg install python python-ensurepip-wheels -y`
- `pkg install libarchive jsoncpp libuv rhash -y`
- `pkg install cmake -y`

## New — PYCDC Rapid

- `git clone https://github.com/Youchuang-Studio/pycdc-rapid.git`
- `cd pycdc-rapid`
- `cmake -B build`
- `cmake --build build`
- `cp build/pycdc $PREFIX/bin/pycdc`
- `cp build/pycdas $PREFIX/bin/pycdas`
- `pycdc /sdcard/file_decoded.pyc > /sdcard/file_normal.py`
