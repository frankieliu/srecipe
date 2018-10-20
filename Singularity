Bootstrap:docker
From:ubuntu:latest  

%labels
MAINTAINER Vanessasaur
SPECIES Dinosaur

%environment
RAWR_BASE=/code
export RAWR_BASE

%runscript
echo "This gets run when you run the image!" 
exec /bin/bash /code/rawr.sh "$@"  

%post  
echo "This section happens once after bootstrap to build the image."  
mkdir -p /code
sed -i '/bionic.*universe/s/^#//g' /etc/apt/sources.list
apt-get -y update
apt-get install emacs
apt-get install firefox
apt-get install gnome-terminal
# apt-get install vim
# android-tools-adb
# android-tools-fastboot
# apt-get install aptitude
# apt-transport-https
# blueman
# apt-get install chicken-bin
# apt-get install cmake
# apt-get install code
# apt-get install curl
# docker-ce
# apt-get install dropbox
# apt-get install elixir
# apt-get install emacs
# apt-get install erlang-solutions
# apt-get install esl-erlang
# gamin
# apt-get install gdebi
# apt-get install geeqie
# apt-get install gimp
# apt-get install git
# apt-get install google-chrome-beta
# apt-get install googletest
# apt-get install inkscape
# jq
# apt-get install libcanberra-gtk-module
# apt-get install libgtest-dev
# apt-get install libgtk2.0-cil
# apt-get install libgtk2.0-cil-dev
# apt-get install libgtk2.0-dev
# apt-get install libgtk2.0-doc
# apt-get install lighttpd
# apt-get install mame
# apt-get install maven
# apt-get install meld
# nasm
# apt-get install net-tools
# nfs-common
# apt-get install nodejs
# apt-get install okular-extra-backends
# opensc
# openssh-server
# apt-get install oracle-java10-installer
# playonlinux
# apt-get install r-base
# apt-get install rstudio
# apt-get install scrot
# simplescreenrecorder
# teamviewer
# apt-get install texlive-latex-recommended
# apt-get install tmux
# apt-get install unrar
# apt-get install vlc
# weechat
# apt-get install xclip
# yubico-piv-tool
# apt-get install zoom
# zsnes:i386
echo "RoooAAAAR" >> /code/rawr.sh
chmod u+x /code/rawr.sh