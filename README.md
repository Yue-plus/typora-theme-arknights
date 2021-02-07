# typora-theme-arknights

## 主题开发中……

## 参与开发

> 点击 Typora 的 文件 > 偏好设置 > 通用 > 勾选“开启调试模式”
> 然后再文本编辑区右键会多出一个检查元素，然后就可以像在浏览器中调 css 一样

欢迎[提交反馈](https://github.com/Yue-plus/typora-theme-arknights/issues/new) & [发起 PR](https://github.com/Yue-plus/typora-theme-arknights/pulls)

### 可能需要的文档

- [SASS 中文网](https://www.sass.hk/)
- [如何為 Typora 撰寫客製化樣式](https://pjchender.github.io/2018/04/24/note-%E5%A6%82%E4%BD%95%E7%82%BA-typora-%E6%92%B0%E5%AF%AB%E5%AE%A2%E8%A3%BD%E5%8C%96%E6%A8%A3%E5%BC%8F/)
- [Write Custom Theme for Typora](http://theme.typora.io/doc/Write-Custom-Theme/)

> `html-preview` 文件夹源于 <https://github.com/typora/typora-theme-toolkit>

### 环境配置

- 安装好 [VScode](https://code.visualstudio.com/) 代码编辑器
- 参考使用 [Visual Studio Code 插件 Live Sass Compiler 可将 Sass 或 Scss 实时编译为 CSS](https://www.sass.hk/skill/sass154.html) 使用以下参数配置插件：

  ```json
  "liveSassCompile.settings.autoprefix": [],
  "liveSassCompile.settings.generateMap": false,
  "liveSassCompile.settings.formats":[

      // 扩展
      {
          //可定制的出口CSS样式（expanded，compact，compressed，nested）
          "format": "expanded",
          //编译后缀名
          "extensionName": ".css",
          //编译保存的路径；在偏好设置 > 外观 > 打开主题文件夹
          "savePath": "C:\\Users\\Yue_plus\\AppData\\Roaming\\Typora\\themes"
      } 
      
  ],

  "liveSassCompile.settings.excludeList": [
      "**/node_modules/**",
      ".vscode/**"
   ],
  ```


## 友情链接

- [hexo-theme-arknights](https://github.com/Yue-plus/hexo-theme-arknights)：Hexo 博客主题