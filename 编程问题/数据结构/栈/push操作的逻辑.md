# push操作的逻辑

1. 判断当前栈是否已满
2. 如果满，重新分配内存，修改`S->top`的地址，重新设置当前栈已分配大小`S->stacksize`，执行3
3. `S->top`自增1并赋值

## 流程图

<div align=center>

![顺序结构push的操作流程](/编程问题/数据结构/栈/images/顺序结构push的操作流程.png)

</div>