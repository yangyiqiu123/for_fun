# Type conversion function

[C++类型转换函数：将当前类的类型转换为其它类型](http://c.biancheng.net/view/2340.html)

- 轉換構造函數能夠將其它類型轉換為當前類類型（例如將 double 類型轉換為 Complex 類型），但是不能反過來將當前類類型轉換為其它類型（例如將 Complex 類型轉換為 double 類型）。
- C++ 提供了類型轉換函數（Type conversion function）來解決這個問題。類型轉換函數的作用就是將當前類類型轉換為其它類型，它只能出現在類中。

![Untitled](Type%20conversion%20function%20c8aae4938680439f8e37cbae5deb390a/Untitled.png)

![Untitled](Type%20conversion%20function%20c8aae4938680439f8e37cbae5deb390a/Untitled%201.png)

![f = 24.6
f = 43.1
n = 43](Type%20conversion%20function%20c8aae4938680439f8e37cbae5deb390a/Untitled%202.png)

f = 24.6
f = 43.1
n = 43

1. type 可以是內置類型、類類型以及由 typedef 定義的類型別名，任何可作為函數返回類型的類型（void 除外）都能夠被支持。一般而言，不允許轉換為數組或函數類型，轉換為指針類型或引用類型是可以的。
2. 類型轉換函數一般不會更改被轉換的對象，所以通常被定義為 const 成員。
3. 類型轉換函數可以被繼承，可以是虛函數。
4. 一個類雖然可以有多個類型轉換函數（類似於函數重載），但是如果多個類型轉換函數要轉換的目標類型本身又可以相互轉換（類型相近），那麼有時候就會產生二義性。以 Complex 類為例，假設它有兩個類型轉換函數：

![Untitled](Type%20conversion%20function%20c8aae4938680439f8e37cbae5deb390a/Untitled%203.png)