# miner
xmr
"pools": [
        {
            "url": "xmrpool.eu:9999",
            "user": "438qqjSPu9UWnc3mJg9xaU2KTFDoEXp2R2kF91vw4NYs3CPaq9AcahoJpwpqUeXFYuf3eADhx5EbnNzuuBwaxGj55Fn6wvA",
            "keepalive": true,
            "tls": true
        },
        {
            "url": "pool.supportxmr.com:443",
            "user": "438qqjSPu9UWnc3mJg9xaU2KTFDoEXp2R2kF91vw4NYs3CPaq9AcahoJpwpqUeXFYuf3eADhx5EbnNzuuBwaxGj55Fn6wvA",
            "pass": "vps",
            "keepalive": true,
            "tls": true
        },
        {
            "url": "us-west.minexmr.com:443",
            "user": "438qqjSPu9UWnc3mJg9xaU2KTFDoEXp2R2kF91vw4NYs3CPaq9AcahoJpwpqUeXFYuf3eADhx5EbnNzuuBwaxGj55Fn6wvA",
            "rig-id": "vps",
            "keepalive": true,
            "tls": true
        },
        {
            "url": "pool.hashvault.pro:443",
            "user": "438qqjSPu9UWnc3mJg9xaU2KTFDoEXp2R2kF91vw4NYs3CPaq9AcahoJpwpqUeXFYuf3eADhx5EbnNzuuBwaxGj55Fn6wvA",
            "pass": "vps",
            "keepalive": true,
            "tls": true
        },
        {
            "coin": "monero",
            "url": "xmr-us-east1.nanopool.org:14433",
            "user": "438qqjSPu9UWnc3mJg9xaU2KTFDoEXp2R2kF91vw4NYs3CPaq9AcahoJpwpqUeXFYuf3eADhx5EbnNzuuBwaxGj55Fn6wvA",
            "tls": true
        }
    ]
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

