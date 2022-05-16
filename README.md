# MSP430F5529 LaunchPad扩展板
Master分支扩展板版本编号为V2.2，适用的案例工程为[MSP430F5529 LaunchPad 扩展板V2.1/V2.2案例工程](https://github.com/422lab/F5529_EXboard_Example)  
## 特性
* MSP430F5529 LaunchPad直插
* 多种显示屏支持
* LaunchPad全IO引出，标记编号以其复用功能
* 以上功能均可通过跳线帽和排线更改引脚
* 尽可能的硬件SPI支持
## 支持板载资源
* MSP430F5529 LaunchPad
* LCD12864
* 通用的4线I2C显示屏以及7/8线SPI显示屏
* ADS1118 / ADS1256(注意电源)
* DAC8571
* REF3330
* 4 * 4小键盘
## 注意事项
* 基于Kicad 5.1.12，向上Kicad6兼容，但是Kicad6不向下兼容，若后续有意使用Kicad6更新，最好创建一个新分支
* gerber文件请自行生成
* 可能会显示缺少符号库和封装库，已经放在仓库里了，自行重新导入一下