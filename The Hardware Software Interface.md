# The Hardware Software Interface

- 华盛顿大学CSE351, 以此温习和学习计算机组成原理

### Section 1

- Processors only know 0 or 1, 0 -> low V 1-> high V

- CPU和memory之间存在着宽带宽，因为两者经常交换数据

  CPU要从内存里面取数据，放在memory里面，然后进行计算处理再放回memory

  - 如何提高CPU处理速度
    1. 提高带宽
    2. 在CPU放缓存

- CPU中用Instruction cache放指令，Register放数据

- C语言不会检查是否out of bound

- Extract the sign of bit of a signed integer

​       (x >> 31) & 1

- Arithmetic >> 2; x=10100100->11101001
- 二进制来表示小数， 101.11-> 8 + 2 + 1/2 + 1/4
- 

