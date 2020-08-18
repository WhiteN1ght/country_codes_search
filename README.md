# country codes search

模糊搜索查询中文国家或地区名称和国家地区代码（ISO 3166-1 标准）的对应关系

## Install 

```
go get github.com/13ph03nix/country_codes_search 
```

## Usage

```
➜ country_codes_search -h
Usage of country_codes_search:
  -k string
    	The keyword to search (ignore case) (default "A")

➜ country_codes_search -k 国
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

➜ country_codes_search -k X
SX --- 荷属圣马丁
XK --- 科索沃
MX --- 墨西哥
AX --- 奥兰群岛
```

