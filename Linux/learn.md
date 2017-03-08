# Linux tools 
 
 - nmap
 - perf
 - curl
 - vim
 - httpstat
 - awk cut seq sed grep

 ## curl

 curl -H 'Content-Type:text/plain' --data-binary @jsonTest.md http://upload.daoapp.io/upload/jsonTest.md

 curl -X PUT --data @install.sh http://upload.daoapp.io/upload/install.sh

 curl -sSL http://upload.daoapp.io/loadfile/install.sh | sh

 ## [sh](bash.html)
   循环删除go源码🀄️的测试文件


```bash
find ./ -name *_test.go | xargs rm -rf
```

```
traceroute baidu.com
```