# 前端工程目录
```
zjnytjc-view
|-- api
	|--api.js		接口文件
|-- app
	|-- components	公共组件文件夹
	|-- layout		页面布局文件夹（头部、菜单、登录）
	|-- menus		页面文件夹
|-- images			图片文件夹
|-- js				js文件夹
|-- lib				开发框架文件夹（Vue、Vuex、vmd-ui、vue-router、echarts...）
|-- router			路由入口文件
|-- static			路由开发文件夹
	|--	routerMap	路由开发文件
|-- store			状态管理器文件夹（vuex）
|-- styles			css和字体文件夹
	|-- font			字体文件目录	
	|-- common			公共的css开发目录
|-- utils			工具函数文件夹
	|-- utils.js		路由专用工具函数
	|-- util.js			公共的工具函数（可自行补充）
|-- index.html		单页面开发入口文件
```

# 开发规范
### api.js文件每个接口必须写注释、routerMap.js每个路由必须写注释、全局变量或方法必须写注释
### 所有文件夹及文件使用英文命名（避免使用中文路径）
### 在页面中尽量避免使用style属性，即style="…"
### 重要图片必须加上alt属性。给重要的元素和截断的元素加上title
### 所有页面元素类图片均放入images文件夹
### 所有的css和字体文件均放入styles文件夹下
### 类命名：首字母大写，驼峰式命名.如MyVue
### 函数命名：首字母小写驼峰式命名.如myVue()
### 命名语义化，尽可能利用英文单词或其缩写。
### 常量以及全局变量必须全部使用大写字母、其他变量是用驼峰命名
### 布尔值的变量名的命名前面加is,同理可以加 has,can,should
### 指定数字的变量名，尽量使用num或num开头
### 指定字符串的变量名，尽量用str,或str开头
### 变量应该放在和他有关系的代码中，不要把变量放在最上面，下面隔很远
### 方法命名的第一个单词尽量使用动词。例如：get/set  add/remove  create/destroy   start/stop   insert/delete  begin/end open/colse等
### 使用v-for的标签必须加上key属性
### 查询按钮在前，重置按钮在后、保存、确定按钮在前，取消、关闭按钮在后
### 批量删除统一用灰色按钮，单行删除统一放在表格后面操作列-统一用字体按钮
### 提示信息用 $message,不要用$notify
	
# 使用技术
### Vue v2.6.10
### Vuex v3.0.1
### vue-router v3.0.1
### vmd-ui
### Lvm.js v0.1.0
### Amd
### Echarts v3.4.1
### jquery v1.42