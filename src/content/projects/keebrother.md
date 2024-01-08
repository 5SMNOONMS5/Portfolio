---
title: 紀氏五金
description: 紀氏五金品牌的形象網站
header: https://raw.githubusercontent.com/5SMNOONMS5/portfolio/main/resources/projects/keebrother/keebrother1.png
type: Backend
category: Side Project
tags:
  - Laravel
createdAt: 2023-03-11T13:32:52.449Z
---

### 前台

[網站連結](https://keebrother.com.tw/)

### 專案範疇

負責開發給內部使用的後台，以及 API 給 前端使用

### 示意圖

<smart-figure src="https://raw.githubusercontent.com/5SMNOONMS5/portfolio/main/resources/projects/keebrother/keebrother2.png"></smart-figure>
<smart-figure src="https://raw.githubusercontent.com/5SMNOONMS5/portfolio/main/resources/projects/keebrother/keebrother3.png"></smart-figure>
<smart-figure src="https://raw.githubusercontent.com/5SMNOONMS5/portfolio/main/resources/projects/keebrother/keebrother4.png"></smart-figure>

### 後端技術細節

此專案幾戶所有資料都是透過 API，都可在後台 CRUD

由於舊網站是 wordpress，在處理資料轉移的過程中使用 excel 上傳，並且花蠻多時間跟 PM 溝通 excel 上傳的格式以及規則

excel 規則部分包含處理 **圖文編輯器內圖片路徑**、**影片 youtube 鑲嵌轉換**、**多檔案格式**

至於此專案有嘗試使用之前沒用過的服務

* AWS S3
* [Scribe API Docs](https://scribe.knuckles.wtf/laravel/documenting)

[Scribe](https://scribe.knuckles.wtf/laravel/documenting) 我覺得很好用，相比 swagger 語法相對簡單非常多

對前端極度友善，我最喜歡的就是可以直接客製化產生對應的程式碼給前端複製貼上，大大加速雙方開發流程

專案前端則使用 [Nuxt3](https://nuxt.com/)，考量未來客人可能有 SEO 需求，而產生程式碼範例如下圖

<smart-figure src="https://raw.githubusercontent.com/5SMNOONMS5/portfolio/main/resources/projects/keebrother/keebrother5.png"></smart-figure>

### 使用技術

* Server
  * Linode
  * AWS S3

* 後端
  * [Livewire](https://laravel-livewire.com/)

* API 文檔
  * [Scribe API Docs](https://scribe.knuckles.wtf/laravel/documenting)

* Development platform
  * [Netlify](https://www.netlify.com/)
