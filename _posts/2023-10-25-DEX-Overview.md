---
layout: post
title: DEX 综述【Builder DAO 投研系列第二课笔记】
date: 2023-10-25 18:11
categories: **投研**
---

> 文章大纲：
> 1. DEX 概念含义
> 2. DEX 做市算法
> 3. DEX 代币经济学
> 4. DEX 未来发展

## 一、DEX 介绍

### DEX 基本概念

DEX 的全称是去中心化交易所，它由两个部分构成：交易所和去中心化。

首先，DEX 是一种交易所。因此，在用户端，它能够为用户提供数字货币的交换服务。而在 LP 端，它也能够为做市商提供存储资金的凭证，帮助他们获得分红。

其次，DEX 以去中心化的方式实现交易所的功能。它表现为，用户无需借助第三方平台完成交易，而是直接借助 DEX 所集成的交易功能，本质上是一种点对点的交易。

### DEX 核心价值

去中心化交易所（DEX）在中心化交易所（CEX）的交易模式上做出了改进。

传统的中心化交易所，通常会采用委托订单（Order Book）的方式进行交易。它表现为，同一个币种会产生多个的双向报价，从而产生一定的交易深度和流动性。

委托订单这一模式的优势在于，能够让交易双方都已满意的价格完成交易。但不足在于，如果交易深度不足，会导致长时间无法完成订单。

而去中心化交易所的出现，让交易模式变成了自动做市的模式（AMM）。它表现为，流动性提供者（LP）首先向流动池中注入资金，出现价格，然后再由用户决定是否要参与这个流动性池来完成交易。

也就是说，DEX 的核心价值之一是根据流动性自动计算资产价格，而无需等待交易双方协商出一个价格，这种模式让交易变得更加便捷。

## 二、DEX 做市算法

### 恒定乘积算法

恒定乘积(Constant Product)算法是指，当流动池初始化后，会根据代币的数量计算出一个恒定的乘积，再根据该乘积去计算每次交易后应当获得的数量。

举个例子，如果代币 A 和代币 B 在交易池中的初始数量分别是 x 和 y，并定义它们乘积为 $x * y = k$，那么当用户向交易池中存入数量为 a 的代币 A 后，他所应当获得的代币 B 的数量是：$y - \frac{k}{x+a}$。

### 集中流动性算法

集中流动性（Concentrated Liquidity）算法是对恒定乘积算法的改进。

在恒定乘积算法中，流动性均匀地分布在每一个价格当中。好处是在任何情况下，我们都可以通过流动性池，兑换到所需代币。但不足在于，资金利用效率太低，

## 三、DEX 代币经济学



> 附：课程[视频链接](https://www.aliyundrive.com/s/6V2a4stVfvQ)