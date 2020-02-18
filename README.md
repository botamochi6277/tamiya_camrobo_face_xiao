# TAMIYA CAMROBO FACE EXTENSION BOARD

An extension board for TAMIYA Cam-Program Robot. 
This board provides Light and Audio Outputs.

## LEDs

- RAW RGB LED: rgbをPWMで制御する古典的なフルカラーLED．制御にLED毎に3ピン必要になる．
- NeoPixel: 国内の流通が最も多いマイコン内蔵フルカラーLED．通信が独自規格であり，pigpioと相性が悪い．
- APA102C(DotStar): SPI通信で制御するマイコン内蔵フルカラーLED．pigpioと相性がよく公式サンプルも用意されている．国内での流通がほとんどない．
[APA102-2020はSparkFunから購入できる](https://www.sparkfun.com/products/14608)が2020サイズであり，手ハンダでの実装が困難．[テープLED](https://homemadegarbage.com/apa102-2020_01)が[Amazon](https://www.amazon.co.jp/APA102-5050-SMD%E9%AB%98%E8%BC%9D%E5%BA%A6%E3%83%81%E3%83%83%E3%83%97LED%E3%83%94%E3%82%AF%E3%82%BB%E3%83%AB%E3%83%95%E3%83%AC%E3%82%AD%E3%82%B7%E3%83%96%E3%83%AB%E3%82%B9%E3%83%88%E3%83%AA%E3%83%83%E3%83%97%E3%83%A9%E3%82%A4%E3%83%88DC-144leds-IP20/dp/B07VGH4XSQ/ref=sr_1_1?__mk_ja_JP=%E3%82%AB%E3%82%BF%E3%82%AB%E3%83%8A&keywords=APA102&qid=1582004545&sr=8-1&th=1)にある．
- SK9822: APA102の廉価版[ここで買えそう](https://ja.aliexpress.com/item/32814778563.html?spm=a2g0o.productlist.0.0.6f33f674jdewf5&algo_pvid=11c10ee4-841f-433c-8d72-16933447e2d9&algo_expid=11c10ee4-841f-433c-8d72-16933447e2d9-5&btsid=c6b56052-cd41-4dc9-95ac-8b8313c795ee&ws_ab_test=searchweb0_0,searchweb201602_3,searchweb201603_53)

## Mounting

- Though Hole: 手ハンダでの実装が用意．KITを想定するならこちら
- Surface Mount: 部品密度を上げることができる．最終的に実装を委託するならこちら．

ひとまず，KITの方向で考える．