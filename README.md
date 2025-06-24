# n8n

[![AUR](https://img.shields.io/badge/license-Apache%20License%202.0-blue.svg)](https://github.com/opendidi/pano/blob/main/LICENSE)
[![](https://img.shields.io/badge/node-20.18.1-brightgreen.svg)]()

- 本地运行

- 下载依赖 需要node版本 v20.18.1

```ssh
> pnpm install
```


- 启动项目,需要(n8n-nodes-wechat-offiaccount项目打包完成后运行)

```ssh
> pnpm start
```

- 浏览器打开

```ssh
> http://localhost:5678
```

- 克隆项目到本地

```ssh
> git clone https://github.com/other-blowsnow/n8n-nodes-wechat-offiaccount
```

- 安装依赖

```ssh
> pnpm install
```

- 打包项目

```ssh
> pnpm run build
```

- 配置项目路径

- [N8N_CUSTOM_EXTENSIONS=E:/test2/n8n-nodes-wechat-offiaccount](https://github.com/opendidi/n8n-local-run/blob/main/.env#L13)

- 项目启动后的界面
- <img width="100%" align="center" src="./images/1750754072802.jpg" />

- 创建一个n8n数据库图片如下，数据表运行n8n会自动创建：
- <img width="25%" align="center" src="./images/1750754940680.jpg" />