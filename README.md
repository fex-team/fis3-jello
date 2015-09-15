# fis3-jello

基于 fis3 针对 jsp/velocity 模板的前端工程解决方案。

此版本基于 fis3， 想了解 fis2 版本，请移步至：https://github.com/fex-team/jello

## 使用说明
安装 `fis3-jello`

```
npm install -g fis3-jello
```

然后在 fis-conf.js 中添加以下代码即可。

```js
fis.require('jello')(fis);
```

## 调试服务器

如果当前命令行在 fis-conf.js 所在目录（即项目目录），直接通过 `fis3 server start` 即可。

否则请使用 `fis3 server start --type jello`。

## 体验 demo

```bash
# 创建一个目录，并进入该目录。
mkdir demo
cd demo

# 通过脚手架初始化项目
fis3 init jello-demo

# 编译产出到 fis3 调试服务
fis3 release

# 启动 fis3 调试服务。
fis3 server start
```

脚手架代码来源 https://github.com/fis-scaffold/jello-demo

