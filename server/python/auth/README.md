# 使用说明

目前在python2.7环境测试通过


# 步骤
 
## 修改aksk

修改aksk.py的`AK`,`SK`的值为从金山云控制台拿到的aksk


## 启动server

```
python server.py 8321
```

## 测试


然后调用`curl 'localhost:8321/Auth?Pkg=aa.aa'` 看是否得到签名相关信息




# FAQ


## python的代码示例当中有个 aws_token 这个值是什么

不用关心这个值，用nil来处理即可
