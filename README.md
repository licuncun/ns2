# ns2
ns2学习相关
Instll ns2 in the ubuntu16.04LTS
sudo apt update
sudo apt upgrade
sudo apt install build-essential
sduo apt install tcl tcl-dev tk tk-dev
sudo apt install libxmu-dev libxmu-headers
tar zxvf ns-allinone-2.35.tar.gz
vi +137 /home/user/ns-allinone-2.35/ns2.35/linkstate/ls.h
#将第137行的     void eraseAll() { erase(baseMap::begin(), baseMap::end()); } 改为      void eraseAll() {this->erase(baseMap::begin(), baseMap::end()); } 
cd /home/user/ns-allinone-2.35
./install

