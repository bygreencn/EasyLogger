# linux demo

---

## 1、简介

使用GCC编译。通过 `main.c` 的 `test_elog()` 方法来测试日志的输出。已在 `easylogger\inc\elog_cfg.h` 开启异步输出模式。

### 1.1、使用方法

使用前需提前配置好编译环境，配置成功后，执行 `make.sh` 脚本，等待编译完成后，运行 `out\EasyLoggerLinuxDemo` 即可看到运行结果。

## 2、文件（夹）说明

`easylogger\port\elog_port.c` 移植参考文件

## 3、其他功能

可以打开 `main.c` 的62-68行中的部分注释，来测试以下功能。

- 第62行：动态使能或失能日志输出
- 第64行：动态设置过滤优先级
- 第66行：动态设置过滤标签
- 第68行：动态设置过滤关键词
