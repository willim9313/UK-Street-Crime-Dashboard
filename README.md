# UK-Street-Crime-PowerBI-Dashboard
West Yorkshire street crime, stop and search dashboard  
嘗試使用英國警政單位的街頭犯罪類型的項目資料進行dashboard搭建  
資料參考範圍為2020~2022年間，聚焦在本人曾生活過得西約克郡地區做為目標  
參考原始資料為3種資料源，透過powerquery完成ETL(城市、街道字串的拆分)，crimeID與對應產出表作left join  
最終依據資料本身特性區別可歸納地區與無疾而終的案件呈現4張dashboarding成果，主題分別如下:  
1. 西約克郡路邊攔檢與搜查  
2. 西約克郡街頭犯罪趨勢與犯罪類別分布地區
3. 西約克郡特定城鎮街頭犯罪地點與類型
4. 西約克郡無特定地點街頭犯罪呈報與案件最終結果

data source: 
2020~2022 UK police street crime, stop and search, outcomes of West Yorkshire region  
https://data.police.uk/data/  

Contains public sector information licensed under the Open Government Licence v3.0.  

license reference:  
https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/  
