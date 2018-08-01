# money_keyboard

* 作者：macaihong
* 邮箱：mc260@foxmail.com
* 版本：**`0.0.8`**

## 介绍

_数字软键盘_带确定键


## 安装

`lm-*` 组件使用 `npm` 进行管理，命名空间统一为 `lm-`，请使用以下命令进行组件安装。

```
npm install lm-money-keyboard --save
```

- 如果你还没有安装 `npm`，可通过以下方式进行 [安装](https://nodejs.org/en/download/)。
- 安装cnpm `npm install -g cnpm --registry=https://registry.npm.taobao.org`


## 使用

### 样例文档

- 待开发

### 使用

```
<MoneyKeyboard
    classNames="d1"
    visible={true}
    handle={this.handle}
    onOk={this.onOk}
/>

```
### 配置参数

| Prop | Type | Default | Description |
| ---- |:----:|:-------:| :----------:|
| **`handle`** | `func` | `args => args` | 点击触发事件 |
| **`onOk`** | `func` | `args => args` | 点击数字面板外执行的函数 |
| **`visible`** | `bool` | `false` | 是否显示数字面板 |
| **`classNames`** | `string` | `undefined` | 自定义className |


### 展示效果

<img width="400" src="http://img.chuansroom.com/resources/WechatIMG18.png" />

## 注意事项

- 组件注意事项

暂时不支持自定义确定按钮颜色


## 开发调试

进入项目目录后，使用 `node` 命令启动服务

```
npm run start
```

打包发布可通过 `node` 命令执行

```
npm run build
npm publish
```


## 相关资料

* [lm 组件开发规范](http://)


## Changelog

0.0.3 修正确定按钮背景色

0.0.4 修正边框颜色

0.0.5 取消键盘蒙层

0.0.6 样式修改

0.0.8 修改键盘动画时间
