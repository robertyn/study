<meta http-equiv="refresh" content="2">

# 代码格式化快捷键设置
- Edit - Line - Reindent（中文路径则是：编辑 - 行 - 再次缩进）

- 首先通过以下路径打开用户按键绑定文件：

` Preferences → Key Bindings – User `



- 后在其中添加以下代码（如果你有需要的话，其中的快捷键组合是可以自己定义的）：
{"keys": ["ctrl+shift+l"], "command": "reindent" , "args":
{"single_line": false}}

# 代码格式化插件

- html/css/js prettify(可以格式化html/css/js)

- prettyJSON(仅仅可以格式化json)

- standarformat(不好用)


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

# 基本使用配置
- 选择主题

```
"color_scheme": "Packages/Theme - Brogrammer/Brogrammer.tmTheme",

```

- 设置字体大小

```
"font_size": 16,

```

- 翻译出来的忽略什么什么的(英语渣,不知道干什么的,我也不会)

```

"ignored_packages": ["Vintage"],

```

- 编辑行高亮

```
"highlight_line": true,

```

- 在sublime窗口的左上角会显示当前编辑的文件的绝对路径

```

"show_full_path": true,

```

- 文档树名称加粗显示

```

"bold_folder_labels": true,

```

- 失去焦点保存文档(要是没有这个功能我肯定会把sublime丢弃)

```

"save_on_focus_lost": true,

```

- 防止滚动过头

```

"scroll_past_end": true,

```

- 显示当前文件编码

```

"show_encoding": true,

```


"show_line_endings": true,

- tab换行

```

"tab_size": 2,
"translate_tabs_to_spaces": true,

```

- 保存时去掉空格

```

"trim_trailing_white_space_on_save": true

```




