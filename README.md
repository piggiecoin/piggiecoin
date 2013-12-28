# PiggieCoin [PIG]

Piggiecoin is a new coin based on Litecoin. You can mine it with your CPU or with your graphics card.

##Specifications

Scrypt Proof of Work

30 Seconds Block Targets, 3 Hour Diff Readjustments

Special reward system: Random block ultra high rewards

1-50,000: 0-10,000,000 PiggieCoin Reward

50,001 — 100,000: 0-5,000,000 PiggieCoin Reward

100,001 — 150,000: 0-2,500,000 PiggieCoin Reward

150,001 — 200,000: 0-1,250,000 PiggieCoin Reward

200,001 — 250,000: 0-625,000 PiggieCoin Reward

250,001 — 300,000: 0-312,500 PiggieCoin Reward

300,000+: 100,000 Reward (flat)

## How to build

    sudo apt-get install build-essential \
                         libssl-dev \
                         libdb5.1++-dev \
                         libboost-all-dev \
                         libqrencode-dev \
                         libminiupnpc-dev

    cd src/
    make -f makefile.unix USE_UPNP=1 USE_IPV6=1 USE_QRCODE=1

### Ports
RPC 28888
P2P 28889

## License
Piggiecoin is released under the terms of the MIT license. See [COPYING](COPYING)
for more information or see http://opensource.org/licenses/MIT.


