# money-v2
## 开发前准备
手动添加本地配置文件
增加 coin.yaml 配置参考 coin-template.yaml
增加 config.yaml 配置参考 config-template.yaml

## 开发

```bash
./dev
```

如果遇到没有权限，请使用chmod给文件加权限

```bash
chmod +x ./dev
```

如果deno安装失败，请手动安装，并加入环境变量
```bash
# mac
curl -fsSL https://deno.land/x/install/install.sh | sh
```

## 钉钉
钉钉机器人请添加以下四个关键词过滤:
debug info warn error

## 新增数据持久化