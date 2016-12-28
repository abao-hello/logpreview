# 介绍 
logpreview是一个远程收集日志的工具，旨在方便查看项目
运行中的各种错误和异常日志信息。目前工具处于第一个版
本状态，正在进行第二个版本开发测试。

# 功能
1. 收集项目日志。
2. 远程访问日志数据，分析日志。
3. 日志持久化处理，开发版本中准备使用redis做缓存和数
据的持久化。
4. 后续扩展功能再补充。

# 安装
1.安装go编译器版本 (开发使用go1.5)。
2.使用go get github.com/abao-hello/log-preview会将项
目下载到默认第一个GOPATH目录环境目录下面
3.使用进入到ulog目录下面，使用go install命令会在
  bin目录下面生成对应的可执行文件。