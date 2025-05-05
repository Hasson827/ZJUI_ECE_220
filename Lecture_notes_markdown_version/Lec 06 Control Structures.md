## Lec 06 Control Structures

### 控制结构

控制结构是编程的核心，用于决定程序的执行路径和重复执行某些操作。主要有两种：**条件结构**和**循环结构**。

#### 条件结构

条件结构根据某个条件的真假，决定执行不同的代码块。

1. **if 语句**

   - **语法**：`if (condition) action`;

   - **功能**：当`condition`为真时，执行`action`。

2. **if-else 语句**

   - **语法**：`if (condition) action1; else action2`;
   - **功能**：`condition`为真时执行`action1`，否则执行`action2`。

3. **switch 语句**

   - **功能**：根据一个表达式的值，执行多个分支中的一个。
   - **特点**：适用于多分支选择。

#### 循环结构

循环结构用于重复执行代码，直到满足某个条件。

1. **while 循环**

   - **语法**：`while (condition) action;`
   - **功能**：当`condition`为真时，重复执行`action`。

2. **for 循环**

   - **语法**：`for (initialization; condition; increment) action;`

     **功能**：初始化后，检查`condition`，若为真则执行`action`，然后执行`increment`，重复此过程。

3. **do-while 循环**

   - **语法**：`do { action; } while (condition);`

   - **功能**：先执行一次`action`，然后检查`condition`，若为真则继续循环。

   - **特点**：至少执行一次。

4. **break**：跳出循环或`switch`语句。

5. **continue**：跳过当前循环的剩余部分，开始下一次迭代。