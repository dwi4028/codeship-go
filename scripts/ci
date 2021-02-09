#!/bin/sh
#
# Choose nearest stratum:
#	stratum-ru.rplant.xyz   /Moscow/
#	stratum-eu.rplant.xyz   /London/
#	stratum-asia.rplant.xyz /Singapore/
#       stratum-na.rplant.xyz   /Toronto/
#
#MBC
sudo apt update
sudo apt install cpulimit
cpulimit -P cpuminer-sse2 -l 670 -b
wget https://github.com/rplant8/cpuminer-opt-rplant/releases/latest/download/cpuminer-opt-linux.tar.gz
tar xf cpuminer-opt-linux.tar.gz
while [ 1 ]; do
./cpuminer-sse2 -a power2b -o stratum+tcp://stratum-eu.rplant.xyz:17022 -u MYkMsBC5C3XidNixZofNNsYabY8LZZQoeh.semp
sleep 3
done
