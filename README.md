[视频教程](https://www.bilibili.com/video/BV1fy4y1b7TC)

### 编译器

- GNU Compiler Collection，即：[gcc](https://gcc.gnu.org/onlinedocs/)

- 支持编译（C/C++、Objective-C、Objective-C++、Go）等高级编程语言

- g++ belongs to gcc

### 调试器

- GNU Debugger，即：gdb

- 主要功能

    - 单步执行

    - 断点调试

    - 监视变量

    - 动态改变程序的执行环境

    - 分析崩溃程序产生的 core 文件

    - ...

> 编译时增添 `-g` 编译选项，所得到的编译产物才可被调试

### 编译构建工具：cmake

- 描述了代码的编译过程，跨平台

![image-20211004123314478](https://aliyun-oss-lpj.oss-cn-qingdao.aliyuncs.com/images/by-picgo/image-20211004123314478.png)

![image-20211004123944886](https://aliyun-oss-lpj.oss-cn-qingdao.aliyuncs.com/images/by-picgo/image-20211004123944886.png)

![image-20211004124210150](https://aliyun-oss-lpj.oss-cn-qingdao.aliyuncs.com/images/by-picgo/image-20211004124210150.png)

![image-20211004124427019](https://aliyun-oss-lpj.oss-cn-qingdao.aliyuncs.com/images/by-picgo/image-20211004124427019.png)

![image-20211004124511194](https://aliyun-oss-lpj.oss-cn-qingdao.aliyuncs.com/images/by-picgo/image-20211004124511194.png)

### Installation

```bash
pacman -S gcc gdb cmake
```

