# VSCODE插件使用技巧

## Auto Close Tag自动补全关闭标签

安装即可用，你敲html标签，它能自动帮你补全。

## Auto Rename Tag自动重命名标签

在你更改标签名的时候，它会帮你把对应的关闭标签页进行同样的更改。

## Beautify

HTML、CSS、JS、JSON SASS语法高亮,格式化代码的工具

ctrl+shift+p输入beautify就有提示。

## Better Comments

不同的注释显示不同的颜色，*，？，！起头然后开始写，你可以看到注释的颜色是不同的

## Bracket Pair Colorizer

对应括号显示同样的颜色，以防我们搞混括号配对。

## Code Runner

帮助我们运行代码的工具，比如你要运行一个js文件，打开这个文件，然后ctrl+alt+n就可以运行文件，系统自动调用node帮我们运行文件。

## Document This(js 和typescript的注释模板)

ctrl+alt+D，两次（注意：新版的vscode已经原生支持,在function上输入/** tab）
![image](https://upload-images.jianshu.io/upload_images/6870630-c0d6f349947f4b52.gif?imageMogr2/auto-orient/strip)

## Easy Sass编译输出css

第一步：在 VS Code 中使用 Ctrl+Shift+P打开命令面板，输入Preferences: Open User Settings或Preferences: Open Workspace Settings。

```ccs
usersittings
    "easysass.compileAfterSave": true, //保存即编译
    "easysass.formats": [ //nested：嵌套缩进的 css 代码。
    //expanded：没有缩进的、扩展的css代码。
    //compact：简洁格式的 css 代码。
    //compressed：压缩后的 css 代码

            {
                "format": "expanded",
                "extension": ".css"
            },
            {
                "format": "compressed",
                "extension": ".min.css"
            }
        ],
    "easysass.targetDir": "css/" //自定义输出路径，如果不定义就会默认输出跟当前sass一样的路径。

```

## JavaScript (ES6)code snippets

es6的代码自动补全

## jQuery Code Snippets

jquery代码自动补全，比如你要写一段ajax你需要输入jqAjax然后敲回车。

## Node.js Modules IntelliSense

提供JavaScript和TypeScript导入声明时的自动补全。

## Path Autocomplete 路径补全工具



## Project Manager 项目管理工具

这两种方式对于需要经常切换项目时，比较耗时
为解决这个问题，vscode提供了Project Manager插件管理，开发时常用的项目

（1）command+ shift + p打开配置文件，
输入 Project Manager: Edit Projects

```js
[
	{
		"name": "nuxtest",
		"rootPath": "e:\\nuxtest",
		"paths": [],
		"group": ""
	},
	{
		"name": "vuetest",
		"rootPath": "e:\\vuetest",
		"paths": [],
		"group": ""
	}
]

```

（2）在左侧图标栏下就会有个小文件夹的选项，点击进去就可以切换项目了。

## Vetur

语法高亮、智能感知、Emmet等帮助我们快速开发vue

## vscode-icons 为文件管理器增加文件类型图标

## vue-beautify

vue文件格式化，有三种用法
1、快捷键ctrl+shift+f ;
2、在文件中右键选择Beautify Vue ;
3、按f1,搜索 Beautify Vue然后点击.


## markdown的使用

