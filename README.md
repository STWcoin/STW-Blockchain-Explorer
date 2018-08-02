# STWcoin-Blockchain-Explorer
Block explorer for STWcoin CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon stwcoind. It should be accessible from the Internet. Run stwcoind with open port as follows:
```bash
./stwcoind --restricted-rpc --enable-cors=* --enable-blockchain-indexes --rpc-bind-ip=0.0.0.0 --rpc-bind-port=31458
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.
