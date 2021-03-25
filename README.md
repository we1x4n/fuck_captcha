# fuck_captcha

基于muggle-ocr的验证码识别脚本，目前仅支持4-6简单英数验证码

准确率是高于百度OCR的

# 环境以及依赖

* windows 10
* python 3.7
* muggle-ocr（python库）

# 安装方法

`pip3 install muggle-ocr`

# 使用方法

配合burpsuite插件[captcha-killer](https://github.com/c0ny1/captcha-killer/)
```
POST /img2text HTTP/1.1
Host: <your_ip>:<your_port>


image=<@URLENCODE><@BASE64><@IMG_RAW></@IMG_RAW></@BASE64></@URLENCODE>
```

# 参考文章

[captcha-killer调用tesseract-ocr识别验证码](https://github.com/c0ny1/captcha-killer/tree/master/doc/case01)


# 招聘

渗透测试工程师(base:哈尔滨)

![](wechat-qrcode.png)
