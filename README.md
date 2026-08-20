Note: PepeCoin / Memetic was bridged to an Ethereum ERC-20 token in 2023. See links on [https://linktr.ee/pepecoins](https://linktr.ee/pepecoins) for more information.

***
# PepeCoin - PEPE  / Memetic - MEME
#### v. 3.1.1.0

PepeCoin, also known as Memetic, launched in 2016, is a digital decentralized crypto-currency, listed as as Memetic / MEME on Bittrex, Upbit, Coinmarkets, and CoinMarketCap, due to political pressure in 2016.

Memetic, AKA PepeCoin, incorporates both blockchain 2.0 and blockchain 3.0 technologies and is under continued development.

Pepecoin / Memetic is a Proof of Stake (POS) cryptocurrency with privacy features and masternode technology. Mastertoad (masternode) and stakers are rewarded for processing transactions and collectively ensuring the security of the network.

Previously, we were a Proof of Stake and Proof of Work hybrid but due to the rise of 51% attacks we have shifted to POS until more technology improvements are discovered.

Pepecoin / Memetic is decentralized, encrypted image storage in IPFS, cryptographically verified against the PepeCoin blockchain. Protect your memes and political information from censorship.

Pepecoin / Memetic is the base infrastructure for the Kekdaq decentralized meme asset exchange.

PepeCoin is a fully open source, decentralized, encrypted project that supports the preservation of all freedom of speech that is within the bounds of US law.

#### Join the offical [Telegram](https://t.me/pepecoins) room for technical support and to participate our community.

See [Bitcointalk ANN](https://bitcointalk.org/index.php?topic=1391598.0) for more details.

***
#### Technical Specifications
#####
 - Default port 29377 
 - RPC port 29376
 - 60 second block time
#####
- Proof of Stake - POS - 7% at block 600,000, reducing yearly.  Currently 3.25% per year, reducing 50% each year
- Proof of Work - POW ended at block 1,700,000 in late 2018 to reduce chain reorganization issues and improve the stability of Kekdaq
- X11 mining algorithm (Sequential mixing of Blake256, BMW, Grostl, JH, Keccak, Skein, Luffa, Cubehash, SHA-3, SIMD, and ECHO)
- PEPE / MEME is Full Proof-of-Stake beginning at block 1700000. The POW reward rate was migrated to the POS reward, at 3.25% per year, reducing 50% each year.
- 600 confirmations for newly Proof of Stake minted blocks
- 6 hour minimum stake age with 12 hour average
- Additional security improvements
  
 **Features**

- Decentralized encrypted private messaging
- Stealth Addresses
- Fully blockchain based, public decentralized encrypted messaging chat wall in wallet
- In wallet public messaging wall  - set messagewall=1 in pepecoin.conf to enable
- JSON-RPC functions to externally query all public wall messages
- Integrated block explorer
- Image timestamping on the blockchain for proof of ownership
- In-wallet hash image verification checking functions
- JSON-RPC functions to externally query blockchain for hashed image datas
- IPFS-based data hashing storage currently under development
- Integrated Bittrex trading functions
- Mastertoads pay 37.5% of all mined POS blocks, distributed among MT owners
- Kekdaq decentralized meme "asset" platform live in testing / development stage

See [bitcointalk.org](https://bitcointalk.org/index.php?topic=1391598.0) post for more info: https://bitcointalk.org/index.php?topic=1391598.0

-------------------------------
## Downloading & Compiling
-------------------------------
 
### Windows Wallet

[https://github.com/memeticofficial/pepecoin-memetic/releases](https://github.com/memeticofficial/pepecoin-memetic/releases)


#### Linux Builds:

PepeCoin uses libsecp256k1, libgmp, Boost1.55+, Openssl1.01, Berkeley DB 4.8+, and QT5 to compile.

Ubuntu 18.04+ or Debian 9+ is recommended.

#### Instructions for Building Command Line Daemon
>
>sudo apt-get install build-essential libtool autotools-dev automake pkg-config libevent-dev bsdmainutils libboost-system-dev libboost-filesystem-dev libboost-chrono-dev libboost-program-options-dev libboost-test-dev libboost-thread-dev libminiupnpc-dev libgmp3-dev libdb-dev libdb++-dev libgmp3-dev lzma-dev libssl1.0-dev zlib1g-dev zlib1g libgmp-dev 
>	
>git clone https://github.com/memeticofficial/pepecoin-memetic.git
>
>cd pepecoin-memetic/src
>
>make -f makefile.unix USE_UPNP=-
>
>strip pepecoind
>

after successfully compiling you can may move pepecoind to run "globally" as an application by doing the following
>cd pepecoin-memetic/src
>
>mv pepecoind /usr/bin

You can also the shell script at https://gist.github.com/cryptopepe/82b59b51680e13e5f1e08224bfdd71fc to compile (remember to chmod +x to make script executable) for more info visit https://snap.memetic.ai/cheatsheet.txt

#### Instructions for Building GUI Wallet

>sudo apt-get install libqt5gui5 libqt5core5a libqt5dbus5 qttools5-dev qttools5-dev-tools libprotobuf-dev protobuf-compiler qt5-default build-essential libtool autotools-dev automake pkg-config libevent-dev bsdmainutils libboost-system-dev libboost-filesystem-dev libboost-chrono-dev libboost-program-options-dev libboost-test-dev libboost-thread-dev libminiupnpc-dev libgmp3-dev libdb-dev libdb++-dev libgmp3-dev lzma-dev libssl1.0-dev zlib1g-dev zlib1g libgmp-dev
>
>git clone https://github.com/memeticofficial/pepecoin-memetic.git
>
>cd pepecoin 
>
>qmake
>
>make -j2 -f Makefile USE_UPNP=0
>
--------------------

### Websites
https://pepecoin.io

https://kek.space

https://memetic.ai

### Social

[Twitter](https://twitter.com/pepecoins) 

[Telegram](https://t.me/pepecoins) - Official MEME / PEPE Support and Community Room

### Exchanges

[Bittrex (USA)](https://bittrex.com/Market/Index?MarketName=BTC-MEME) -- Largest regulated and secure US exchange

[Upbit (ASIA)](https://upbit.com/exchange?code=CRIX.UPBIT.BTC-MEME) -- Popular South Korean exchange

[Changenow (Worldwide)](https://changenow.io/) -- Shapeshift type service accepting cc purchases

[Coinswitch (Worldwide)](https://coinswitch.co/) -- Shapeshift type service

[Coinexchange (EU)](https://www.coinexchange.io/market/MEME/BTC)

<s>[Cryptopia](https://www.cryptopia.co.nz/Exchange?market=PEPE_BTC)</s> -- Remove requested after exchange hacked

### Block Explorer

[http://explorer.memetic.ai/](http://explorer.memetic.ai/)

### Charts

[CoinMarketCap](https://coinmarketcap.com/currencies/pepecoin/)


### Websites 
[Main Site](https://pepecoin.io)

### Social

[Twitter](https://twitter.com/pepecoins) 

[Telegram](https://t.me/pepecoins)  - Official MEME / PEPE Support and Community Room

# Links

[Windows Wallet DEPRECIATED](https://github.com/pepeteam/pepecoin/releases) 

[Bitcointalk ANN DEPRECIATED](https://bitcointalk.org/index.php?topic=1391598.0) 


------------------
------------------
Seednodes
```addnode=seed.memetic.ai```

Bootstrap File 
[Latest](https://snap.memetic.ai/latest.tar.gz/)
------------------
------------------
PepeCoin Logo (V1 & V2) & Memetic Logo (V2 Full)
------------------
![Pepecoin](https://snap.memetic.ai/images/256x.png "Pepecoin") 
![Pepecoin v2](https://i.imgur.com/xnSJvT9.jpg  "Pepecoin-v2") 
![Memetic v2](https://i.imgur.com/Nepi5t1.png  "Memetic-v2")


------------------
------------------
License 
------------------
##### Open-source software released under the GNU GPL v2 license ALL RIGHTS RESERVED ##### 

Copyright (c) 2015-2024 PepeCoin Developers 

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

The above copyright notices and this permission notice shall be included in
all copies or substantial portions of the Software.

See LICENSE for additional information and all COPYING and Copyright

