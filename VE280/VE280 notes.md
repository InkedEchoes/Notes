## L2:
![[Pasted image 20240927142737.png]]

##### cp

##### rm
> rm 一个文件夹 和 rm 一个文件命令不同
> 删除非空目录 和 空目录 的命令不同

##### mv
```bash
mv file1 file2 // rename 
mv file1 dir // mv file into directory
mv dir1 dir2 //rename dir1 as dir2(如果dir2不存在)，如果存在的话就是mv
```



### long format
- permission owner grou
### Other commands
- single match (tab)
- Compare:
```bash
diff text1.txt text2.txt
```


```bash
sudo apt-get install emacs
```
## L3:Develop && Compilation
```bash
g++ -g *-g for out putting the deugging information*

```
![[Pasted image 20240926150821.png]]

#### .o file
源代码--> 机器代码
.o 文件包含了经过编译的机器代码（二进制代码）不完整的（没有被链接器处--导致包括为解析符号
需要其他的链接器
#### .exe
```bash
command: g++ -o program source.cpp
```

然后生成exe（binary file 二进制 可执行

#### .h file
**class definition**(注意！！！)

```C++
#include "add.h"
```
本质是COPY & PASTE


### reference
- difference between reference and pointer
- 
# l4
- **lvalue
- **rvalue
   - 只能出现在右边
   - 
### Function declaration 
```c
int add(int a, int b);
```
### Function definition

### Function call Mechanisms 
- Pass by value
- Pass by reference

![[Pasted image 20241010151502.png]]
> initialize的方法：绑定，后续无法修改指向的～
> ![[Pasted image 20241010152315.png]]
> 绑定（成为const）
> 然后修改它对应的值
> 