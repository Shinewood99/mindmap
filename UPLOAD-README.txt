法商笔记｜并购知识图谱——静态测试包

上传方式：
1. 解压 ZIP。
2. 将解压后的所有文件一起上传到目标网页目录。
3. 确保 index.html 和 assets 文件夹保持在同一层级。
4. 不要只上传 index.html，也不要修改 assets 内的文件名。
5. 建议先上传到新目录，例如 /lawmap/，不要直接覆盖现有 mindmap。

建议测试地址：
https://ydzl.net/lawmap/

这个包：
- 不需要 Node.js
- 不需要数据库
- 不引用外部 JavaScript CDN
- 可以部署在普通 Nginx、Apache、宝塔、OSS 或静态托管平台

如果页面空白，请检查：
- 是否完整上传了 assets 文件夹
- 服务器是否允许访问 .js 和 .css 文件
- 是否通过 http/https 地址访问，而不是双击本地 index.html
