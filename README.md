# canal1.1.4
修改canal1.1.4 版本同步时候 兼容tidb v3数据库

1: 修改canal 支持 没有表主键ID，也可以更新记录，并同步TIDB <br>
2:因TIDB 不支持alter 多列，修改canal DDL 支持多列同步到TIDB。
