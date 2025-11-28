## XP.css 简体中文化

尝试对 [botoxparty 的 XP.css](https://github.com/botoxparty/XP.css/)进行简体中文化。

XP.css 是一个 CSS 文件，能够将语义化的 HTML 呈现得美观大方。该文件不包含任何 JavaScript 代码，能够与你的前端框架兼容。

### 使用方法

在&#60;head&#62;里边使用&#60;link&#62;来导入css。

```html
<!DOCTYPE html>
<html lang="zh-CN">
  <head>
    <title>XP.css 示例</title>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="https://noelle2alternate.github.io/XP.css/xp.css" />
  </head>

  <body>
    <div class="window" style="margin: 32px; width: 250px">
      <div class="title-bar">
        <div class="title-bar-text">
          示例标题
        </div>
      </div>
      <div class="window-body">
        <p>示例文本</p>
      </div>
    </div>
  </body>
</html>
```

有关此库组件的具体说明，请参阅[文档页面](https://noelle2alternate.github.io/XP.css/)。

### 许可协议

[MIT](https://github.com/Noelle2alternate/XP.css/blob/main/LICENSE)
