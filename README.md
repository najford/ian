pkg update

pkg upgrade -y

pkg install git

pkg install python-pip

git clone https://github.com/najford/ian.git

cd ian

git pull

python3 -m pip install requests

pkg i python-numpy

pip install rich --upgrade

pip install -r requirements.txt

pip3 install pystyle

python main.py
