Jaccard為分析set1，set2屬性中的0與1的個數，系數值越大，樣本相似度越高。  
getstrings為取得我們的路徑，截取內容。  
pecheck為確認或判斷。  
若threshold設為0.8，則表示使用jaccard算出的數字只要大於等於0.8以上兩者就會進行連線。  
若threshold設為0.3，則表示使用jaccard算出的數字只要大於等於0.3以上兩者就會進行連線。  
關聯值設太高或太低都不好，太高連接線太少，則會找不到相關的惡意程式；太低連接線太多，則會造成每個惡意程式都相關，所以太高或太低，所呈現出來的結果都不是很準確。
