# 模板
*Templates*

所有模板都存储在文件夹“900_Supporting_Files/910_Templates”中。
保险库中使用了两种不同的模板：

- 插件“模板”的模板
- 插件“定期笔记”和“日历”的模板

## "Templater"模板
*Templates for "Templater"*

它们用于为目标管理、日志（每日笔记除外）和知识管理生成笔记。
支持的格式：例如`<% tp.file.creation_date() %>`

##  "Periodic Notes" 和 "Calendar"模板
*Templates for  "Periodic Notes" and "Calendar"*

它们用于生成每日笔记和定期回顾，它们存储在子文件夹“Periodic_Note”中。  
支持的格式：例如`{{date+7d:gggg-[W]ww}}`和`<% tp.file.creation_date() %>`。
