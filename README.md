# DOS 简单命令

```bash
C:\〉D:
:: 回车后进入 D 盘

D:\〉CD DOS
:: 进入 DOS 子目录

D:\dos〉DIR
:: 列出目录中的文件

D:\dos〉DEBUG
:: 进入 DEBUG
```

![img](https://doc.shiyanlou.com/userid12501labid332time1419944230704/wm)

#### （1）数据寄存器

数据寄存器中每个寄存器又可以分为 2 个 8 位的寄存器。分别为 AH、AL，BH、BL，CH、CL，DH、DL。H 表示高字节（高 8 位）寄存器、L 表示低字节（低 8 位）寄存器。

例如：用 AX 寄存器存放一个字 1234H，表示为 (AX)=1234H，即高字节 12 放在 AH，低字节 34 放在 AL 中。

#### （2）地址寄存器

地址寄存器包括指针和变址寄存器 SP、BP、SI、DI 四个 16 位寄存器。

顾名思义，它们可用来存放存储器操作数的偏移地址。另外，它们也可以作为通用寄存器用。

#### （3）段寄存器

8086CPU 有 4 个 16 位的段寄存器，分别是 CS 代码段寄存器、DS 数据段寄存器、ES 附加段寄存器、SS 堆栈段寄存器。