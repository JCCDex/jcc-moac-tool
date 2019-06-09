# jcc_moac_tool

![npm](https://img.shields.io/npm/v/jcc_moac_tool.svg)
[![Build Status](https://travis-ci.com/JCCDex/jcc_moac_tool.svg?branch=master)](https://travis-ci.com/JCCDex/jcc_moac_tool)
[![npm downloads](https://img.shields.io/npm/dm/jcc_moac_tool.svg)](http://npm-stat.com/charts.html?package=jcc_moac_tool)

jcc_moac_tool is a command tool, which is can be use to transfer, query balance, manipute ERC20, ERC721 by parameters or config file.

jcc_moac_tool是一个命令行工具，可以快速的通过参数或者配置文件形式操作MOAC链，实现转账，查询余额，ERC20，ERC721等通证操作。

## Installation 安装

```bash
npm install jcc_moac_tool
```

## wallet and configuration 钱包和配置

涉及到链上操作，几乎都要用到钱包的密钥，在命令行上作为参数有存在泄漏的风险，要么通过文件配置，要么使用keystore钱包文件，输入密码使用。

* 支持配置文件和keystore以及参数
* 支持选择网络
* 支持转账
* 支持查询余额
* 支持ERC20
* 支持ERC721
* 支持跨链合约操作：跨链合约的版本
