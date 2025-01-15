# QilingLab
存放QilingLabWP
# Lab1

# Lab2
qiling有四种实现hook的API
- [ ] QL_INTERCEPT.EXIT：在系统调用执行完成之后立即执行hook函数。

- [ ] QL_INTERCEPT.ENTER：在系统调用执行之前执行hook函数。

- [ ] QL_INTERCEPT.EXIT_TREE：在系统调用执行完成并返回后，执行完其他所有系统调用的hook函数之后再执行当前系统调用的hook函数。

- [ ] QL_INTERCEPT.EXIT_ALL：在系统调用执行完成并返回后，执行所有系统调用的hook函数。
