# redisNotes key 操作
```
//
set age 18
set name zhangshang

//查询有哪些key
keys age
keys name
keys na[m]
keys k*
//
randomkey 

//
del age
keys *
rename key //改名key 
set site www.wangzhi.com
rename site wangzhi
exists site
keys *
get wangzhi
del wangzhi

renamenx newkey //如果新明不存在，改名

get www.zixue.it

set site www.zixue.it
set serach www.so.com
renamenx site sea
get sea
renamenx sea search

keys *

```

##redis有16个数据库
```
keys *
select 1
keys *

```
