### Impl

[imp1](http://www.bogotobogo.com/python/python_numpy_batch_gradient_descent_algorithm.php)

### 取某一天，某一個測項
```
>>> df[df[u'日期'].isin(['2014/1/1']) & df[u'測項'].isin(['PM2.5'])]
         日期  測站     測項   0   1   2   3   4   5   6   7   8   9  10  11  12  \
9  2014/1/1  豐原  PM2.5  26  39  36  35  31  28  25  20  19  30  41  44  33   

   13  14  15  16      
9  37  36  45  42 ...  

[1 rows x 27 columns]
```

![PM25 vs all](./scatter_PM25_vs_all.png)