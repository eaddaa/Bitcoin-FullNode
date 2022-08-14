# Bitcoin-FullNode

## requirements:


```
2 vCPU
2 GB RAM
400 GB SSD
```
## set up full node:

```
curl https://bitnodes.io/install-full-node.sh | sh
```

## Log control:
```
tail -f /root/bitcoin-core/.bitcoin/debug.log
```

![image](https://user-images.githubusercontent.com/101149671/184448757-fd5ef32e-212b-4d94-abdb-6967bd0a1627.png)

## Latest block 749,176,  [Explorer Link](https://explorer.btc.com/btc/blocks)

## stop:
```
cd /root/bitcoin-core/bin && ./stop.sh
```
## to remove:
```
./install-full-node.sh -u
```

## Short description:

* active node: 13367
* Full node : 12021
* pruning node: 1278



