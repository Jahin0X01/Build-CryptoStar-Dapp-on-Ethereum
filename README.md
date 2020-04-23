# Build-CryptoStar-Dapp-on-Ethereum
Udacity DAPP Project 5 (BlockChain nanodgree)

### Instructions
install the npm packages then we will start to run the app
```sh
$ cd Build-CryptoStar-Dapp-on-Ethereum
$ npm install 
$ truffle develop
```
now we have the server in the local host : http://127.0.0.1:9545/ 
we will make a privet network using metamask then add new account (we have privet keys in the termninal) like the follwing table
```
Truffle Develop started at http://127.0.0.1:9545/
Accounts:
(0) 0x5c34a3e39467f7d46b6165c40d846d34b275d48c
(1) 0x7a024745c9abdd18e660506a2db374c92f730dd1
(2) 0x43635e2f03e1708aeefd36dfa6f259c424ec5b3d
(3) 0x61a5d4d1c4c3206b5c9bbf4b7c2daeabc61606bf
(4) 0xe4938e0d927e37465368158e41786bcfd6b71843
(5) 0x990ba1b1751b8751978fc82914cf91a8d2c831bc
(6) 0x6a1973f8a563ce4244af7a911a835a33fb7892b9
(7) 0x9a7de32e7725fd1f03802e2c96ea8cd7001e45c3
(8) 0x14c9fb6f2a5cd9485fd1db2c2221db6188a12411
(9) 0x07259fb1ce63523a32daa3340207a04dce20a598

Private Keys:
(0) fe19c7d71888ffe53643890dd681e00e9f44765ad8747070131724c9d6021728
(1) 68490c19af2251d12e4bd07889e1e20f0361540effc88d73f379fc677fdb5f0f
(2) 3ceadb9bbca8115a55edf146fc7c76a20145b0e2b40336ba37f8ab0cd58458dd
(3) a2b6fbac3b36fa58d9a07b75ded4b14da289f290d46f68fdc8712d6eefac04e5
(4) 10f129b994b13cf2ed81cad150afae0d2e160c16cbab84ce0784abffcb6a6d10
(5) eec1480b6d46a34855174714fcee309fb28ec37d0a3f5691166218bb9820b696
(6) 1f23510a601033dc197a361837c7e7aaedd467de607f8170867112a6f89267a1
(7) 6f6fb1d39a5e426d9225b2eccffb32f4c547eb6f8c77fc7080c71fb4559c781c
(8) 9f2b19b43c2a6d5e42eb95b4b7ec0cdb6b36380a54d021db28da916a66fc671e
(9) 272076676bafb2f07c85739f7c7843392bbbb91426663392dd8975ad086c0029
```
now we will complete in the `truffle develop` cli using the following 
```sh
$ compile
$ migrate --reset
$ test
```
we will keep this terminal and open new tap 
```sh
$ cd app
$ npm run dev
```
