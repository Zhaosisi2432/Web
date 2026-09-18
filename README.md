# 用户注册页面实验
## 作业内容
本次实验使用HTML5完成用户注册页面，综合运用列表、表格、表单三大模块。页面使用语义标签 header、main、footer 搭建整体结构。表单包含用户名、密码、邮箱、手机号、单选框、复选框、下拉菜单、文本域、文件上传等控件。表格实现了单元格合并，使用ul无序列表、ol有序列表、dl定义列表。通过required必填校验、pattern手机号正则校验，JS监听表单提交事件，在控制台打印表单数据。

## 使用标签
语义标签：header、main、footer、h1~h3
表格：table、thead、tbody、tr、th、td
列表：ul、ol、li、dl、dt、dd
表单：form、input、label、select、option、textarea、button

## 遇到的困难及解决方法
1. label标签和控件绑定出错，点击文字无法选中对应选项，通过设置for和id属性一一对应解决。
2. 表格colspan、rowspan合并单元格容易写反，对照教材例子调整，修复表格错位问题。
3. 表单提交会自动刷新页面，使用JavaScript的preventDefault阻止默认提交行为，实现控制台输出表单数据。


