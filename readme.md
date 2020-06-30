# Quick Led

## 1.简介

**Quick Led** 旨在提供一个快捷易用的led驱动包。

### 1.1目录结构

`Quick Led` 软件包目录结构如下所示：

``` 
qled
├───inc                             // 头文件目录
│   |   qled.h                  	// API 接口头文件
│   └───qled_sample.h           	// 示例头文件
├───src                             // 源码目录
│   |   qled.c                  	// 主模块
│   └───qled_samplec             	// 示例模块
│   LICENSE                         // 软件包许可证
│   README.md                       // 软件包使用说明
└───SConscript                      // RT-Thread 默认的构建脚本
```

### 1.2许可证

Quick Led package 遵循 LGPLv2.1 许可，详见 `LICENSE` 文件。

### 1.3依赖

- RT_Thread 4.0

## 2.使用

### 2.1获取组件

- **方式1：**
通过 *Env配置工具* 或 *RT-Thread studio* 开启软件包，根据需要配置各项参数；配置路径为 *RT-Thread online packages -> system packages -> qled* 


### 2.2配置参数说明

| 参数宏 | 说明 |
| ---- | ---- |
| QLED_TOTAL 				| 支持的led总数 			|
| QLED_TIME_UNIT_MS 		| led闪烁时间的时间单位 	|
| QLED_THREAD_NAME 			| led驱动线程名称			|
| QLED_THREAD_STACK_SIZE 	| led驱动线程堆栈尺寸 	|
| QLED_THREAD_PRIO 			| led驱动线程优先级 		|
| QLED_USING_SAMPLE 		| 使用示例 				|
| QLED_RUN_PIN 				| 示例运行灯引脚 			|
| QLED_SOS_PIN 				| 示例SOS信号灯引脚 		|

## 3. 联系方式

* 维护：qiyongzhong
* 主页：https://gitee.com/qiyongzhong0/rt-thread-qled


