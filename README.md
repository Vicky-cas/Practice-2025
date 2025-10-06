## Practice-2025  
This repository includes some little projects that display the practice I done recently  
#### 1. 匯率爬蟲 (Exchange Rate Crawler)  
目的：爬取匯率資訊，示範如何使用 BeautifulSoup 抓取網頁資料。
重點技術：
requests 發送 HTTP 請求
BeautifulSoup 解析 HTML
成果：自動抓取美金匯率，並輸出為乾淨可用的資料。

#### 2. 天氣爬蟲 (Weather API Crawler)
目的：透過公開 API 取得天氣資訊，展示如何使用 API 取代傳統爬蟲。
重點技術：
使用 requests 呼叫 API
解析 JSON 格式資料
成果：輸出當日或指定城市的即時天氣資訊。

#### 3. 澳洲天氣預報 (Australia Rain Prediction - Machine Learning)
目的：以澳洲天氣資料集為基礎，預測當天是否會下雨。
重點技術：
pandas 資料處理
scikit-learn：前處理 (StandardScaler, OneHotEncoder)
建立 Pipeline 與 GridSearchCV
模型：RandomForestClassifier
成果：
模型準確率約 84%
視覺化 混淆矩陣 與 特徵重要性
展示完整 ML workflow (資料分割 → 前處理 → 訓練 → 評估 → 視覺化)
