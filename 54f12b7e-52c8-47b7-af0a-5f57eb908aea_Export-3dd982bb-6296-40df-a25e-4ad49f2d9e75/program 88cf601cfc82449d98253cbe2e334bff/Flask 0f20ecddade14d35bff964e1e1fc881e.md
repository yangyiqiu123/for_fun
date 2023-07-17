# Flask

# 環境

[虛擬環境](Flask%200f20ecddade14d35bff964e1e1fc881e/%E8%99%9B%E6%93%AC%E7%92%B0%E5%A2%83%20d7acb5199b5d438a8ec7213171081361.md)

# 藍圖

[templates floder 路徑](Flask%200f20ecddade14d35bff964e1e1fc881e/templates%20floder%20%E8%B7%AF%E5%BE%91%2086b31c12e33246f191181e6778a12b91.md)

# 資料庫

[如果要跟新模型怎麼半](Flask%200f20ecddade14d35bff964e1e1fc881e/%E5%A6%82%E6%9E%9C%E8%A6%81%E8%B7%9F%E6%96%B0%E6%A8%A1%E5%9E%8B%E6%80%8E%E9%BA%BC%E5%8D%8A%2091a0d98fe25349fe8d08ebd4287408a2.md)

[****SQLALchemy****](Flask%200f20ecddade14d35bff964e1e1fc881e/SQLALchemy%207d94d651a1944b478d21c88ebc313aa6.md)

# 重新導向範例

- 當 client 收到 redrict 後會發起 GET 乞求給指定頁面 ， 收到 GET 請求後做出相應動作 ， 而不是在 POST 後直接給

[PRG模式](Flask%200f20ecddade14d35bff964e1e1fc881e/PRG%E6%A8%A1%E5%BC%8F%209971167483644ab4b9042c87f39dc803.md)

# **Flask-Login獲取next參數request.args.get('next')獲取不到值**

[獲取next參數](Flask%200f20ecddade14d35bff964e1e1fc881e/%E7%8D%B2%E5%8F%96next%E5%8F%83%E6%95%B8%20c7162f252e144ede9c2eefd083e5e753.md)

# cookie & session

## cookie

Cookie 是伺服器（Server）傳送給瀏覽器（Client）的一小片段資料，並請瀏覽器保存起來，以便往後向相同的伺服器發送請求時，附上這 Cookie 的資料。

![Untitled](Flask%200f20ecddade14d35bff964e1e1fc881e/Untitled.png)

[介紹](Flask%200f20ecddade14d35bff964e1e1fc881e/%E4%BB%8B%E7%B4%B9%203dbc7559a711474da8a1029044498ef0.md)

# session

Session 將使用者相關的敏感資訊存放在伺服器端 — 可能在記憶體或資料庫中 — 並創建一個相對應且獨特的 ID（Session ID），在回傳給客戶端的 Cookie 中一併附上，未來客戶端只要附上含有這個 Session ID 的 Cookie 給伺服器，伺服器就能匹配相對應的 Session — 也能找到需要的敏感資料了！

![Untitled](Flask%200f20ecddade14d35bff964e1e1fc881e/Untitled%201.png)