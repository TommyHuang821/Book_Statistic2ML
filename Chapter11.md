---
title: 'Book_Statistic2ML_Chapter11'
disqus: hackmd
---
[讀者天地 - 機器學習的統計基礎](https://hackmd.io/@TommyHuang/book_statistics2ML)
> [name=黃志勝 Chih-Sheng (Tommy) Huang]
* [作者Medium Blog](https://chih-sheng-huang821.medium.com/)

本書「機器學習的統計基礎」出版社為旗標科技股份有限公司

**此份筆記為[讀者天地 - 機器學習的統計基礎](https://hackmd.io/@TommyHuang/book_statistics2ML)用來作為書本內容修正紀錄**

---
[TOC]
# 第 11 章神經網路倒傳遞學習法
## 11.1 最小化損失函數以找出權重參數
## 11.2 隱藏層到輸出層wkj的梯度(∇wkj)
### 11.2.1 計算第一項(∂E∂zj)
### 11.2.2 計算第二項(∂zj∂wkj)
### 11.2.3 得到∇wkj
## 11.3 輸入層到隱藏層vik的梯度(∇vik)
### 11.3.1 計算第一項(∂E∂zj)
### 11.3.2 計算第二項(∂zj∂sk)
### 11.3.3 計算第三項(∂sk∂vik)
### 11.3.4 得到∇vik
### 11.3.5 小結
## 11.4 前向傳遞與倒傳遞範例實作
### 11.4.1 前向傳遞計算預測值
### 11.4.2 用倒傳遞學習法反推以更新權重
## 11.5 梯度消失與梯度爆炸



###### tags: `Book_Statistic2ML`
