# 🍦-node

> A naive and simple way for get a full-node bitcoin w/ xpub address

## must have
- multi-arch compatible (arm & amd64) docker friendly
- docker/bitcoin-core
- docker/bitcoin-storage
- docker/tor
- docker/app : a mobile-first app for add/watch your `XPUB`s and also for create/broadcast [PSBT](https://github.com/bitcoin/bitcoin/blob/master/doc/psbt.md)s.
- docker/torrent : if you want share your bitcoin-storage helping other to a fastest sync
