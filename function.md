# B188功能函数汇总

## 一. 介绍关于B188功能

* 中断获取功能
* 主从设备同步
* 获取 als cct 光谱 flicker数据
* binning
* 等等（后续补充。）

## 二. B188平台驱动接口
### 1. 初始化寄存器

初始化主要涉及的参数有哪些:

```c
static void opus_one_register_iic_ops(struct cct_rear_i2c_operations *const ops);
```

| 参数 | **描述**    |
| --------- | ------------------ |
| struct cct_rear_i2c_operations *const ops       | Pin number         |

### 2. 初始化寄存器

初始化主要涉及的参数有哪些:

```c
void opus_one_get_para_info();
```

| Parameter | **Discription**    |
| --------- | ------------------ |
| pin       | Pin number         |
| mode      | Pin operation mode |

### 2. 初始化寄存器

初始化主要涉及的参数有哪些:

```c
static void opus_one_get_para_info(int para[]);
```

| Parameter | **Discription**    |
| --------- | ------------------ |
| int para[]    | Pin number     |
