# Academic Projects

本頁整理我在長庚大學資訊工程學系期間參與的研究、畢業專題與課程實作。

內容以實際參與之研究與專案為主。若為共同專案，會連結至原始團隊 Repository，並盡量註明我的工作內容；部分課程成果與報告則整理於本 Repository 中，作為學習歷程與實作紀錄。

**林冠妤｜長庚大學 資訊工程學系**

---

## Research

### FreqFuseNet — 頭頸部 3D 醫學影像分割

FreqFuseNet 以頭頸部薄壁危及器官（Organs at Risk, OAR）分割為研究問題，探討 FFT 與 FcaNet 頻率分支在特徵融合時的尺度差異，並透過尺度正規化與固定殘差融合改善雙頻特徵整合。

研究過程中參與模型實驗、消融分析、基準方法比較、結果整理與論文相關工作。

- **研究領域：** Medical Image Segmentation、Deep Learning、3D CT
- **資料集：** SegRap2023
- **研究內容：** 頻率特徵融合、Ablation、Benchmark、模型驗證
- **研究成果：** medRxiv Preprint；Computer Methods and Programs in Biomedicine 投稿中
- **GitHub：** [freq-spatial-headneck-seg](https://github.com/Tiffanyxxx3238/freq-spatial-headneck-seg)
- **Preprint：** [FreqFuseNet — medRxiv](https://www.medrxiv.org/content/10.64898/2026.07.09.26357642v2)

---

## Graduation Project

### PineNose — 鳳梨電子鼻非破壞性熟度檢測系統

PineNose 為結合氣體感測、機器學習、影像辨識與邊緣運算的鳳梨智慧檢測系統。系統整合 Arduino Mega、Raspberry Pi、氣體感測器陣列、熟度分類模型、影像辨識模型、Flask API、Web 介面與雙端 App。

我在專題中擔任組長，主要參與系統整合、硬體與感測器整合、資料蒐集、後端與資料庫、Docker 部署、雙模態功能串接，以及系統測試與問題排查。

- **感測端：** Arduino Mega 2560、MQ2、MQ3、MQ9、MQ135、TGS2602、BME280
- **邊緣運算：** Raspberry Pi 3
- **熟度模型：** ExtraTrees
- **影像模型：** YOLOv8n、EfficientNet-B0
- **系統：** Flask、Database、Docker、Web / Mobile App
- **成果：** 2026 農業創新科技競賽金獎
- **團隊 GitHub：** [electronic-nose-pineapple-ripeness-assessment](https://github.com/icguproject25-droid/electronic-nose-pineapple-ripeness-assessment)
- **專題網站：** [PineNose Official Site](https://icguproject25-droid.github.io/pinenose_official_site/)
- **展示影片：** [YouTube Demo](https://www.youtube.com/watch?v=X8AnxetTEi4)

---

## Coursework Projects

### 人工智慧分類專題

**Spatiotemporal Crime Classification with Transfer Learning**

以多城市犯罪資料建立時空分類問題，並分析模型於不同城市資料條件下的分類與遷移表現。

此為共同課程專案，主要 Repository 由組員帳號維護，因此 Git commit 紀錄不完全代表實際工作分配。

**我的參與內容：**
- 參與題目與實驗方向討論
- 參與程式架構與分析流程規劃
- 參與程式撰寫與結果整理
- 搜尋與整理城市犯罪資料來源
- 將模型輸出與分析結果整理為簡報與 Word 報告
- 參與專題成果討論與報告準備

- **課程：** 人工智慧分類專題
- **授課教師：** 萬書言教授
- **課程成績：** 94 / 100
- **團隊 GitHub：** [spatiotemporal-crime-transfer-learning](https://github.com/Tiffanyxxx3238/spatiotemporal-crime-transfer-learning)
- **課程成果文件：**
  - [期末專題簡報](./ai-classification/AI_Project_Presentation.pptx)
  - [互動式犯罪預測地圖操作說明](./ai-classification/Crime_Prediction_Map_Guidance.pdf)

> 目前團隊 Repository 已包含課程後續持續整理與擴充之內容；本頁所列個人工作以當時實際參與範圍為準。

---

### 網頁文字探勘

**Airline Reviews Text Mining**

以航空公司評論資料進行文字探勘與情緒分析，包含 TF / TF-IDF、VADER、LDA、BERTopic 與互動式 Dashboard。

我在團隊中負責 **Member B** 的工作內容，包括 TF / TF-IDF、VADER 情緒分析、LDA 主題分析及相關結果整理。

- **內容：** Text Mining、TF-IDF、VADER、LDA、Dashboard
- **GitHub：** [Airline-Review-Text-Mining](https://github.com/lin-jessic/Airline-Review-Text-Mining)
- **線上 Dashboard：** [Airline Reviews Text Mining Dashboard](https://lin-jessic.github.io/Airline-Review-Text-Mining/%E5%AD%B8%E5%A7%8A/dashboard_2/index.html)

---

### 網頁程式設計期末專題

以 React 建立互動式創作網站，包含 3D 明信片工作台、拍貼機、個人儲存空間與 Community Wall，並以 Firebase 完成公開部署。

**我的主要工作：**
- 建立網站整體初步架構
- 使用 React 建立前端框架
- 使用 `.jsx` 撰寫畫面與互動邏輯
- 實作登入、註冊與頭像選擇功能
- 建立 Postcard Studio、Photo Booth Studio、My Storage、Community Wall 等主要分頁
- My Storage 支援作品儲存、刪除與下載
- Community Wall 支援作品發布、留言與按讚
- 建立 3D 明信片工作台
  - 正反面切換
  - 文字輸入
  - 拖曳印章
  - 撤銷印章
  - 360 度預覽
  - 下載與儲存
- 建立 3D 拍貼機場景動畫
  - 上傳照片
  - 3-Cut / 4-Cut 版型切換
  - 下載與儲存
- 使用 Firebase Hosting 部署網站
- 修正 Community Wall，使不同使用者能看到彼此發布之作品、留言與按讚內容
- 與組員共同修正手帳作品儲存至 My Storage 的問題

- **GitHub：** [Web-Programming](https://github.com/lin-jessic/Web-Programming)
- **公開網站：** [Stamp Studio Online](https://web13-practice.web.app)

---

### 軟體工程

課程期末專題依授課教師指定題目，進行威秀影城網站功能與介面復刻。
依課程指定題目，以威秀影城網站為參考進行功能與介面實作。專案由團隊共同開發，包含電影資訊、影城資訊、場次、會員、訂票與訂單等網站功能，並完成使用手冊與系統測試報告。
原始團隊 Repository 為 Private，因此另整理本人課程期間參與之版本，作為課程成果與學習紀錄。
- **原始 GitHub：** [software_engineering_new](https://github.com/rebeccahou0424/software_engineering_new)
- **課程：** 軟體工程
- **專案形式：** 團隊期末專題
- **主要內容：** Web Development、Database、Software Testing、Team Development
- **GitHub：** [Software-Engineering-Cinema-Website](https://github.com/lin-jessic/Software-Engineering-Cinema-Website)

> 此 Repository 目前為 Private；若無存取權限，請參考本 Repository 中整理之課程報告。

---

## Embedded / Systems Coursework

以下課程之期末專題或實作目前仍在整理中，之後將依原始程式碼與報告建立獨立 Repository 或補充成果連結。

### 微算機實驗
- 8051 微控制器
- Embedded C
- 周邊控制與實驗
- **授課教師：** 張哲維教授
- **主要平台：** 8051
- **撰寫語言：** 組合語言、C語言
- **內容：** 微控制器程式設計、硬體控制與實驗；主要專題為:期中專題-貪食蛇、期末專題-音樂盒(音樂卡片)。
- **GitHub：** [8051-Microcomputer-Lab](https://github.com/lin-jessic/8051-Microcomputer-Lab)

### 軟硬體協同設計
- 軟硬體介面與協同設計
- 系統實作
- **授課教師：** 謝萬雲教授
- **GitHub：** 整理中

### 計算機網路
以 C++ 實作可供網站離線瀏覽的 Web Crawler / Downloader。依課程規格，不使用現成 HTTP 函式庫，而是透過 WinSock 自行建立連線、產生 HTTP GET Request 並解析 Response。

專題進一步實作 HTML 連結解析、遞迴 Crawling、相對與絕對 URL 處理，以及多執行緒檔案下載、進度監控、續傳、檔案類型與大小篩選等功能。

- **課程：** 計算機網路
- **授課教師：** 李春良教授
- **語言：** C++
- **主要內容：** HTTP、WinSock、Web Crawling、Multi-threading、URL Parsing
- **專案形式：** 個人期末專題
- **GitHub：** [CPP-Web-Crawler-Downloader](https://github.com/lin-jessic/CPP-Web-Crawler-Downloader/tree/main)

### 系統程式
使用 Python 與 Tkinter 實作簡易 SIC/XE Assembly 解譯器，可載入、編輯與執行 `.asm` 測試程式，並以程式模擬 SIC/XE 暫存器與記憶體狀態。
實作過程包含 Assembly 程式解析、資料定義處理、Instruction 執行流程，以及 GUI 指令操作介面，並附三組 `.asm` 測試程式驗證執行結果。

- **主要內容：** SIC/XE、Assembly Parsing、Register / Memory Simulation、Interpreter
- **語言：** Python
- **GUI：** Tkinter
- **開發環境：** Visual Studio Code
- **GitHub：** [SICXE-Interpreter](https://github.com/lin-jessic/SICXE-Interpreter/blob/main/README.md)

---

## Additional Coursework Repositories

以下 Repository 主要為課堂練習、測驗與作業紀錄，因此統一整理於此，不列為主要專題成果。
### 多媒體資訊概論
- 三次課程作業
- **GitHub：** 整理中

### 計算機概論
- [CS101](https://github.com/lin-jessic/CS101)
- [cs101-2025](https://github.com/lin-jessic/cs101-2025)

### 網頁程式設計課堂練習
- [Webp2026](https://github.com/lin-jessic/Webp2026)

### 資料結構與演算法
- [CS101](https://github.com/lin-jessic/CS101)
- [cs101-2025](https://github.com/lin-jessic/cs101-2025)
---

## Notes

本頁主要作為研究、專題與課程成果之索引。

共同專案之程式碼可能由團隊共用帳號或組員帳號維護，因此 Git commit 紀錄不一定完整反映個人實際參與內容；個人工作項目以課程分工、報告及實際完成內容為依據。

尚未公開或尚未整理完成之課程成果，會在確認程式碼、文件與授權內容後陸續補充。
