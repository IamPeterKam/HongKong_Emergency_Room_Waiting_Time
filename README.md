# HongKong_Emergency_Room_Waiting_Time

# 香港急症室等候時間 – 支援網站  
🔗 https://hongkong-emergency-room-waiting-time.netlify.app/

## 私隱政策  
🔗 https://hongkong-emergency-room-waiting-time.netlify.app/privacy

本專案為「香港急症室等候時間」iOS App 提供 **Apple App Store 上架所需的支援網站（Support URL）**，  
內容包含應用程式使用說明、免責聲明及私隱政策。

---

## 📋 專案簡介

此為一個 **純靜態網站（Static Website）**，專為符合 Apple App Store 審核要求而設計，  
目的在於向使用者及 Apple 審核人員清楚說明本應用程式的性質、資料來源及使用範圍。

本網站包含以下頁面：

- **Support Page（index.html）**  
  提供應用程式簡介、資料來源說明及免責聲明

- **Privacy Policy（privacy.html）**  
  說明本應用程式不收集任何個人資料

---

## 📊 資料來源說明（重要）

本應用程式所顯示之急症室等候時間資料，來源自香港政府「開放數據平台（data.gov.hk）」所提供的公開數據：

- **資料集名稱**：急症室等候時間  
- **資料提供單位**：醫院管理局  
- **資料平台**：香港政府開放數據平台  
- **資料集連結**：  
  https://data.gov.hk/tc-data/dataset/hospital-hadata-ae-waiting-time

本應用程式僅作為公開資料的整理與展示工具，  
不會修改、詮釋或推論任何臨床意義。

---

## 🎯 設計原則

- ✅ 符合 Apple App Store Review Guidelines
- ✅ 明確標示為「資訊參考用途」
- ✅ 清楚免責聲明（非醫療診斷、非醫療建議）
- ✅ 採用政府開放數據平台之公開資料
- ✅ 不收集、不儲存、不分享任何個人資料
- ✅ 響應式設計（支援手機與桌面瀏覽）
- ✅ 純 HTML + CSS（無 JavaScript）
- ✅ 可本地預覽、可直接部署至 Netlify

---

## ⚠️ 重要聲明（App 定位）

本支援網站所對應之 iOS App：

- 僅提供 **香港公立醫院急症室等候時間等公開資訊**
- 所有內容 **僅供參考用途**
- **不提供任何醫療建議、診斷、分流或治療指引**
- 實際急症室處理次序由醫護人員根據即時臨床評估決定
- 本應用程式並非由政府或醫療機構營運

---

## 🗂️ 檔案結構
- index.html       （Support Page（使用說明、資料來源與免責聲明））
- privacy.html     （Privacy Policy（私隱政策））

---

## 🖥️ 本地預覽方式

本專案為純靜態網站，可直接於本機預覽：

1. 將專案下載或複製至本機
2. 直接以瀏覽器開啟 `index.html`
3. 無需安裝任何套件或啟動伺服器

---

## 🚀 部署方式（Netlify）

本網站已部署至 Netlify，部署方式如下：

1. 將整個專案資料夾拖曳至 Netlify
2. 自動生成公開網址
3. 將網址填入 App Store Connect：
   - **Support URL** → `/`
   - **Privacy Policy URL** → `/privacy`

---

## 📌 使用範圍

此網站僅作以下用途：

- Apple App Store 上架審核
- 使用者支援與資訊說明
- 公開資料的展示與整理

不作為：
- 醫療用途
- 診斷依據
- 就醫建議
- 商業推廣網站

---

## 📄 授權與聲明

本專案僅用作支援「香港急症室等候時間」iOS App。  
所使用之數據均來自政府開放數據平台，實際內容與準確性以原始資料發布單位為準。

如需轉載或改作其他用途，請自行評估相關法律、資料使用條款及 App Store 審核風險。
