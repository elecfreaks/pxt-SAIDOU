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
    WuKong.setAllMotor(100, -100)
})
input.onButtonPressed(Button.AB, function () {
    WuKong.stopAllMotor()
})
input.onButtonPressed(Button.B, function () {
    WuKong.setServoAngel(wuKong.ServoList.S0, 360)
    WuKong.setServoAngel(wuKong.ServoList.S2, 180)
    WuKong.setServoAngel(wuKong.ServoList.S4, 90)
    WuKong.setServoAngel(wuKong.ServoList.S6, 0)
})
basic.showIcon(IconNames.Heart)
WuKong.setLightMode(wuKong.LightMode.BREATH)
Octopus.buttonEvent(DigitalPin.P1, Octopus.ButtonType.down, function () {
    Octopus.showUserText(1, "Hello, SaiDou.")
})

```
## Supported targets

* for PXT/microbit

## License
MIT

