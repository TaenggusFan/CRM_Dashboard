# 資料分析專案名稱

【**顧客洞察與管理儀表板**】

## 專案概述

利用客戶數據進行全面分析，有效地管理客戶關係，提升客戶滿意度和忠誠度，並最終提高銷售表現。

## 專案結構

一、專案流程  
流程 1.數據集  
流程 2.資料處裡 : 透過原始資料進行相關基礎資料清理  
流程 3.資料導入MySQL : 將清理好資料導入資料庫  
[數據分析 - SQLAlchemy套件與資料庫連接](https://medium.com/@u357ps8633/%E6%95%B8%E6%93%9A%E5%88%86%E6%9E%90-sqlalchemy%E5%A5%97%E4%BB%B6%E8%88%87%E8%B3%87%E6%96%99%E5%BA%AB%E9%80%A3%E6%8E%A5-8826cdc6014d)  
流程 4.Power BI Dashboard : 相關數據呈現  

二、專案資料夾及檔案說明  
**\專案\Dataset**  
[Kaggle](https://www.kaggle.com/datasets/nancymee/customer-segmentation-data)  
**\專案\Python Work**  
資料清洗及導入資料庫  
**\專案Power BI**  
客戶相關資訊及銷售狀況及顧客關係圖表呈現  
![Dashboard1](https://github.com/TaenggusFan/CRM_Dashboard/blob/main/Power%20BI/Dashboard1.png?raw=true)  
![Dashboard2](https://github.com/TaenggusFan/CRM_Dashboard/blob/main/Power%20BI/Dashboard2.png?raw=true)  

## Dashboard結果呈現
1.客戶人口統計  
女性客戶人數略少於男性和其他性別，但總體差異不大。  
年齡分佈顯示，30-40歲和40-50歲的客戶佔比較大，這些年齡段的總營業額也較高，這表明這些群體可能是主要的消費者。  

2.客戶行為  
平均消費分數為50.69，表示客戶有中等水平的消費習慣。  
不同品項的銷售占比中，“電子產品”和“運動用品”佔比最高，各佔21.5%，其次是“家居”和“雜貨”，各佔20.6%和19.9%。  
年購買次數分佈顯示，大多數客戶的年購買次數在20-30次之間。

3.客戶忠誠度  
客戶活躍度分佈顯示，41-50歲和51-60歲的客戶較為活躍，而21-30歲的非活躍客戶比例較高。  
會員年數與平均購買頻率的關係圖顯示，隨著會員年數的增加，平均購買頻率也上升，尤其是在第8年的平均購買頻率達到最高。  
忠誠度分析顯示，各年齡段的平均忠誠度分數相對穩定，這表明年齡對忠誠度的影響不大；會員年數對消費行為的影響顯著，會員年數較長的客戶有著更高的消費分數。  
