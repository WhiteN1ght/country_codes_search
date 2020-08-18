# country codes search

模糊搜索查询中文国家或地区名称和国家地区代码（ISO 3166-1 标准）的对应关系

## Install 

```
go get github.com/13ph03nix/country_codes_search 
```

## Usage

```
➜ ./c2c -h
Usage of ./c2c:
  -k string
    	The keyword to search (ignore case) (default "A")

➜ ./c2c -k 国
DE --- 德国
FR --- 法国
CG --- 刚果共和国
HK --- 中国香港
GB --- 英国
TW --- 中国台湾
KR --- 韩国
CD --- 刚果民主共和国
TH --- 泰国
CN --- 中国
US --- 美国
MO --- 中国澳门

➜ ./c2c -k X
SX --- 荷属圣马丁
XK --- 科索沃
MX --- 墨西哥
AX --- 奥兰群岛
```

