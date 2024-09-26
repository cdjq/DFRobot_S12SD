DFRobot_LTR390UV
===========================

* [中文版](./README_CN.md)

SKU：SEN0636

![产品效果图片](../../resources/images/SEN0540.png)
  
## Product Link (https://www.dfrobot.com)
    SKU: SEN0540

## Table of Contents

  * [Summary](#summary)
  * [Installation](#installation)
  * [Methods](#methods)
  * [Compatibility](#compatibility)
  * [History](#history)
  * [Credits](#credits)

## Summary

A sensor that reads the intensity of ultraviolet light.

## Installation

To use this library, first download the library file, paste it into the \Arduino\libraries directory, then open the examples folder and run the demo in the folder.

## Methods

```C++
  /**
   * @fn begin
   * @brief Init s12sd device
   * @return Return value init status
   * @retval 0  Succeed
   * @retval -1 Failed
   */
  int8_t begin(void);

  /**
   * @fn readUvValue
   * @brief Read the UV voltage value
   * @return voltage value (mV)
   */
  uint16_t readUvValue(void);

  /**
   * @fn readUvIndex
   * @brief Read the UV Index
   * @return UV Index
   */
  uint16_t readUvIndex(void);

  /**
   * @fn readUvClass
   * @brief Read the risk level
   * @return 0-4 (Low Risk,Moderate Risk,High Risk,Very High Risk,Extreme Risk)
   */
  uint16_t readRiskLevel(void);

```

## Compatibility

MCU                | SoftwareSerial | HardwareSerial |      IIC      |
------------------ | :----------: | :----------: | :----------: | 
Arduino Uno        |      √       |      X       |      √       |
Mega2560           |      √       |      √       |      √       |
Leonardo           |      √       |      √       |      √       |
ESP32              |      X       |      √       |      √       |
ESP8266            |      √       |      X       |      √       |
micro:bit          |      X       |      X       |      √       |
FireBeetle M0      |      X       |      √       |      √       |
Raspberry Pi       |      X       |      √       |      √       |

## History

- 2022-06-30 - Version 1.0.0 released.

## Credits

Written by TangJie(jie.tang@dfrobot.com), 2021. (Welcome to our [website](https://www.dfrobot.com/))
