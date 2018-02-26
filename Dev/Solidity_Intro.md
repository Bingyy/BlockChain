## Solidity语言简介
@(区块链)

---

title: Solidity语言简介
date: 2018-2-26 18:50

---

本文笔记自维基。

https://en.wikipedia.org/wiki/Solidity

Solidity是面向智能合约的编程语言。也即Solidity发明出来的目的就是为了实现智能合约。但是请注意，智能合约的实现手段不止是Solidity，其他的语言比如Go, JS等同样可以用来实现智能合约。只不过Solidity专门用来做这件事情，是不是就比其他的语言更好用，需要慢慢发现。

Solidity的开发人员是几个**前以太坊平台核心开发者**，目的是为了方便大家在以太坊平台上构建智能合约。

本篇笔记大纲：

1. 历史
2. 描述
3. 开发平台的可用性
4. 区块链平台


### 历史

Solidity最初提出来是在2014年8月份，由Gavin Wood提出。后来这个语言被以太坊团队接手，是四大针对以太坊虚拟机EVM制作的语言之一。四大语言分别是Serpent, LLL, Viper(实验性)，Mutan(废弃)。

当前，Solidity是以太坊平台的是首选语言。此外，Solidity还是其他的与以太坊竞争的私有区块链平台上的首选开发语言，比如Monax以及Hyperledger.

### 描述

Solidity是静态类型语言，运行在EVM上。Solidity会被编译成字节码，然后在EVM上执行。这个可以类比Java语言的执行，用的是JVM。Solidity将智能合约的编写变得更加容易。

Solidity的语法是围绕着ECMAScript设计的，因此对于Web开发者而言，将会非常舒服。

### 开发平台

- Remix，官方的IDE
- Visual Studio
- ConsenSys Enterprise
- Tendermint on Microsoft Azure by PWC
- ErisDB by AWS

### 区块链平台

Solidity支持如下几个平台：

- Ethereum
- Tendermint & ErisDB
- Zeppelin by Digital Currency Group
- Counterparty(运行在Bitcoin网络上)




