# micropython-lckfbPi
基于最新的 micropython 1.19.1版本编译  梁山派 micropython 固件版本,支持 i2s,i2c 等等,,,

功能支持列表
result：
```c
MicroPython v1.19.1-782-g699477d12-dirty on 2022-12-24; newPi with STM32F429

>>> import machine
>>> dir(machine)
['__class__', '__name__', 'RTC', 'ADC', 'DEEPSLEEP_RESET', 'HARD_RESET', 'I2C', 'I2S', 'PWRON_RESET', 'Pin', 'SOFT_RESET', 'SPI', 'Signal', 'SoftI2C', 'SoftSPI', 'Timer', 'UART', 'WDT', 'WDT_RESET', 'bitstream', 'bootloader', 'deepsleep', 'disable_irq', 'enable_irq', 'freq', 'idle', 'info', 'lightsleep', 'mem16', 'mem32', 'mem8', 'reset', 'reset_cause', 'rng', 'sleep', 'soft_reset', 'time_pulse_us', 'unique_id']
```
