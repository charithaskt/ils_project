# INTEGRATED LIBRARY MANAGEMENT SYSTEM__ILS

> This project is made using python and django
intranet app has all basic models
intranet app is the one where we have customized the django admin interface
accounts has user modules and mail authentication part









You can install Python-3.6 on Ubuntu 18.04 as follows:

wget https://www.python.org/ftp/python/3.6.3/Python-3.6.3.tgz
tar xvf Python-3.6.3.tgz
cd Python-3.6.3
sudo apt-get install -y make build-essential libssl-dev zlib1g-dev libbz2-dev \
libreadline-dev libsqlite3-dev wget curl llvm libncurses5-dev libncursesw5-dev \
xz-utils tk-dev libffi-dev liblzma-dev
./configure --enable-optimizations --with -ensurepip=install
make -j8
sudo make altinstall
python3.6
sudo rm -f usr/bin/python3
sudo ln -s usr/local/bon/python3.6 usr/bin/python3

You can creatre virtual environment and use as follows:

mkdir ~/pyenv
cd ~/pyenv
python3 -m venv ils
cd ils
source ./bin/activate
mkdir projects
cd projects
