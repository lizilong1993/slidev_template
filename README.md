|||||
|-|-|-|-:|
|Language| [EN](./README.md)|[CN](./README.CN.md) |[![Build and Deploy](https://github.com/lizilong1993/slidev_template/actions/workflows/deploy.yml/badge.svg)](https://github.com/lizilong1993/slidev_template/actions/workflows/deploy.yml)|

# Welcome to my talks

This project is powered by [Sli.dev](https://sli.dev) + Github Actions + Github Pages.

Special Thanks [fguisso/talks](https://github.com/fguisso/talks/)!

## Running for development

- `npm install`
- `npm run dev -- slides/my-slide.md`
- visit <http://localhost:3030>

Learn more about Slidev on [documentations](https://sli.dev/).

## Deploy in Github Pages
> remenber to replace the infos with your own in the '.github\workflows\deploy.yml'. 
Deploys are dispatched by commit messages:

```bash

# please add suffixes ,it will display in the language collum of the table
git pull

git add slides/<slide-name>.en.md

git commit -m "deploy: <slide-name>.en" 

git push

```

Please wait the 'Github Actions' work complete， then go to your repository 'Settings->Pages->Build and deployment->Source', and choose the item 'Github Actions'.

## Past talks

|Name|Presented at|Slides Link|PDF Link|
|:-:|:-:|:-:|:-:|
|slides.cn|2023-03-11|[https://lizilong1993.github.io/slidev_template/slides.cn](https://lizilong1993.github.io/slidev_template/slides.cn/)|[https://cdn.jsdelivr.net/gh/lizilong1993/slidev_template@main/exports/slides.cn.pdf](https://cdn.jsdelivr.net/gh/lizilong1993/slidev_template@main/exports/slides.cn.pdf)|
|slides.en|2023-03-11|[https://lizilong1993.github.io/slidev_template/slides.en](https://lizilong1993.github.io/slidev_template/slides.en/)|[https://cdn.jsdelivr.net/gh/lizilong1993/slidev_template@main/exports/slides.en.pdf](https://cdn.jsdelivr.net/gh/lizilong1993/slidev_template@main/exports/slides.en.pdf)|
|slides.fr|2023-03-11|[https://lizilong1993.github.io/slidev_template/slides.fr](https://lizilong1993.github.io/slidev_template/slides.fr/)|[https://cdn.jsdelivr.net/gh/lizilong1993/slidev_template@main/exports/slides.fr.pdf](https://cdn.jsdelivr.net/gh/lizilong1993/slidev_template@main/exports/slides.fr.pdf)|
