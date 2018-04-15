## 科恩实验室面试题(部分）
### 一面：
1.x64调用约定

    rdi,rsi,rdx,rcx,r8,r9

2.git分支回滚

    git reset --hard commit_id

3.怎么开启gdb core dump

    ulimit -u

4.movsx什么意思

带符号扩展传送指令

     80h = 1000 0000 最高位为符号位, 即符号位为1
    则MOVSX AX, BL后, AX = 1111 1111 1000 0000 = FF80h 
    
    61h = 0110 0001 最高位为符号位, 即符号位为0
    MOVSX EDX, BL（BL = 0x61)
    则EDX = 0000 0000 0000 0000 0000 0000 0110 0001 = 00000061h

5.写一个函数，能够接受不定长参数(任意语言）

### 二面

1.unsigned char 和 char有没有区别

2.用英语讲一个自己比较熟悉的漏洞

3.这个漏洞怎么打补丁

4.这个漏洞的模型在哪里还有影响

## 深信服面试(部分）
### 一面：
1.栈和堆的区别

2.分析过什么漏洞，都是什么类型的

3.根据你做过的项目问你问题

### 二面：
1.复现过多少个漏洞

2.从哪些地方了解漏洞

3.发表过文章吗
