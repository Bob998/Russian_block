# C++实现俄罗斯方块

## 实验内容：

实现俄罗斯方块主要函数的设计，完成基本功能并运行

### 实验知识点：

- 窗口的绘制
- 方块类的设计
- 旋转算法
- 移动、消除函数

### 实验环境

- Linux 18.04 终端
- g++编译器
- ncurses库

### 编译程序

编译命令要加上-l选项引入ncurses库：

```
g++ main.cpp -o main -l ncurses
```

### 运行程序：

```
./ main
```

### 运行结果：

![image-20210303223640803](C:\Users\Bob\AppData\Roaming\Typora\typora-user-images\image-20210303223640803.png)

## 开发准备：

### 安装ncurses库：

```
sudo apt-get update
sudo apt-get install libncurses5-dev
```

### 编程解决问题：

- 显示方块

- 实现方块的移动

- 方块选择

- 层满的方块要消行

- 提示下一个方块形状

  

