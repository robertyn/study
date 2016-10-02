<meta http-equiv="refresh" content="2">

# 代码格式化快捷键设置
- Edit - Line - Reindent（中文路径则是：编辑 - 行 - 再次缩进）

- 首先通过以下路径打开用户按键绑定文件：

Preferences → Key Bindings – User

- 后在其中添加以下代码（如果你有需要的话，其中的快捷键组合是可以自己定义的）：
{"keys": ["ctrl+shift+l"], "command": "reindent" , "args":
{"single_line": false}}

# 浏览器实时刷新
```
//在html页面加入如下代码
<meta http-equiv="refresh" content="2">
```

#设置默认编码格式

- 选择菜单Preferences->Settings-User在花括号中添加下面一行代码：
"default_encoding": "UTF-8",


# 设置markdown在浏览器中打开快捷键

```
{
	"keys": ["alt+m"],
	"command": "markdown_preview", 
	"args": {"target": "browser"} 
},

```

# 代码格式化(pretty JSON)
- json格式化 快捷键 `ctrl+alt+j`

# 设置默认编码为utf-8

```
{
	"default_encoding": "UTF-8"
}

```

# 设置sublime自带格式化快捷键

- 默认配置文件

```
"use_entire_file_if_no_selection": true,// 默认不选中时对整个文件做操作
"indent": 4,//缩进
"sort_keys": false,// 默认缩进2个空格，可自定义为缩进4个空格或一个制表符\t
"ensure_ascii": false,// 默认关闭，开启时将对所有非ASCII编码的字符做unicode编码

```

- 快捷键设置

```
{
	"keys": ["ctrl+alt+l"], 
	"command": "reindent" , 
	"args":{"single_line": false}
}

```




# 设置使用默认浏览器打开文件

```
{
	"keys": ["f1"],
	"command": "view_in_browser"
}

```

# 创建文件&文件夹

```

//创建文件与文件夹(advancednewfile)
[
    {
        "keys": [
            "alt+insert"
        ],
        "command": "advanced_new_file_new"
    },
    {
        "keys": [
            "ctrl+alt+insert"
        ],
        "command": "advanced_new_file_new",
        "args": {
            "is_python": true
        }
    }
]


```




