Language [EN](./README.md)|[CN](./README.CN.md)
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
git pull

git add slides/<slide-name>.md

git commit -m "deploy: <slide-name>.en" # please add suffixes ,it will display in the language collum of the table

git push
```

Please wait the 'Github Actions' work complete， then go to your repository 'Settings->Pages->Build and deployment->Source', and choose the item 'Github Actions'.

## Past talks

|Name|Presented at|Slides Link|PDF Link|
|:-:|:-:|:-:|:-|
