# Linux命令

### logstash启动命令

```shell
/home/installs/logstash-7.3.0/bin/logstash -f /home/cntd/klq/logstash_config/文件名 --path.data=/home/cntd/klq/logstash_file/文件夹
```

### 查询当前文件夹有多少文件

```shell
ls | wc -w
```

### 复制文件

```shell
cp -r temp/t1/* t1/
```

### 查找文件

```shell
find --name	xxxx.txt
```

### 后台启动Java

```shell
nohup java -Dpath=/home/cntd/klq/old_file/cntd_data_mail_fetch.txt -jar domain_clean-1.0-SNAPSHOT-jar-with-dependencies.jar>./log/cntd_data_mail_fetch.log 2>&1 &
```



find / -name ElasticSearch -print





curl -XGET -u 'elastic:ff#IST@QA1203' http://localhost:9200/_cat/indices?v

curl -XDELETE  -u 'elastic:ff#IST@QA1203' http://localhost:9200/cntd_data_ip_info





curl -XGET -u 'elastic:ff#IST@QA1203' http://localhost:9200/cntd_data_ip_info?pretty



curl -XGET http://ip:port/索引名?pretty
