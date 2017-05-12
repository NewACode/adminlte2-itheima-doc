# AdminLTE2-Itcast-定制版

![后台首页](https://hans007.gitbooks.io/adminlte2-itcast/img/后台首页.png)

## 前言

- 本 `后台管理模板` 是基于开源项目 `AdminLTE2` ，为符合在国内项目中使用，就行定制开发。
- `AdminLTE2` 是一个完全的响应式管理模板，基于 `Bootstrap3` 框架，高度可定制，易于使用。适合从小型移动设备到大型台式机的屏幕分辨率。
- `AdminLTE2` 框架在网页架构与设计上，有很大的辅助作用，尤其是前端架构设计师，用好 `AdminLTE2` 不但美观，而且可以免去写很大CSS与JS的工作量。
- [本项目Git地址](http://git.oschina.net/docafe/adminlte2-itcast)
- [在线浏览](http://research.itcast.cn/adminlte2-itcast/release/dist/pages/all-admin-index.html)

## 技术栈

Bootstrap3 + jQuery

## 定制说明

- 修改 - 默认中文字体 `微软雅黑`
- 修改 - 本项目访问字体库文件 `font-awesome` `bootstrap-font` 避免了 `墙内` 无法下载，打开页面长时间`白屏`问题
- 修改 - `谷歌` js库文件为本项目访问, 原因同上
- 修改 - 汉化常用控件 如: `timepicker` 、 `datepicker` 、 `daterangepicker` 、 `ckeditor` 、  `WYSIHTML5` 、 `Markdown`
- 重构 - 基于node技术，采用 `百度fis3` 工程化管理
- 重构 - 发布文件有两种，一种是带工具栏导航的完整页面，另一种是不带的直接内容页，方便后台人员定制
- 重构 - 所有用到的组件都整理在了 `plugins` 目录下，取消了bower包管理，因为组件会进行二次开发定制
- 添加 - `通用界面`示范代码 ( `登录` 、`注册` 、`404错误页` 、`500错误页` 、`空白页` 、`数据列表页` 、`表单页样式` )
- 添加 - `图表Charts`示范代码 ( `ChartJS` 、`Morris Charts` 、`Flot Charts` 、`Inline Charts` )
- 添加 - `UI界面元素`示范代码 ( `标准 General` 、`图标 Icons` 、`按钮 Buttons` 、`滑块 Sliders` 、`时间线 Timeline` 、`对话框样式 Modals` 、`窗体小部件 widgets` )
- 添加 - `表单 Forms`示范代码 ( `基础表单元素` 、`高级表单元素` 、`编辑器` )
- 添加 - `表格 tables`示范代码 ( `简单表格` 、`数据表格` )
- 添加 - `样例-订单管理`示范代码 ( `全部订单` 、`订单表单` 、`退款` )
- 添加 - `样例-游记管理`示范代码 ( `游记列表` 、`添加游记` 、`游记点评` 、`游记设置` )
- 添加 - `样例-系统管理`示范代码 ( `系统设置` )

## 目录

## 参考

- [AdminLTE2官方网站](https://almsaeedstudio.com/)
- [百度fis3](http://fis.baidu.com/fis3/index.html)