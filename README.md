# MLX90640-With-STM32
MLX90640 is a fully calibrated 32x24 pixels thermal IR array sensor.

## MLX90640 with STM32 SWI2C 
* SDA_PIN:PB7
* SCL_PIN:PB6

The data will printf on UASRT1 with 115200 buad rate like the blow picture!

![](https://github.com/imliubo/MLX90640-With-STM32/blob/master/image/MLX90640_STM32_HAL_SWI2C.png)

## MLX90640 with STM32 HWI2C 
* SDA_PIN:PB7
* SCL_PIN:PB6
* I2C Clock Speed: 400000Hz
* RefreshRate: <=16Hz (>=32Hz Fail...)

The data will printf on UASRT1 with 115200 buad rate like the blow picture!

![](https://github.com/imliubo/MLX90640-With-STM32/blob/master/image/MLX90640_STM32_HAL_HWI2C.png)
