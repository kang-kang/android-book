# 01 Chapter 2 版本控制及开发规范

## 版本控制

1. 常用软件使用
+ CVS（Concurrent Version System，协同版本控制系统）
+ SVN（SubVesioN，子版本）2001年发布，自由/开源软件
	1. 常用命令
+ Git：The stupid content tracker（傻瓜内容跟踪器），Linux给出的定义
	1. 学习文档：
		+ Pro Git
+ hg：使用习惯类似svn，与git同为分布式版本控制系统

2. SVN 使用的工作流程
	+ 更新（update）
	+ 修改
	+ 提交（commit）

3. SVN 目录组织
	+ trunk
	+ tags
	+ branch
	
## 编码规范

1. 参考java代码规范，如下：
2. 命名：有意义，尽量不缩写
3. packneme：以com.ginwave.----开头
4. 代码：每行不超过80字符
5. 方法：不超过40行，可拆分
6. 字符串：尽量定义在xml文件中，不在代码里面定义
7. 编码：使用utf-8
8. 注释：尽量不使用中文，参考javadoc

