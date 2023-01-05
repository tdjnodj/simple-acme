# simple-acme
申请ssl证书简单化

# 使用

单次使用(最新版)：

```shell
bash <(curl https://raw.githubusercontent.com/tdjnodj/simple-acme/main/simple-acme.sh)
```

稳定版:

```shell
bash <(curl -L https://github.com/tdjnodj/simple-acme/releases/latest/download/simple-acme.sh)
```

多次使用(稳定版):

```shell
wget https://github.com/tdjnodj/simple-acme/releases/latest/download/simple-acme.sh && bash simple-acme.sh
```

最新版:

```shell
wget https://raw.githubusercontent.com/tdjnodj/simple-acme/main/simple-acme.sh && bash simple-acme.sh
```


此后运行
```shell
bash simple-acme.sh
```
即可

# 特性

- 自动安装一些依赖（不会耗费太多时间）
- 自动检测 80 端口是否占用
- 自动拷贝证书
- 可生成自签证书
- 支持多种网页服务器申请
- 支持ipv6
- 对错误的提示不足
- 界面简洁

# 计划

- [ ] dns模式（因为我没有付费域名，所以不会添加）
- [ ] 人性化的输入判断（技术有限，不会添加）
- [ ] 后续更新（本来就是奔着简单来的，还要什么?）

# Credits

主要代码来源: [taffychan-acme](https://github.com/taffychan/acme)

[acme.sh](https://acme.sh/)

[Let's Encrypt](https://letsencrypt.org/)
