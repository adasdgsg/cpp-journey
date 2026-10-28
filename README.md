# cpp-journey

我的 C / C++ 学习记录。从零开始，一步一步往上走。

## 环境

| 项 | 值 |
|---|---|
| 系统 | Ubuntu 24.04.5 LTS（VirtualBox 虚拟机） |
| 编译器 | gcc 13.3.0 |
| 调试器 | gdb 15.1 |
| 版本控制 | git 2.43 |
| 从 Windows 连过来 | `ssh -p 2222 hhhnhlimnh@127.0.0.1` |

## 目录

```
.
├── hello.c         第一天：hello world
└── c-basics/       计算器三代 + 逐文件问题清单
    ├── README.md
    ├── 2222 - 副本.c
    ├── 3333.c
    └── FileName.c
```

## 进度

| 日期 | 学什么 | 产出 |
|---|---|---|
| 2026-10-27 | 跑通第一个程序 | `hello.c` |
| 2026-10-28 | 回顾自己的旧代码，整理问题清单 | `c-basics/` |

## 怎么跑

```bash
gcc -Wall -Wextra hello.c -o hello && ./hello
```

`-Wall -Wextra` 是必须带的：它们会把「用了没初始化的变量」「函数缺返回值」这类问题提前喊出来，
省掉一半调试时间。
