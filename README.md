# README

Carolyn Phillips Personal Blog

## Daily operation

- Post a new article `hexo new [filename]`
- Generate files to the public directory `hexo g`
- Preview `hexo s`
- Git Add `git add .`
- Git Commit `git commit -a -S -m "xxx"`
- Git Push `git push origin main`

## Deploy my blog project on a new computer

First, go to the [Nodejs official website](https://nodejs.org/en/) and download and install node

```shell
npm install -g hexo-cli
git clone git@github.com:car0lynphillips/blog.git
cd blog
npm install
```

## Set up release

Default publishing is done automatically via `GitHub Action`