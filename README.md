## 搭建github图床

在https://github.com/Molio-tan/setting/tokens生成 token: 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

在https://sm.ms/home/apitoken 获取token: ...

在`typora`所在服务器上安装`picgo-core cli`
```
sudo npm install picgo -g
```
在`typora`偏好设置中使用`custom commnad`: `/usr/local/bin/picgo upload`, 配置`config`后验证上传即可
