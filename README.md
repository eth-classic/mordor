# Mordor
[![Join the chat at https://gitter.im/eth-classic/mordor](https://badges.gitter.im/eth-classic/mordor.svg)](https://gitter.im/eth-classic/mordor?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

<p align="center">
<img src="https://github.com/stevanlohja/ETC_Gifs/blob/master/mordor_testnet/mordor_logo.png?raw=true">
</p>

<center>
  <h3 align="center">Mordor</h3>
  <p align="center">
    An Ethereum Classic PoW testnet to replace Morden.
    <br />
    <a href="https://mordorexplorer.ethernode.io/">Mordor Explorer</a>
    ·
    <a href="https://github.com/eth-classic/mordor/issues/new">Create an Issue</a>
  </p>
</center>

_Launch: October 3, 2019 at ETCSummit. [eth-classic/mordor#1](https://github.com/eth-classic/mordor/issues/1)_

- Frontier: `0`
- Homestead: `0`
- GasReprice: `0`
- Diehard: `0`
- Gotham: `0`
- Defuse Difficulty Bomb: `0`
- Atlantis: `0`
- Agharta: `301_243`

### Genesis hash

```
0xa68ebde7932eccb177d38d55dcc6461a019dd795a681e59b5a3e4f3a7259a3f1
```

### Parity Ethereum

Minimum required version: `v2.5.8`

```
parity --chain ./parity.json --port 30000
```

### Geth Classic

Minimum required version: `v6.0.9`

```
geth --chain ./gethc.json --port 31000
```

### Multi-Geth

Minimum required version: `v1.9.3`

```
geth init ./mgeth.json
geth --networkid 7 --port 32000
```

### IOHK Mantis

_Mantis no longer supports Ethereum Classic chains._

### Hyperledger Besu (a.k.a. Pantheon)

_Besu does not support Ethereum Classic yet._
