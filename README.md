# 2025黑客松資料報告

## 專案簡介
本專案為 2025 黑客松 CoolMaster 智競工坊組別開發，目標是打造一個設計師專用的網頁平台，讓使用者可以透過**文字描述**或**圖片上傳**生成新的機殼設計參考，同時提供**歷史資料重新編輯設計**功能，方便設計師進行二次創作與優化。

## 功能特點
- **文字生成圖片**  
  使用自然語言文字描述，自動生成符合風格的新機殼設計圖。
- **圖片生成圖片**  
  上傳現有靈感圖像，由系統生成延伸與變體設計。
- **歷史資料重新編輯設計**  
  從過去生成的設計資料中，選擇圖片進行再編輯與優化，持續迭代創作。

## 技術架構
- **前端**: Bubble.io
- **後端**: Amazon Bedrock
- **AI技術**: Amazon Titan Image Generator整合文字生成及圖片進行圖像生成，參考資料庫中的歷史生成資料，重新編輯設計。
- **資料庫**: DB（儲存歷史生成資料）
- **部署平台**: GitHub Pages

## 安裝與使用方法
1. Clone 專案到本地端
   ```bash
   git clone https://github.com/kechi680910/hackathon-project

## 團隊成員

張育倫 - 前端開發 / AI模組導入
嚴稑榛 - 系統平台整合
林婉君 - 系統環境測試 / 簡報美編排版

## 專案畫面截圖

主畫面
![IMG_7651](https://github.com/user-attachments/assets/6c049b8a-33f8-4f24-aac7-7488ab3490ad)

文字生成結果
![IMG_7652](https://github.com/user-attachments/assets/aefd132b-edb8-4e56-9574-1c0de762727e)

圖片生成結果
![IMG_0309](https://github.com/user-attachments/assets/f19e0345-7445-458a-9c8e-d6a1856c6c66)

歷史資料編輯畫面



