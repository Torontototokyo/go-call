### Not work
```sh
go env -w GOPROXY=https://goproxy.cn,direct
go env -w GOSUMDB="sum.golang.org https://goproxy.cn/sumdb/sum.golang.org"
```
### Work
```sh 
go env -w GOSUMDB=off 
```


```sh 
go get github.com/Torontototokyo/go-call 
```