
# 数据读取（readr）

## 读取 read.table

读取普通数据可用 read.table，有6个参数比较重要：

- file：文件路径
- sep：文件的分隔符，缺省无
- skip：跳过开始的 skip 行开始读取
- header：是否将第一行读取为列名，缺省 FALSE
- nrows：读取的行数
- fill：将缺失数据定为 NA, 缺省并无指定

## 高阶包 readr

也可用 readr 包读取表格型数据，不仅速度快，且能直接读取为 tbl 格式。参考 [readr 介绍](http://www.xueqing.tv/cms/article/102)。


```r
library(readr)
```

read_csv 和 read_tsv 分别读取分隔符为逗号和制表符的数据，read_csv2 则是读取分号分割的数据，read_dlim 读取自定义的。

函数定义：


```r
# read_delim(file, delim, quote = "\"", escape_backslash = FALSE,
#  escape_double = TRUE, col_names = TRUE, col_types = NULL,
#  locale = default_locale(), na = c("", "NA"), comment = "", skip = 0,
#  n_max = -1, progress = interactive())
```

write_csv 用于写入数据，不写入行名。

函数定义


```r
# write_csv(x, path, na = "NA", append = FALSE, col_names = !append)
```
