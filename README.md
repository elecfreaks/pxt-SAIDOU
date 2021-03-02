![](https://img.shields.io/badge/Plantfrom-Micro%3Abit-red) ![](https://img.shields.io/travis/com/elecfreaks/pxt-SAIDOU) ![](https://img.shields.io/github/v/release/elecfreaks/pxt-SAIDOU) ![](https://img.shields.io/github/last-commit/elecfreaks/pxt-SAIDOU) ![](https://img.shields.io/github/languages/top/elecfreaks/pxt-SAIDOU) ![](https://img.shields.io/github/issues/elecfreaks/pxt-SAIDOU) ![](https://img.shields.io/github/license/elecfreaks/pxt-SAIDOU) 

# 赛豆 SAIDOU Package

![](/SAIDOU.png/)

赛豆，micro:bit智能硬件竞赛套装，西瓜创客&恩孚科技联合推出。

SAIDOU micro:bit intelligent hardware competition package, Jointly produced by SAIDOU and ELECFREAKS.

你可以访问 [赛豆官网](https://www.saidou42.com)，获取硬件套装和更多赛事信息

You can visit [SAIDOU](https://www.saidou42.com) For hardware packages and more.

## Code Example
```JavaScript

input.onButtonPressed(Button.A, function () {
    neZha.setMotorSpeed(neZha.MotorList.M1, 100)
    neZha.setMotorSpeed(neZha.MotorList.M2, 100)
    neZha.setMotorSpeed(neZha.MotorList.M3, 100)
    neZha.setMotorSpeed(neZha.MotorList.M4, 100)
})
input.onButtonPressed(Button.B, function () {
    neZha.setServoAngel(neZha.ServoList.S1, 119)
    neZha.setServoSpeed(neZha.ServoList.S2, -58)
})
input.onButtonPressed(Button.AB, function () {
    neZha.stopAllMotor()
})
basic.forever(function () {
	
})

```
## Supported targets

* for PXT/microbit

## License
MIT

