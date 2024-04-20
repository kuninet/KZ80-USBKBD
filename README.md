# KZ80マイコン用 MSX USBキーボードアダプタ # 

## 概要 ##
* USBキーボードをRaspberry PI PICOにつなぎ、MSX互換のPPI(8255)へつなげるボードです。
  * HRA!氏のusb_keyboard_bridge_for_msxを使わせていただいています。

## 回路図

* [回路図(PDF)](https://github.com/kuninet/KZ80-USBKBD/blob/main/KiCAD/KZ80-USBKBD.pdf)

## 注意

* KiCADデータは [KiCAD](KiCAD)ディレクトリに入ってます。KiCad6を使用しています。KiCad v5以前では開けません。
* 基板製造データは[KiCAD/PCB](KiCAD/PCB)に入っています。
* ファームウェアの書き込みにはコツがいりますので、こちらのBLOG記事を参考にしてください。
  * [KZ80-USBKBD用 RaspberryPi Picoオブジェクトビルド方法](https://kuninet.org/2023/03/30/kz80-usbkbd%e7%94%a8-raspberrypi-pico%e3%82%aa%e3%83%96%e3%82%b8%e3%82%a7%e3%82%af%e3%83%88%e3%83%93%e3%83%ab%e3%83%89%e6%96%b9%e6%b3%95/)

## ライセンスについて
* 私が作成した回路についてはMITライセンスで公開します。

## 参考・使用させていただいた情報
* usb_keyboard_bridge_for_msx
  * https://github.com/hra1129/msx_tools/tree/main/usb_keyboard_bridge_for_msx
* Raspberry Pi Pico シンボル&フットプリント
  * https://datasheets.raspberrypi.org/rp2040/VGA-KiCAD.zip
