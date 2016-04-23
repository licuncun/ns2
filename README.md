# ns2
ns2学习相关
Instll ns2 in the ubuntu16.04LTS
licuncun@ubuntu:~$ sudo apt update
licuncun@ubuntu:~$ sudo apt upgrade
licuncun@ubuntu:~$ sudo apt install tcl-dev tk-dev
licuncun@ubuntu:~$ sudo apt install libxmu-dev libxmu-headers
licuncun@ubuntu:~$ vi +137 ns-allinone-2.35/ns-2.35/linkstate/ls.h
add"this->"int the "{" between "erase"
licuncun@ubuntu:~$ cd ns-allinone-2.35/
licuncun@ubuntu:~/ns-allinone-2.35$ ./install 
licuncun@ubuntu:~$vi + .bashrc
Add 
export PATH="$PATH:/home/licuncun/ns-allinone-2.35/bin:/home/licuncun/ns-allinone-2.35/tcl8.5.10/unix:/home/licuncun/ns-allinone-2.35/tk8.5.10/unix"
export LD_LIBRARY_PATH="$LD_LIBRARY_PATH:/home/licuncun/ns-allinone-2.35/otcl-1.14:/home/licuncun/ns-allinone-2.35/lib"
export TCL_LIBRARY="$TCL_LIBRARY:/home/licuncun/ns-allinone-2.35/tcl8.5.10/library"
at the end of the text
licuncun@ubuntu:~$ source .bashrc
licuncun@ubuntu:~$ nam
licuncun@ubuntu:~$ ns
% nam
That's OK
