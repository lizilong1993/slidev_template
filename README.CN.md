|||||
|-|-|-|-:|
|语言| [EN](./README.md)|[CN](./README.CN.md) |[![Build and Deploy](https://github.com/lizilong1993/slidev_template/actions/workflows/deploy.yml/badge.svg)](https://github.com/lizilong1993/slidev_template/actions/workflows/deploy.yml)|

# 欢迎

本仓库由 [Sli.dev](https://sli.dev) + Github Actions + Github Pages驱动.

非常感谢 [fguisso/talks](https://github.com/fguisso/talks/)!

## 安装环境

- `npm install`
- `npm run dev -- slides/my-slide.md`
- visit <http://localhost:3030>

更多资料请前往官方文档自行查看 [documentations](https://sli.dev/).

## 部署到Github Pages

请严格按照以下格式进行提交:
> 'commit信息需要包含deploy' 和 '后缀（使用的语言）'；
> 如不需要修改README.md 可以自行修改.'github\workflows\deploy.yml'
> 别忘了把'.github\workflows\deploy.yml'里的相应信息改成你自己的。
```bash
git pull 

# 文件必须带上后缀来标识语言哈
git add slides/<slide-name>.cn.md

git commit -m "deploy: <slide-name>.cn" 

git push
```

请在等待'Github Actions'执行完毕后去往仓库的'Settings->Pages->Build and deployment->Source'选择'Github Actions'。


## 最近的报告

|名称|时间|链接|PDF|
|:-:|:-:|:-|:-:|
|slides.cn|2023-03-11|[https://lizilong1993.github.io/slidev_template/slides.cn](https://lizilong1993.github.io/slidev_template/slides.cn/)|[https://cdn.jsdelivr.net/gh/lizilong1993/slidev_template@main/exports/slides.cn.pdf](https://cdn.jsdelivr.net/gh/lizilong1993/slidev_template@main/exports/slides.cn.pdf)|
|slides.en|2023-03-11|[https://lizilong1993.github.io/slidev_template/slides.en](https://lizilong1993.github.io/slidev_template/slides.en/)|[https://cdn.jsdelivr.net/gh/lizilong1993/slidev_template@main/exports/slides.en.pdf](https://cdn.jsdelivr.net/gh/lizilong1993/slidev_template@main/exports/slides.en.pdf)|
|slides.fr|2023-03-11|[https://lizilong1993.github.io/slidev_template/slides.fr](https://lizilong1993.github.io/slidev_template/slides.fr/)|[https://cdn.jsdelivr.net/gh/lizilong1993/slidev_template@main/exports/slides.fr.pdf](https://cdn.jsdelivr.net/gh/lizilong1993/slidev_template@main/exports/slides.fr.pdf)|
