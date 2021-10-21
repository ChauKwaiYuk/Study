markdown自带的`[TOC]`不能再GitHub上面显示目录，所以只能使用其他办法来生成目录。

这里将记录我找到的方法。

1. 首先确保已经按照自己的要求划分好各级目录

2. 安装doctoc

   ```npm
   npm i doctoc -g
   ```

3. 接下来就是执行命令实现自动生成

   ```
   doctoc xxx.md
   ```



**By Chau**

