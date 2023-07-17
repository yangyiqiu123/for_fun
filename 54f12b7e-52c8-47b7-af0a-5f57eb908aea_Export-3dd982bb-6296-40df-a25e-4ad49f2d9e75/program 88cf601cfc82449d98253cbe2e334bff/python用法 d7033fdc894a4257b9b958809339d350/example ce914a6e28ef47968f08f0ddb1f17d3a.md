# example

- 反轉 list  順序
    
     list_name.reverse()
    
- 在 list 裡加東西
    
    list_name.append()
    
- 如果需要同時新增多個項目，請使用extend()方法
list_name.extend([9, 11, 13])
- 在指定的索引位置插入1個項目
    
    list_name.insert(1, 3)
    
- 刪除指定索引的清單項目
list_name list1[2]
- 使用pop()方法刪除和傳回最後1個項目
    
    e1 = list_name .pop()
    
    - 如果pop()方法有參數，就是刪除和傳回指定索引值的項目，
    如下所示
        
        e2 = list_name .pop(1)
        
- 如果需要刪除指定項目（不是索引），我們可以使用remove()方法
    
    list_name .remove(9)
    
    ```python
    # Removing elements from a list
    lst7 = [1, 2, 3, 4, 5]
    lst7.remove(3)
    print(lst7)  # Output: [1, 2, 4, 5]
    
    lst8 = [1, 2, 3, 4, 5]
    del lst8[2]
    print(lst8)  # Output: [1, 2, 4, 5]
    ```
    
- count() 方法用于统计某个元素在列表中出现的次数
    
    list_name.count(7)
    
- list長度
    
    len(list_name)