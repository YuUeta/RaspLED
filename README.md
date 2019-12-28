# RaspLED
Raspberry pi3 を使用したデバイスドライバの作成
## 作成したドライバについて
### 使用方法
```
sudo make
sudo insmod myled.ko
sudo chmod 666 /dev/myled0
echo [コマンド] > /dev/myled0
```
### コマンドの種類及び動作
+ 1 : 1つ目のLEDが点灯する
+ 2 : 0.3秒の速度でLEDが赤→黄→緑→青→赤の順番で10回点灯後すべてののLEDが点灯する
+ 3 : 0.3秒の速度でLEDが青→緑→黄→赤→青の順番で10回点灯後すべてののLEDが点灯する
+ 4 : すべてのLEDを消す
+ 5 : すべてのLEDを消す

## 動画URL
作成したデバイスドライバの動作動画  
https://youtu.be/7xPbnW0739Q
