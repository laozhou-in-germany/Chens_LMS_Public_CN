# 文件夹结构、笔记类型和符号
*Folder Structure, Note Types and Symbols*

## 文件夹结构
*Folder structure* 

此 Vault 具有以下文件夹结构：

###### **000_Drafts**: 所有稍纵即逝的笔记和捕获的笔记  
###### **100_Goal_Management**: 目标管理的所有笔记  
  - 110_🏛Pillars  
  - 111_🔁Routines  
  - 112_🤯Mindsets  
  - 130_🌟Value_Goals  
  - 150_🎯Outcomes  
  - 170_💎Projects  
  - 171_📽Video_Projects  
###### **300_Journal**: 日志的所有笔记  
  - 310_🌄Daily
  - 320_🎉Events
  - 340_🖥️Meetings
  - 391_👤Person
###### **500_Knowledge_Management**:  知识管理的所有笔记
  - 510_📔Literature_Notes
  - 530_⚛️Atomic_Notes
  - 550_🌲Evergreen_Notes
  - 570_🗩Topics
###### **700_Periodic_Review**: 定期回顾的所有笔记
  - 710_❇Weeks  
  - 730_📅Months  
  - 750_⌛Quarters  
  - 770_🌏Years  
###### **900_Supporting_Files**: 此保管库的所有支持类文件

## 笔记类型
*Note types*

文件夹结构基于笔记类型。每个文件夹存储一种笔记类型的笔记。  
yalm front matter 用于记录笔记类型。

~~~
---
fileClass: literature-note  
---
~~~

属性名称 `fileClass` 是为了更好地与插件 [Supercharged links](https://github.com/mdelobelle/obsidian_supercharged_links) 兼容。 

该库提供了许多用于自动化的仪表板和功能。它们由插件 [Dataview](https://github.com/blacksmithgu/obsidian-dataview) 通过查询笔记类型和其他元信息来实现。这是查询结果的一个示例。

![image-20220803212723887](images/image-20220803212723887.png)

## 符号
*Symbols*

每个笔记类型都由一个符号表示。 有关符号的定义，请参见文件夹结构。 此外，笔记评分``score``也用符号表示：

- ◷：×
- ◔：xx
- ◑：xxx
- ◕：xxxx
- ●：xxxxx

符号会自动显示在笔记标题之前或之后。 它们在阅读模式或dataview查询结果（实时预览模式）中可见。 需插件 [Supercharged links](https://github.com/mdelobelle/obsidian_supercharged_links) 支持此功能。
