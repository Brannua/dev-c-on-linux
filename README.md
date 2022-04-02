> Try on manjaro-linux，参考[视频教程](https://www.bilibili.com/video/BV1fy4y1b7TC)

#### Install（gcc、gdb、cmake）

```bash
sudo pacman -S gcc 
sudo pacman -S gdb
sudo pacman -S cmake

# 以上 3 条命令可合并成 1 条命令
sudo pacman -S gcc gdb cmake

# 验证安装是否成功
gcc --version
gdb --version
cmake --version
```

#### gcc 编译器

- GNU Compiler Collection

- 支持编译（Fortran、C/C++、Objective-C、Objective-C++、Go）等高级编程语言

```bash
> tldr gcc

gcc

Preprocess and compile C and C++ source files, then assemble and link them together.
More information: https://gcc.gnu.org.

...

> tldr g++

g++

Compiles C++ source files.
Part of GCC (GNU Compiler Collection).
More information: https://gcc.gnu.org.
...

```

#### gdb 调试器

- GNU Debugger，主要功能有：

  1. 单步执行程序
  2. 断点调试
  3. 监视程序中变量值的变化
  4. 动态改变程序的执行环境
  5. 分析崩溃程序产生的 core 文件
  6. ...

> 需使用`-g`进行编译，得到的编译产物才能被 GDB 调试
>
> 在 GDB 环境中不输入任何命令直接敲击回车就会执行上一条命令

#### cmake

- 一款跨平台的编译构建工具

- 支持以简单的语句描述所有平台中代码的编译过程

![image-20211004123314478](https://aliyun-oss-lpj.oss-cn-qingdao.aliyuncs.com/images/old-from-gitee-2022-03-25/by-picgo/image-20211004123314478.png)

![image-20211004123944886](https://aliyun-oss-lpj.oss-cn-qingdao.aliyuncs.com/images/old-from-gitee-2022-03-25/by-picgo/image-20211004123944886.png)

![image-20211004124210150](https://aliyun-oss-lpj.oss-cn-qingdao.aliyuncs.com/images/old-from-gitee-2022-03-25/by-picgo/image-20211004124210150.png)

![image-20211004124427019](https://aliyun-oss-lpj.oss-cn-qingdao.aliyuncs.com/images/old-from-gitee-2022-03-25/by-picgo/image-20211004124427019.png)

![image-20211004124511194](https://aliyun-oss-lpj.oss-cn-qingdao.aliyuncs.com/images/old-from-gitee-2022-03-25/by-picgo/image-20211004124511194.png)

#### vscode 插件

![image-20211003164514863](https://aliyun-oss-lpj.oss-cn-qingdao.aliyuncs.com/images/old-from-gitee-2022-03-25/by-picgo/image-20211003164514863.png)
