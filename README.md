# Use WeiXin to Scan The Qrcode 微信扫描二维码

> There are many different IT courses in this miniprograme,such as,IoT,AI,Big Data,Backend Development,Frontend Development,UI and more. Please scan it and enjoy yourself.
> 在这个微信小程序中，有很多不同类型的 IT 课程，例如：物联网、人工智能、大数据、后端开发、前端开发、UI 设计等。请扫码尽情观看学习吧。

![免费IT学习平台](https://github.com/Yooye/express-tutorial-in-chinese-and-english/blob/main/qrcode.png)

# Bilingual Express tutorial in English and Chinese(中英双语 Express 教程)

# 1. Introduction 介绍

> Express is a fast, unopinionated, minimalist web framework for Node.js
> Express 是一个快速的、灵活的、极简的 Nodejs 开发框架

## Fast 快速的

> You can use it easily and quickly.
> 它很简单，你可以快速上手

## unopinionated 灵活的

> An unopinionated framework gives developers more control and the ability to shape their software according to their own preferences, while an opinionated framework provides a more structured and standardized approach to development.
> 一个灵活的框架会将项目的控制权交给开发者，允许他们根据自己的实际需求定制项目功能.
> 然而，一个“强约束”的框架会有很多的代码组织标准来约束开发者

## minimalist 极简的

> You can create a Nodejs server by a few lines of code.
> 你可以使用很少的代码，就能创建一个 Nodejs 服务

# 2. Create An Express Application(搭建 Express 项目)

> If you want to create a Nodejs server useing Express,you need to set up an Express project first.
> 如果你想基于 Express 搭建一个 Nodejs 服务，你需要先初始化一个 Express 项目
> Express provides a tool called “express-generator” which allows you to set up an Express Application quickly.
> Express 为我们提供了一个名为“express 生成器”的工具，我们可以使用这个工具快速搭建 Express 项目

Next,Let's finger out how to use "express-generator"
接下来我们演示一下，如何使用“express 生成器”

## Step1

> Use npm to install "express-generator" globally in your computer
> 使用 npm 在你的电脑上全局安装 express-generator

```
npm i express-generator -g
```

## Step2

> Use the express command to set up your Express Application
> 使用 express 命令创建 express 项目

```
express --no-view --git express-project
```

- --no-view means do not use any template engine such as "ejs".By default, generator will choose a template engine to render the data.
- --no-view 意思是：不使用任何模板引擎。默认情况下 generator 生成器会自己选一个模板引擎来渲染数据。
- --git means create a .gitignore file by default
- --git 可以让生成器帮我们创建一个.gitignore 文件
- express-project is your own project name
- express-project 是自定义的项目名称

## Step3

Now, we can see an application named "express-project" there. We need to start it up by useing the followling commands.
这个时候，我们可以看到一个名为 express-project 的项目已经创建好了。我们还需要使用下面的命令启动它。

1. Please make sure to excute the following commands in the directory of your application.
   > 请确保在你自己的项目目录下，执行下面所有命令.

```
cd express-project
```

2. Install all the dependencies useing Npm
   > 使用 npm 安装项目所需依赖

```
npm i
```

3. Start it up
   > 启动项目

```
npm run start
```

4. Try to access 'http://localhost:3000' in your browser.If you can see some words like 'Express,Welcome to Express',it means your Node server has started up successfully. Congratulations!
   > 尝试在浏览器中访问 http://localhost:3000，如果看到类似“Express,Welcome to Express”的字样。说明你已经成功启动了 Node 服务。恭喜你！
