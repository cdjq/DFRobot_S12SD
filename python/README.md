DFRobot_LTR390UV
===========================

- [中文版](./README_CN.md)

A sensor that reads the intensity of ultraviolet light.

![产品效果图](../../resources/images/SEN0540.png)

## Product Link (https://www.dfrobot.com)

    SKU：SEN0540

## Table of Contents

  * [summary](#summary)
  * [installation](#installation)
  * [methods](#methods)
  * [compatibility](#compatibility)
  * [history](#history)
  * [credits](#credits)

## Summary

A sensor that reads the intensity of ultraviolet light.


## Installation

Download this library to Raspberry Pi before use, then open the routine folder. Type python demox.py on the command line to execute a routine demox.py. For example, to execute the read_data.py routine, you need to enter:

```python
python read_data.py
```

## Methods

```python
  def read_UV_data(self)
    '''!
      @brief Read the UV voltage value
      @return voltage value (mV)
    '''

  def read_UV_index(self)
    '''!
      @brief Read the UV Index
      @return UV Index
    '''

  def read_risk_level(self)
    '''!
      @brief Read the risk level
      @return 0-4 (Low Risk,Moderate Risk,High Risk,Very High Risk,Extreme Risk)
    '''
```

## Compatibility

* RaspberryPi Version

| Board        | Work Well | Work Wrong | Untested | Remarks |
| ------------ | :-------: | :--------: | :------: | ------- |
| Raspberry Pi2 |           |            |    √     |         |
| Raspberry Pi3 |           |            |    √     |         |
| Raspberry Pi4 |       √   |            |          |         |

* Python Version

| Python  | Work Well | Work Wrong | Untested | Remarks |
| ------- | :-------: | :--------: | :------: | ------- |
| Python2 |     √     |            |          |         |
| Python3 |     √     |            |          |         |

## History

- 2022-06-30 - Version 1.0.0 released.

## Credits

Written by TangJie(jie.tang@dfrobot.com), 2021. (Welcome to our [website](https://www.dfrobot.com/))
