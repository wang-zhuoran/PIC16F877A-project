# PIC16F877A-project - LCD 轮播显示
  
  - Platform: PIC DIP-40
  - Compiler: XC8
  - IDE: MPLAB X IDE v5.50

### 主要实现功能
  - 利用I2C将“Ready”信息写入EEPROM，再由UART将EEPROM中信息发送至PC端
  - 利用ADC将光敏电阻两端电压转变为discrete value
