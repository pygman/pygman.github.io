# 商品数量变更日志 接口文档

## 1.插入日志：
#### 接口地址:
    /wmProLog/insert
    
#### 接口作用:
    
    插入商品数量变更日志
    
##### 参数列表
     - sku_code 商品id
     - um       单位
     - num      变动前数量
     - movenum  变动数量
     - newnum   更新后数量
     - lc_code  货位
     - wh_code  仓库id
     - taskid   业务id
     - usercode 员工
     - info     预留字段
     
##### 接口返回
    插入成功：{result:1}
    插入失败：{result:0}
