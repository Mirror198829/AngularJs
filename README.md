
# 技术栈：AngualrJs1.5.11 + iCheck +ui-router
# AngularJs1.0 知识点

# 指令
## 指令的命名约定
* js中指令的名称是驼峰式，如：blgMenu
* HTML中模板使用blg-meun形式（原因：html不区分大小写，ng的html编译器遇到左侧形式，会转成对应驼峰式）
* 指令名称唯一
* 不能使用ng开头前缀，因ng内置指令已经占用
## restrict 约束选项
restrict共有4个选项，为了指明ng在HTML模板中如何触发指令
* A: 只匹配属性名 `<div blg-menu></div>`
* E: 只匹配元素名 `<blg-menu></blg-menu>`
* C: 只匹配类名 `<div class="blg-menu"></div>`
* M: 只匹配注释 `<!--directive:blg-menu-->`
通常设置为 restrict:'AE'
## 事件指令
* ng-click/dbclick ng-mousedown/up ng-mouseenter/leave ng-mousemove/over/out ng-keydown/up/press ng-focus/blur ng-submit
* ng-selected
* ng-change
* ng-copy
* ng-cut
* ng-paste
# form表单
## 表单验证className
* .ng-valid{}
* .ng-invalid{}
* .ng-pristine{}
* .ng-dirty{}


