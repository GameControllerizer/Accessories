[GameControllerizer](https://github.com/GameControllerizer)の開発過程において生まれた副産物の紹介です．

---
# Voltage regulation board for LiPo battery

LiPoバッテリー（3.7V, JSTPH 2pin）からmicro:bitやブレッドボードに3.3V電源を供給するための電圧変換基板です．
ソルダジャンパを設定することでケーブルの正負が逆になっているLiPoバッテリーにも対応できます．
**[SwitchScienceにて委託販売中です](https://www.switch-science.com/catalog/8038/)．**

## Board

<img src=./images/board_01.jpg width="480">
<img src=./images/board_00.png width="480">

## Spec

- Size : 11.4 x 25.4 mm
- Input voltage (max) : 6.0V
- Output current (max) : 500mA
- Output voltage : 3.3V
- Input connector : JST PH 2pin
- Output connector : 2.54mm pitch, through hole
- Schematics : [hsb-vrb-v1_schematics.pdf](./resources/hsb-vrb-v1_schematics.pdf)

※昇圧機能を有していないため，バッテリー残量が少なくなった場合に出力が3.3Vを下回ることがあります．

## Usage examples

#### 1. for micro:bit

<img src=./images/for_microbit.jpg width="480">

#### 2. for breadboard

<img src=./images/for_breadboard.jpg width="480">

## Solder jmper setting

LiPoバッテリーのケーブル正負に応じて，ソルダジャンパを以下のように設定します．

<img src=./images/solder_jumper_setting.png width="420">

## Notice

- 本製品は開発者向けの製品となっています．本ページの技術情報を読んでいただいた上でご自身の責任でご使用下さい．技術サポートは致しかねます．
- 本製品を使用して発生した直接的・間接的な損害に対するその種類，規模を問わず補償は致しかねます．
- 返品，キャンセル，返金等については各委託販売会社の規則に準じます．
- 未実装の初期不良品交換のみ対応いたします（到着後2週間以内）．それ以外の部品実装後の交換・故障またはその原因追及は致しかねます．
- 購入される方は，上記をご理解いただいたものとさせていただきます．
- 連絡先 : gamecontrollerizer(at)gmail.com
