# 构建基于飞书 +Vitepress 的自动化同步部署方案

## 1.搭建好看的Vitepress
https://vitepress.yiov.top/preface.html
必装：安装nodejs

建议安装：安装vscode

可选安装：安装git

````
#安装pnpm
npm install -g pnpm
#查看版本号
pnpm -v
# 对应版本

pnpm add -D vitepress
# warn (ECONNRESET)一般是网络问题
pnpm vitepress init

````

::: danger 危险
这是一个危险警告
:::
pnpm run docs:dev

封装
pnpm add -D vue

