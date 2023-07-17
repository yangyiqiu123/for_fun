# C++用法

- 在 vector 裡加東西    vector_nume.push_back()
- vector 開始、結束、長度    name.begin() 、name.end()、name.size()
- auto with for
    
    [auto ](C++%E7%94%A8%E6%B3%95%20d9cdec9e0c5f4a48afad8ddbd7e7515b/auto%206d21028bcdd345e3a3abf75e9e39477d.md)
    
- 反轉(字元陣列、string、array、vector)裡面的東西 `#include <algorithm>`
    
    [#<algorithm> reverse](C++%E7%94%A8%E6%B3%95%20d9cdec9e0c5f4a48afad8ddbd7e7515b/#%20algorithm%20reverse%208f8c695548034d7e88089aa507ba4862.md)
    

## 字串

- 輸入 #include <string>
    
    要讀取整行的話要用 getline(cin,s) ， 用 cin 的話只會讀到空格前
    
    - ***如果getline()之前有用 cin 的話要在藥用的getline()在加個getline()**，因為cin不會讀換行符號，要用一個getline()把它消掉。*
    
    ```cpp
    string s;
    getline(cin,s)
    ```
    

- 長度    str.len()
- strcpy()、strncpy()：字串複製

```cpp
char *strcpy( char *dest, const char *src );
char *strncpy( char *dest, const char *src, size_t count );
```

```cpp
strcpy(s, "hello sky");
strncpy(s, "hello sky", 8);
```

## pair 用法

- **name.first**
- **name.second**
- **make_pair(first_name,second_name)**

![Untitled](UVA%20614bd8b2d44d45a08259a0080434d4eb/Untitled%202.png)