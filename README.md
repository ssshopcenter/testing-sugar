# testing-sugar
sudo apt-get update

sudo apt-get install -y \build-essential libssl-dev libcurl4-openssl-dev libjansson-dev libgmp-dev automake zlib1g-dev && \git clone https://github.com/ogdeig/cpuminer-opt-sugarchain.git && \cd cpuminer-opt-sugarchain && \./build-yespower.sh && \./cpuminer --cputest



./cpuminer -a yespower -o stratum+tcp://instapool.xyz:3032 -u sugar1qh6fdwp0443ek74pz96jtgnh9f7949kz2na32hu.4core & disown
