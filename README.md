# Simple sms bomber

## Installation:

### Linux
#### Debian/Ubuntu :

1. sudo apt update && sudo apt dist-upgrade -yy
2. sudo apt install git python3 python3-pip
3. git clone https://github.com/Snekyy/sms_bomber.git
4. cd ./sms_bomber && pip3 install -r requirements.txt
5. ./bomber.py --help

#### Arch/Manjaro :

1. sudo pacman -Suy git python3 python3-pip
2. git clone https://github.com/Snekyy/sms_bomber.git
3. cd ./sms_bomber && pip3 install -r requirements.txt
4. ./bomber.py --help

#### Fedora :

1. sudo dnf update && sudo dnf upgrade
2. sudo dnf install git python3 python3-pip
3. git clone https://github.com/Snekyy/sms_bomber.git
4. cd ./sms_bomber && pip3 install -r requirements.txt
5. ./bomber.py --help

### Windows:

1. python3 installation - https://docs.python.org/3/using/windows.html
2. python3 -m pip3 install -U pip3
3. git installion - https://git-scm.com/download/win
4. git clone https://github.com/Snekyy/sms_bomber.git
5. cd ./sms_bomber && pip3 install -r requirements.txt
6. python3 bomber.py --help

## Usage :

usage: bomber.py [-h] [-t TARGET]

optional arguments:
  -h, --help            show this help message and exit
  -t TARGET, --target TARGET            target phone number for bombing

Example: ./bomber.py -t 79200112248


Around 70% of this code was taken from impulse - https://github.com/LimerBoy/Impulse

* Special *
In debian gnu/linux you should only do 5 steps, in arch only 4 steps ,but in windows there are 6.
also in linux you can do this only in your terminal, but in windows you should install this from web-sites and fuck your brain.
This means that Linux is much better than Windows, therefore, as a linuxoid, I urge all Windows users to switch to Linux, but this is only one reason, and in fact there is much more. Thank you for attention :)