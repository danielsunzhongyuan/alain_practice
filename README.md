# alain_practice
https://ng-alain.com/en . It is a scaffold of Angular.

ng-alain 是一个脚手架，基于Angular和ant-design。
（ant-design、ant-design-pro是蚂蚁金服开发的一套前端框架，默认的是 React 版本，但是也有 Angular 版本）

Vue的脚手架是 Vue-Cli，React的脚手架是 create-react-app。

## 部署前准备
使用 Angular 或者 ng-alain 之前，要先安装 ng ，
```
npm install -g @angular/cli
ng --version

Angular CLI: 7.1.1
Node: 10.14.1
OS: darwin x64
Angular: undefined
```

## 纯Angular新建一个Project
```
ng new my-app
cd my-app
ng serve -o
```
完成上面的3步，即可打开一个 http://localhost:4200 

## 使用 CLI 新建一个Project
```
# 确保使用的是最新版本 Angular cli
ng new my-project --style less
cd my-project
ng add ng-alain
# 如果你想创建一个英文版本，则：
ng add ng-alain --defaultLanguage=en
ng serve
```
可以看出这样只比纯Angular多了一步 ng add ng-alain，意思是安装一个外部的库。

## 代码clone 新建一个Project
```
git clone --depth=1 https://github.com/ng-alain/ng-alain.git my-project
cd my-project
yarn
ng serve -o
```
这种方式比上一种方式的好处是，可以展示所有样例，效果如下：
![Alain全示例](/images/alain-sample-with-all-components.png)

