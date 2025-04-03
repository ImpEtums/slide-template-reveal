# Reveal-md 极简PPT模板

这是一个基于reveal-md的极简风格PPT模板，使用Markdown编写内容，支持数学公式和代码高亮。

## 使用说明

1. 确保已安装Node.js
2. 全局安装reveal-md:
   ```
   npm install -g reveal-md
   ```
3. 运行演示:
   ```
   reveal-md template.md --css custom.css
   ```

## 自定义内容

- 编辑`template.md`文件修改演示内容
- 使用`---`分隔幻灯片
- 主标题页会自动居中，后续幻灯片标题位于左上角

## 功能支持

- 数学公式（使用$或$$包裹）
- 代码块（使用```包裹）
- 列表、粗体、斜体等Markdown格式
