# TAMIYA CAMROBO FACE EXTENSION BOARD

An extension board for TAMIYA Cam-Program Robot. 
This board provides Light and Audio Outputs.

## LEDs

- RAW RGB LED: rgbをPWMで制御する古典的なフルカラーLED．制御にLED毎に3ピン必要になる．
- NeoPixel: 国内の流通が最も多いマイコン内蔵フルカラーLED．通信が独自規格であり，pigpioと相性が悪い．
- APA102C(DotStar): SPI通信で制御するマイコン内蔵フルカラーLED．pigpioと相性がよく公式サンプルも用意されている．国内での流通がほとんどない．
[APA102-2020はSparkFunから購入できる](https://www.sparkfun.com/products/14608)が2020サイズであり，手ハンダでの実装が困難．
- SK9822: APA102の廉価版[ここで買えそう](https://ja.aliexpress.com/item/32814778563.html?spm=a2g0o.productlist.0.0.6f33f674jdewf5&algo_pvid=11c10ee4-841f-433c-8d72-16933447e2d9&algo_expid=11c10ee4-841f-433c-8d72-16933447e2d9-5&btsid=c6b56052-cd41-4dc9-95ac-8b8313c795ee&ws_ab_test=searchweb0_0,searchweb201602_3,searchweb201603_53)

## Mounting

- Though Hole: 手ハンダでの実装が用意．KITを想定するならこちら
- Surface Mount: 部品密度を上げることができる．最終的に実装を委託するならこちら．