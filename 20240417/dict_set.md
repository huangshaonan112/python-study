# Python 基础


## 字典 dict


- dict(), {}
- 键值对，key: value
- {'name': 'alice', 1: 10, 5.0: 50, True: 1, None: None }
- 键唯一


### 内置方法


|方法|说明|
|:---:|:--|
|.get(key, default)|获取 key 的值，如果失败，返回 default|
|.keys()|取得所有的键的序列|
|.values()|取得所有的值的序列|
|.items()|取得所有的键值对元组的序列|



## 集合 set


- set(), {}
- 只有键，且唯一


- 合集 `|`
- 交集 `&`
- 差集 `-`
- 异或 `^`


### 内置方法


|方法|说明|
|:---:|:--|
|.add(el)|添加元素el|
|.pop()|随机弹出一个元素|
|.remove(el)|删除，失败报错|
|.discard(el)|删除，失败不报错|






***

2024-04-17

__EOF__
