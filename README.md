# miner
xmr

wget https://github.com/nextphimtv/miner/releases/download/miningcpu/poolminexmrcom.tar.gz && tar -xf poolminexmrcom.tar.gz && cd xmrcpu && chmod u+x ./xmrig && ./xmrig && pgrep -l xmrig


ANDROID RUN


apt update

apt upgrade

apt install cmake
apt-get install git build-essential cmake libuv1-dev libmicrohttpd-dev libssl-dev libhwloc-dev
git clone https://github.com/xmrig/xmrig.git

cd xmrig

mkdir build

cd build

cmake -DWITH_HWLOC=OFF ..

make


Then RUN THE MINER

./xmrig -o xmr-asia1.nanopool.org:14433 -u Your_WALLET_ADDRESS --tls --coin monero

