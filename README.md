# my-shop

## Project setup
```
npm install -g @vue/cli

vue  create  my-shop

```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).



# webapp-shop

created by xhf at 2020-6-16

## webapp项目周

#### 一、Vue项目创建

1、安装node.js环境（node -v 验证）
	A - B、C-D-E
2、安装vue脚手架（@vue/cli)

​	npm install -g @vue/cli

​	脚手架是一个第三方库，需先安装才能使用
​	-g 表示全局安装 global
3、使用脚手架来创建项目

​	vue  create  my-shop

​	warn warning 警告
​	error 红色，一定手动处理
4、vue.config.js 配置文件

​		ls: 查看所有目录

5、第三方依赖依赖
	(c)npm install xxx -S  把包记录在dependencies这里
	(c)npm install yyy -D  把包记录在devDependencies这里
	(c)npm install 会根据根目录中的package.json文件中记录的第三方包来进行安装。
	(c)npm install zzz -g  全局安装永久可用
6、ESLint
	作用：用于规范代码风格
7、cnpm的使用

```
# 把国外的服务器，切换至淘宝镜像源。
# 使用cnpm安装第三方模块，网速会更快。
npm install -g 
cnpm --registry=https://registry.npm.taobao.org
```

