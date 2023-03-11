语言 [EN](./README.md)|[CN](./README.CN.md)

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

git add slides/<slide-name>.md

git commit -m "deploy: <slide-name>.cn" # please add suffixes ,it will display in the language collum of the table

git push
```

请在等待'Github Actions'执行完毕后去往仓库的'Settings->Pages->Build and deployment->Source'选择'Github Actions'。


## 最近的报告

|名称|时间|链接|PDF|
|:-:|:-:|:-|:-|
