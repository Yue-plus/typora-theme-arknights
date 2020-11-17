# typora-theme-arknights

## 主题开发中……

## 参与开发

### 可能需要的文档

- [SASS 中文网](https://www.sass.hk/)

### 环境配置

<!--
- 安装好 [Node.js](https://nodejs.org/en/download/) 环境。
  + > 推荐使用 [淘宝 NPM 镜像](https://developer.aliyun.com/mirror/NPM)
-->
- 安装好 [VScode](https://code.visualstudio.com/) 代码编辑器
- 参考使用 [Visual Studio Code 插件 Live Sass Compiler 可将 Sass 或 Scss 实时编译为 CSS](https://www.sass.hk/skill/sass154.html) 使用以下参数配置插件：

  ```json
  "liveSassCompile.settings.autoprefix": [],
  "liveSassCompile.settings.generateMap": false,
  "liveSassCompile.settings.formats":[

      // 扩展
      {
          "format": "compact",//可定制的出口CSS样式（expanded，compact，compressed，nested）
          "extensionName": ".css",//编译后缀名
          "savePath": "/"//编译保存的路径
      } 
      
  ],

  "liveSassCompile.settings.excludeList": [
      "**/node_modules/**",
      ".vscode/**"
   ],
  ```
- 在 **cmd** 中使用 [`mklink`](https://docs.microsoft.com/zh-cn/windows-server/administration/windows-commands/mklink) 指令创建符号连接到仓库目录，方便调试：

  ```cmd
  mklink <Typora 主题目录>/arknights.css <仓库目录>/arknights.css
  ```

## 友情链接

- [hexo-theme-arknights](https://github.com/Yue-plus/hexo-theme-arknights)：Hexo 博客主题