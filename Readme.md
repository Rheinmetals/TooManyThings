TooManyThings 是基于Python语言及Tkinter模块开发的一款个人待办事项助手，提供待办添加，待办四项分类法，待办查询，待办编辑，待办删除功能。
本软件数据库采用MySQL语言，无联网同步功能，属于本地系统。
# 一、UI说明
当你启动UImain.py时，会显示如下的页面（图一）
![[Pasted image 20250405143426.png]]
（图一）

点击确定后进入主页面（见图二）。主页面左上角选项框和上方“标题-截止日期”显示框联动，可以选择想要展示的内容，包括：
“今日待办事项”
“全部待办事项”
“重要并且紧急”
“不重要但紧急”
“重要但不紧急”
“不重要不紧急”
“已经完成事项”
七个选择项。不同选择项所对应展示的内容不同。
![[Pasted image 20250405143846.png]]
（图二）

下方添加待办处可以输入标题，内容，截止日期，并选择待办等级（见图三）。**注意：截止日期格式必须为YYYY-MM-DD格式，否则可能会出现显示错误。**
![[Pasted image 20250405144300.png]]
（图三）

全部输入完成后点击保存，会将内容输入进显示框内，并清空“添加待办”中的内容（见图4）。
![[Pasted image 20250405144349.png]]
（图四）

当双击显示框内的内容时，会跳转到“修改待办页面”（如图五）。
![[Pasted image 20250405145303.png]]
（图五）

在此处可以对待办的标题、内容、截止日期、待办等级、完成情况进行修改。修改完成后点击“保存修改”就完成了修改（见图六），点击删除任务会从数据库中删除该任务（见图七、图八）。操作完成后会刷新显示框。
![[Pasted image 20250405145621.png]]
（图六）

![[Pasted image 20250405145703.png]]
（图七）

![[Pasted image 20250405145722.png]]
（图八）
# 二、后续改进
1. 对UI设计进行优化
2. 添加数据回滚机制
3. 添加图像和文件保存机制