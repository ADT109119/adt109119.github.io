---
title: 簡單的搶籤工具
date: "2023-09-15 00:00:00+08:00"
draft: false
description: 簡單寫的一個搶籤工具，使用PeerJS連線，方便隨時開房間、設定主題，讓大家搶籤。(僅花兩天的時間隨便做做，介面與功能都待完善)
image: draw_topic.png
tags:
- Vue
- PeerJS
- HTML
- CSS
- JavaScript
- Side Project
role: 個人專案
time: 2023.09.15~2023.09.17
type: Side Project
tag_bg_color: "#ffffff"
tag_text_color: "#000000"
video_link: ""
code_link: "https://github.com/ADT109119/draw_topic"
website_link: "https://adt109119.github.io/draw_topic/"
gallery:
- 299291697-850f2b30-c664-410a-8b60-a195f04a8dca.png
- 299292395-0f4887bf-9b9a-4219-85d5-e1ec87d715ff.png
- 299292766-ebefb784-4d84-456f-8003-790b9a950dba.png
---

# draw_topic

簡單寫的一個搶籤工具，使用PeerJS連線，方便隨時開房間、設定主題，讓大家搶籤。(僅花兩天的時間隨便做做，介面與功能都待完善)

[https://adt109119.github.io/draw_topic/](https://adt109119.github.io/draw_topic/)

![image](299291697-850f2b30-c664-410a-8b60-a195f04a8dca.png)

## 專案用途

此專案提供一個可以簡單開創建一個搶籤房間的工具，房主只需要設定需要的行列數，在設定項目名稱，便可以讓使用者加入，準備搶籤。

## 目前專案功能及進度

目前支援以下幾種功能:

- [x] 設定行列數
- [x] 設定每列的名稱
- [x] 顯示使用者
- [x] 設定目前是否允許搶籤
- [x] 快速創建/加入房間
- [x] 匯出CSV
- [x] 顯示當前房間QR Code

尚待完成:

- [ ] 設定每個用戶可搶數量(目前全部限制只能搶一個)
- [ ] 匯入CSV

## 畫面

> 操作示意 創建/加入房間>可關閉填寫，等到人都加入後再開啟>點選選項搶簽

![image](299291697-850f2b30-c664-410a-8b60-a195f04a8dca.png)
![image](299292395-0f4887bf-9b9a-4219-85d5-e1ec87d715ff.png)
![image](299292766-ebefb784-4d84-456f-8003-790b9a950dba.png)

## 專案技術

- Vue
- PeerJS
- HTML
- CSS
- JavaScript

## 聯絡作者

你可以透過以下方式與我聯絡

- [Email: 2.jerry32262686@gmail.com](mailto:2.jerry32262686@gmail.com)
...

## Project setup

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Lints and fixes files

```
npm run lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).