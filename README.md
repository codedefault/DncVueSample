## 关于DncVueSample

**VncVueSample**由**码友网**(https://codedefault.com)发布并提供更新支持。

作者:Rector

演示地址：https://codedefault.github.io/DncVueSample/

**DncVueSample：** 是一个基于Vue.js + iview 前端框架搭建的后台管理系统模板，适用于如：OA,CRM,CMS等管理系统的后台开发。 

## 模板简介

### 版本信息

**DncVueSample**当前依赖的组件的版本信息如下：

**Vue.js:** 2.5.17
**iview:** 3.1.0 

### 布局和菜单

该模板以左菜单，右操作面板来布局。左侧菜单树目前支持两级菜单，菜单树以JSON格式定义。其中，菜单项支持指定图标，菜单的链接地址等选项，详细的配置属性如：
```
{
    title:"用户及授权",
    name:"1",
    icon:"logo-apple",
    menuItem:[
        {
            label:"用户管理",
            name:"1-1",
            href:"/account/user/list",
            icon:"logo-apple"
        },
        {
            label:"资源管理",
            name:"1-2",
            href:"/account/resource/list",
            icon:"logo-windows"
        },
        {
            label:"角色管理",
            name:"1-3",
            href:"/account/role/list",
            icon:"logo-tux"
        }
    ]
}
```

左侧菜单支持收起和展开，当菜处于收起状态时，只显示菜单项的图标，这样使得整个系统的在横向的操作界面空更宽一些，在数据的展示上效果会更好。 

### 选项卡

右侧操作区是以选项卡(iframe)打开的各个操作界面，每个选项卡页面均为一个独立的页面。

当点击每个选项卡时，左侧菜单会自动跟踪到当前打开的菜单上。

选项卡切换时，支持切换动画效果，视觉体验非常不错。 

### 结束语

 DncVueSample是一个极简的基于Vue.js + iview 实现的静态后台管理系统模板，她仅是一个后台管理系统模板的雏形UI，不涉及系统功能，但所谓“麻雀虽小五脏俱全”，选择DncVueSample作为后台管理系统的初始模板，可以帮助使用者快速地开始项目的开端UI框架的搭建。

> **注：DncVueSample目前没有适配移动端设备和IE10以下古老的浏览器，所以请在PC设备中使用现代浏览器预览和使用。**

### 代码开源

没错，DncVueSample是开源的，你可以使用DncVueSample模板框架做任何的集成或者开发。

源代码托管地址: https://github.com/codedefault/DncVueSample 

**Demo:** [DncVueSample演示地址][1]

[1]: https://codedefault.github.io/DncVueSample/