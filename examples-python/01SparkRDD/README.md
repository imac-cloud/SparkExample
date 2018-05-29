### 測試資料
```
a,123,456,789,11344,2142,123
b,1234,124,1234,123,123
c,123,4123,5435,1231,5345
d,123,456,789,113,2142,143
e,123,446,789,14,2142,113
f,123,446,789,14,2142,1113,323
```

### Map 練習：
* spark-hw01-map.py
找出測試資料所有的英文字母，結果如下：
```
a
b
c
d
e
f
```

### FlatMap 練習：
* spark-hw02-flatmap.py
找出測試資料所有以","切割的資料
結果如下：
```
a
123
456
789
11344
2142
123
…
```

### filter 練習:
* spark-hw03-filter.py
找出測試資料所有以123與456的資料，結果如下：
```
123
456
123
1234
1234
…
```

### mapToPair 練習:
* spark-hw04-mapToPair.py
將測試資料轉換成(str,1)，結果如下：
```
(a,1)
(123,1)
(456,1)
(789,1)
…
```