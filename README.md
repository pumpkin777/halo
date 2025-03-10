<h1 align="center"><a href="https://github.com/halo-dev" target="_blank">Halo</a></h1>

> Halo 是一款现代化的个人独立博客系统，给习惯写博客的同学多一个选择。

<p align="center">
<a href="https://github.com/halo-dev/halo/releases"><img alt="GitHub release" src="https://img.shields.io/github/release/halo-dev/halo.svg?style=flat-square"/></a>
<a href="https://github.com/halo-dev/halo/releases"><img alt="GitHub All Releases" src="https://img.shields.io/github/downloads/halo-dev/halo/total.svg?style=flat-square"></a>
<a href="https://hub.docker.com/r/halohub/halo"><img alt="Docker pulls" src="https://img.shields.io/docker/pulls/halohub/halo?style=flat-square"></a>
<a href="https://github.com/halo-dev/halo/commits"><img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/halo-dev/halo.svg?style=flat-square"></a>
<a href="https://github.com/halo-dev/halo/actions"><img alt="GitHub Workflow Status" src="https://img.shields.io/github/workflow/status/halo-dev/halo/Halo%20CI?style=flat-square"/></a>
</p>

------------------------------

## 简介

**Halo** `[ˈheɪloʊ]`，意为光环。当然，你也可以当成拼音读(哈喽)。

一个优秀的开源博客发布应用，值得一试。

> [官网](https://halo.run) | [文档](https://docs.halo.run) | [社区](https://bbs.halo.run) | [Telegram 频道](https://t.me/halo_dev)

## 快速开始

下载最新的 Halo 安装包：

> 其他地址：https://docs.halo.run/install/downloads

```bash
curl -L https://github.com/halo-dev/halo/releases/download/v1.4.5/halo-1.4.5.jar --output halo.jar
```

```bash
java -jar halo.jar
```

### Docker:

```bash
docker run -it -d --name halo -p 8090:8090 -v ~/.halo:/root/.halo --restart=always halohub/halo
```

详细部署文档请查阅：<https://docs.halo.run/install/index>

## 周边

- 后台管理（halo-admin）：<https://github.com/halo-dev/halo-admin>
- 独立评论模块（halo-comment）：<https://github.com/halo-dev/halo-comment>
- 管理 APP（已停止维护）：<https://github.com/halo-dev/halo-app>
- 主题仓库：<https://halo.run/themes.html>
- 资源下载：<https://docs.halo.run/install/downloads>
- WeHalo 小程序：<https://github.com/aquanlerou/WeHalo>

## 许可证

[![license](https://img.shields.io/github/license/halo-dev/halo.svg?style=flat-square)](https://github.com/halo-dev/halo/blob/master/LICENSE)

> Halo 使用 GPL-v3.0 协议开源，请尽量遵守开源协议。

## 贡献

参考 [CONTRIBUTING](./CONTRIBUTING.md)。