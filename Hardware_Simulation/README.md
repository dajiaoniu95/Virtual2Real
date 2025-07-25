# STM32_UART_稳定性优化仿真  
​**技术栈**: Proteus仿真 + Python自动化测试  

## 🎯 项目亮点  
- 发现原代码在115200波特率下丢包率12% → 通过调整时钟树配置降至3%  
- 用Python脚本自动注入200种异常数据（代码见`/Stress_Test`）  

## 🛠️ 如何复现  
1. 安装Proteus 8.9（学生免费版）  
2. 打开`STM32_UART.pdsprj`  
3. 运行`python test_uart.py` 查看日志  

## 📸 效果展示  
![虚拟示波器波形](waveform.png)  
*图：优化前后的波形对比*
