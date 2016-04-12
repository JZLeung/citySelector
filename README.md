#   citySelector
一个用原生js实现的多级联动下拉框

##  参数说明
*   selecotor：
    需要联动的`select`的id
*   data：
    当selector触发联动时显示的数据

##  使用
1.  引入`selector.js`
2.  
```
    new selector({
        selecotor:['s1', 's2', 's3'],
        data:datas
    })
```

## API
1.  `getValue`

    `param`: 无

    `return`:
    获取当前已选择的值（文本）
    返回类型为数组

2.  `setValue`

    `param`:

    1.  (必选)传入一组需要设置的数值（0，1，2...）
    2.  (非必选)是否选择对应`value`，默认为`false`，即选择对应的`selectedIndex`

    `return`: 无
