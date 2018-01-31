# stylus-assist
帮助vue.js开发者 编辑 stylus 样式

2018.1.8

#### 获取Plugin
直接从idea插件仓库中搜索 stylus-assist

#### 快捷键
windows: `Alt + insert`, Mac: `control + Enter`

#### 功能介绍
* GoCss 
    * 跳转到样式
        * .vue 文件
        * .pug 跳转到 .styl 文件
    * 新增样式
        * 没有匹配的样式 创建标准格式class名称，例如：$style.aBC => .a-b-c
* PasteCss 格式化从其他地方复制的样式
    * margin:0;  =>  margin 0
    
* GoCss
    * Jump to stylus css
         * .vue file
         * .pug jump to .styl file
    * New class mode
         * If plugin can not find selected class,it will think you want to create a new class,such as：$style.aBC =&gt; .a-b-c
* PasteCss format some css you copy from another place, such as chrome or files
    * margin:0;  =&gt;  margin 0

#### 获取帮助以及建议
QQ:11563928

#### 更新日志
* 1.1.0 changes: 新增pug文件跳转styl文件的支持
* 1.1.1 changes: 修复bug
* 1.1.2 changes: 打包问题
* 1.1.3 changes: 新增光标位置自动选择，适用于：.~"的class
* 1.1.4 changes: 优化了选择逻辑，手动选择和自动选择将更加流畅，不光适用于.~"
* 1.1.5 changes: 修复了一个匹配bug，之前container有可能会误匹配到.container-any，现在将正确匹配到.container
* 1.2.0 changes: 新增功能PasteCss,该功能可以将从chrome中调试的css样式,直接按照标准格式粘贴入stylus
* 1.2.1~1.2.3 changes: 支持多平台，修复一些小问题
* 1.2.4 changes: 应平台要求，添加新的英文描述，需要中文描述的，可以去github查看。
* 1.2.5 优化PasteCss插入方式，现在会正确插入到指定位置。新增选中部分样式，可以直接替换插入，注意替换插入包含两步：删除和插入，因此撤销时需要两次才能撤销完善。

#### Eggs
![image](https://user-images.githubusercontent.com/13230237/34660350-9395c908-f47c-11e7-8f47-a383aabcf18e.png)