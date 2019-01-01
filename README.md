Voytek (fork of PIVX) integration/staging repository
======================================

Dependencies:

sudo add-apt-repository ppa:bitcoin/bitcoin

sudo apt update && sudo apt upgrade

sudo apt install -y build-essential libtool autotools-dev autoconf pkg-config libssl-dev libboost-all-dev software-properties-common libdb4.8-dev libdb4.8++-dev libqt5gui5 libqt5core5a libqt5dbus5 qttools5-dev qttools5-dev-tools libprotobuf-dev protobuf-compiler libqrencode-dev libzmq3-dev libminiupnpc-dev

sudo apt install ufw

sudo ufw allow 17171/tcp && sudo ufw enable
