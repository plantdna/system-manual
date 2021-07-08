# System Manual

该项目使用[Beautiful Hugo](https://github.com/halogenica/beautifulhugo)Theme

## 如何开发

clone 项目: git clone git@gitlab.com:acdna/system-manual.git

1. 启动项目

```bash
  cd system-manual
  hugo server
```

2. 新建文章

```bash
  hugo new post/new_post.md
```

3. 构建静态资源

> 需先修改config.toml中的baseurl字段

```bash
  hugo
```

## 如何部署

1. 克隆线上public项目

```bash
cd system-manual
git clone https://github.com/maizerc/maizerc.github.io.git public
```

2. 构建新的public资源文件

```bash
hugo
```

3. 更新github

```bash
cd public
git add .
git commit -m "update"
git push

```