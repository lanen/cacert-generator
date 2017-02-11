# 创建步骤

1. 生成根证书
    1. 生成证书密钥
    2. 生成证书
    3. 生成crl
2. 生成中级证书
    1. 生成证书密钥
    2. 使用根证书签字中级证书
3. 生成终端证书
    1. 生成证书密钥
    2. 使用中级证书签字终端证书
4. 将终端证书转化成keystore

```
./bin/rootkey
./bin/middlekey
./bin/middlesign
```