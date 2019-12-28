# RaspLED
Raspberry pi3 を使用したデバイスドライバの作成
## 作成したドライバについて
### 使用方法
```
sudo make
sudo insmod myled.ko
echo [コマンド] > /dev/myled0
```
### コマンド
+ 1 : 1つ目のLEDのみを点灯する
+ 2 : 2つ目のLEDのみを点灯する
+ 3 : 3つ目のLEDのみを点灯する
+ 4 : すべてのLEDを間欠点灯する
+ 5 : すべてのLEDを消す

## 動画URL
作成したデバイスドライバの動作動画  
https://youtu.be/Zni6cFDGlNU
