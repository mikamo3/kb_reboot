## 事象

Bootボタンを押しながらリセットしないと起動しない。つまり書き込んだuf2が起動しない。

## 参考



https://github.com/74th/rp2040-dev-board/tree/main

https://www.waveshare.com/w/upload/d/d1/RP2040_Plus.pdf

https://github.com/tjhorner/bizcard
## crystalについて

使っているのは
https://jlcpcb.com/partdetail/Yxc_CrystalOscillators-X322512MSB4SI/C9002

loadcapacitanceは10pF?

コンデンサは33p
参考にしているやつは30pのせてる

ロードキャパシタンス

runがpullupしていないのが怪しい
つけておく

CC1,CC2の抵抗周り

USB D+は30でもいいみたい,22でもいけるか？やめておいたほうがよさそう

Flash
