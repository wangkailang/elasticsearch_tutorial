# elasticsearch_tutorial

## 环境要求
- [java 8](https://www.digitalocean.com/community/tutorials/how-to-install-java-with-apt-get-on-debian-8)

## 运行elasticSearch
```bash
curl -O https://artifacts.elastic.co/downloads/elasticsearch/elasticsearch-6.2.3.zip
unzip elasticsearch-xxx
```
下载后进入`elasticsearch-xxx`文件，并运行
```bash
./bin/elasticsearch
# 查看服务
curl localhost:9200
```