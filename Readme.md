
个人配置的vscode的Markdown Preview插件的主题<br>
主要以热门主题[Aura](https://github.com/daltonmenezes/aura-theme)为主，
如果喜欢这种风格的主题，并在vscode上书写一些Markdown文档，可以尝试使用这个主题

下面是一些演示

<img src="/images/display1.png" alt="演示一">
<img src="/images/display2.png" alt="演示二">

详细可查看[Displays](./Displays/test.md)

# Configuration

## 1. 安装Markdown Preview Enhanced插件
在VSCode中搜索并安装`Markdown Preview Enhanced`插件

## 2. 更换主题
按下快捷键`Ctrl+Shift+V`或者`Ctrl+K V`打开Markdown Preview Enhanced插件的预览窗口<br>
在预览窗口中右键，可以看到*主题*选项，把三个主题统一改成dark类型
>因为Aura主题是黑色系主题，所以选择dark类型的主题，防止自己配置的主题突然出现白色块

## 3. 打开Markdown Preview Enhanced插件的配置文件
按下快捷键`Ctrl+Shift+P`，输入`Markdown Preview Enhanced: Open Custom CSS`，打开配置文件，加入下面的信息
```css
  font-size: 20px;
  // 背景色 
  background-color: #21202E;
  border-radius: 4px;

  // 前景，代码块字体色
  pre,
  code {
    color: #54C59F;
  }

  // 有序无序最前面的标准色改变，不改变后续文字信息 
  ul li::marker {
    color: #8464A9;
  }
  ol li::marker {
    color: #8464A9;
  }
```
