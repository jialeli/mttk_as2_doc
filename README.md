<p align="center">
  <img width="320" src="http://www.mttk.com.cn/images/logo_horizontal.gif">
</p>

<p align="center">
  
</p>

 [简体中文](./README.md) |  [English](./README.EN.md) 

## 简介

[MTTK_AS2](https://github.com/mttk-as2/MTTK_AS2) 是一个遵循AS2协议来实现报文收发的 java 软件系统。 系统中可以灵活配置证书、合作伙伴AS2信息、本地AS2信息等。
MTTK_AS2拥有完善的系统监控和错误追踪，MTTK_AS2 映射模块支持任意数据格式转换成任意数据格式(例如：xml转json/xml转edi/json转edi/edi转json 等)。
MTTK_AS2配套有对应的MTTK_AS2_CLOUD 云端系统，您可以利用MTTK_AS2 向CLOUD 注册，注册Cloud 后可享受 部署映射（格式转换工具） 、配置备份、售后支持等服务。


- [安装文档](https://github.com/mttk-as2/MTTK_AS2/blob/master/doc/Mttk%20AS2%20Installation_CN.pdf)

- [使用文档](https://github.com/mttk-as2/MTTK_AS2/blob/master/doc/MTTK%20AS2%20User%20Manual_CN.pdf)

- [讨论组](https://github.com/mttk-as2/MTTK_AS2/issues)

- 联系邮箱：[as2@mttk.com.cn]

## 前序准备
MTTK_AS2 是java 进行开发，存储用的是mongDB 这意味着你可能需要对这两者有大致的了解，MTTK_AS2  

**系统截图**  

<p align="center">
  <img width="900" src="https://wpimg.wallstcn.com/a5894c1b-f6af-456e-82df-1151da0839bf.png">
</p>

**安装包**

考虑到安装系统需要一定的技术能力去配置 jdk 和mongoDB 这里我们把安装程序分为两个不同类型的安装包  

- [FULL](https://github.com/mttk-as2/MTTK_AS2/tree/master/full)
包含jdk和mongoDB运行环境的安装包  (只适用于64位windows)

- [LESS](https://github.com/mttk-as2/MTTK_AS2/tree/master/less)
不包含jdk和mongoDB运行环境的基础安装包 (此安装包需要自己安装jdk和mongoDB 运行环境)


## 功能

```
- 登录 / 注销

- 权限验证
  - 页面权限
  - 指令权限
  - 权限配置
  - 二步登录

- 多环境发布
  - dev
  - sit
  - stage
  - prod

- 全局功能
  - 国际化多语言
  - 多种动态换肤
  - 动态侧边栏（支持多级路由嵌套）
  - 动态面包屑
  - 快捷导航(标签页)
  - Svg Sprite 图标
  - 本地/后端 mock 数据
  - Screenfull全屏
  - 自适应收缩侧边栏

- 编辑器
  - 富文本
  - Markdown
  - JSON 等多格式

- Excel
  - 导出excel
  - 导入excel
  - 前端可视化excel
  - 导出zip

- 表格
  - 动态表格
  - 拖拽表格
  - 内联编辑

- 错误页面
  - 401
  - 404

- 組件
  - 头像上传
  - 返回顶部
  - 拖拽Dialog
  - 拖拽Select
  - 拖拽看板
  - 列表拖拽
  - SplitPane
  - Dropzone
  - Sticky
  - CountTo

- 综合实例
- 错误日志
- Dashboard
- 引导页
- ECharts 图表
- Clipboard(剪贴复制)
- Markdown2html
```

## FULL包安装

```bash
# 克隆项目
git clone https://github.com/mttk-as2/MTTK_AS2.git

# 解压FULL安装包 \MTTK_AS2\full\FULL.rar


# 解压后，进入解压后的bin目录 [\mttk_as2\work\bin]

# 运行mongoDB环境
mongoStartup.bat

# windows 服务方式运行mongoDB环境
mongoInstallService.bat

# 启动MTTK_AS2服务
startup.bat
```

浏览器访问 http://localhost:5555

## LESS包安装


```bash
# 克隆项目
git clone https://github.com/mttk-as2/MTTK_AS2.git

# 解压项目目录
\MTTK_AS2\less\LESS.rar
```
更多信息请参考 [安装文档](https://github.com/mttk-as2/MTTK_AS2/blob/master/doc/Mttk%20AS2%20Installation_CN.pdf)

## 其它


更多信息请参考 [使用文档](https://github.com/mttk-as2/MTTK_AS2/blob/master/doc/MTTK%20AS2%20User%20Manual_CN.pdf)

## Browsers support

Modern browsers and Internet Explorer 10+.

| [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt="IE / Edge" width="24px" height="24px" />](https://godban.github.io/browsers-support-badges/)</br>IE / Edge | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](https://godban.github.io/browsers-support-badges/)</br>Firefox | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](https://godban.github.io/browsers-support-badges/)</br>Chrome | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" />](https://godban.github.io/browsers-support-badges/)</br>Safari |
| --------- | --------- | --------- | --------- |
| IE10, IE11, Edge | last 2 versions | last 2 versions | last 2 versions |

## License

[MIT](https://github.com/PanJiaChen/vue-element-admin/blob/master/LICENSE)

Copyright (c) 2020-mttk.com.cn
