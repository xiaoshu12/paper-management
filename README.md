# 论文管理

公开网站：https://xiaoshu12.github.io/paper-management/

## 添加论文分析

1. 将每篇论文分析整理为 JSON 文件，放在 papers/ 目录，例如 papers/example.json。JSON 包含副标题、作者、期刊、标签、核心判断和 sections 数组。每个 section 包含 id、nav 和 html 正文。
2. 在 papers.json 中添加一条目录记录：

   {"id":"example","title":"论文标题","year":"2026","file":"papers/example.json"}

3. 提交到 main 分支。GitHub Pages 会自动重新发布。论文会出现在左侧导航中，点击后按网站统一布局阅读。

id 使用小写英文字母、数字和连字符，且每篇论文不重复。title、year 和 file 可以按实际内容修改。

## Notes

Notes 仅保存在当前浏览器的本地存储中，不会上传到 GitHub，也不会让网站访客看到。支持新增、编辑、删除，以及通过 JSON 文件导出和导入备份。换设备或清除浏览器数据前，请先导出备份。
