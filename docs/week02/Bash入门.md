# Bash入门

``` Bash
# 查看当前使用的shell
$ echo $0
# 查看当前用户默认使用的shell
$ echo $SHELL
```

- `PS1` 一级提示符，等待命令输入时的提示符
- `PS1` 二级提示符，多行输入提示符

上一条命令的退出状态可以用`$?`变量来获取，常见的值：

- 0：成功
- 1：未知错误
- 126：命令无法执行
- 127：无效命令
- 130：通过ctrl+c退出

脚本中控制退出状态：`exit 状态值`，默认状态值为0

