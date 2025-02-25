# Changelog

## v1.1.5 (31/07/2021)
fix：修复CSDN博客页面元素改变导致的爬取失败的问题。

---

## v1.1.4 (15/10/2019)
:sparkles:添加的新特性：

1. 添加对主方法的测试。
2. 删除主函数中的休眠函数，加快运行速度。

---

## v1.1.3(15/10/2019)

:sparkles:添加的新特性：更新运行jar的脚本。

---

## v1.1.2 (15/10/2019)

:sparkles:添加的新特性：

1. 为分类专栏实体类添加另一个属性：(分类专栏)数量。
2. 之前每个分类专栏的博客数量是从网页上探测性进行统计的，当数量为20的整数倍时会发生问题，现在改为直接从博客主页爬取此数据，不仅可以节省时间，而且准确。
3. 补充文档说明。

---

## v1.1.1 (14/10/2019)

:bug:修复bug：

1. 修复了当运行时间超过60秒，时间显示不正确的问题。

:sparkles:添加的新特性：

1. 调整了部分输出语句

   - 删除了之前的输出文件内容的语句；添加了程序前后的“字符画”形式的问候语。
   - 优化部分输出语句。

2. 添加了一个计时器，当程序运行时间超过5分钟时，强制停止，评定为网络有问题。

---

## v1.1.0 (14/10/2019)

:sparkles:添加的新特性：

1. 增加了工具的执行时间。
2. 更新了main方法的测试。
3. 优化用户体验，调整了部分输出语句。
4. **添加执行jar的脚本，方便操作**。

---

## v1.0.2 (13/10/2019)

:bug:修复bug：

- 修复了“CSDN页面的关键元素发生变化，导致爬取数据失败的bug"。

:sparkles:添加的新特性：

1. 修改爬虫工具类`Utility`为`SpiderUtil`，并优化了其方法。
2. 优化用户体验：当爬取数据出错时，给出对应提示，如用户名不存在、页面元素发生变化时。
3. 文件名添加时间后缀，以便备份。设置文件编码为utf8。
4. 添加相关方法的测试，提高测试覆盖率。
5. 更新依赖，让`Travis-CI`在集成时能支持jdk1.8的lambda表达式。
6. 添加该工具的“局限性”说明、更新日志。

---

## v1.0.0 (30/09/2019)

✨ 功能介绍
- 输入用户名即可自动生成该用户的CSDN博客的导航目录。

:memo:使用说明
- 下载发布包:package:，按照`README`进行使用。
