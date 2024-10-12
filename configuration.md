
# 配置信息
要自定义 Markdown 文件的 CSS，请按`cmd-shift-p`，然后运行`Markdown Preview Enhanced: Customize CSS (Global)`或`Markdown Preview Enhanced: Customize CSS (Workspace)`命令。

颜色提取先按 `ALT + 2` 然后按 `ALT `
## 背景颜色
```css
background-color: #21202E;
```
## 字体和标题颜色
```css
h1,
h2,
h3,
h4,
h5,
h6
{
color: #8464C6;
}
color: #8464C6;
```
## 序列号
```css
ul li::marker {
    color: #8464A9;
  }

  ol li::marker {
    color: #8464A9;
  }
```
演示

1. 序列号修改了但是后续每日没改

- 11
* dd