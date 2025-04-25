# Zebra-Printer_Supported Development Design and Embeded Tools

<img src="https://cdn.pixabay.com/photo/2019/10/09/07/28/development-4536630_1280.png">

<br>

開発者向けにゼブラプリンタがサポートしているプリンタ言語、開発ツール、パッケージソフト一覧を紹介。

<br>

## プリンタ言語
プリンタが受信可能な印刷・設定言語の対応表。

| \-    | SGD | ZPL | CPCL | ESC-POS |
| :-----: | :---: | :---: | :----: | :-------: |
| ZT600 | x   | x   |      |         |
| ZT500 | x   | x   |      |         |
| ZT400 | x   | x   |      |         |
| ZT200 | x   | x   |      |         |
| ZD600 | x   | x   |      |         |
| ZD400 | x   | x   |      |         |
| ZD200 | x   | x   |      |         |
| ZQ600 | x   | x   | x    |         |
| ZQ500 | x   | x   | x    |         |
| ZQ300 | x   | x   | x    |         |
| ZQ200 | x   |     | x    | x       |

### 
[ZPL II, ZBI 2, Set-Get-Do, Mirror, WML Programming Guide](https://docs.zebra.com/us/en/printers/software/zpl-pg/zpl-ii,-zbi-2,-set-get-do,-mirror,-wml-programming-guide.html)

<br>

## 開発ツール
プリンタ向けソフトウェアを開発する際の開発ツール対応表。

| \-    | Link-OS Multi-Platform<br>SDK | Print Connect | Browser Print | ZQ220+<br>SDK |
| :-----: | :--------------------------: | :-------------: | :-------------: | :----------: |
| ZT600 | x                          | x             | x             |            |
| ZT500 | x                          | x             | x             |            |
| ZT400 | x                          | x             | x             |            |
| ZT200 | x                          | x             | x             |            |
| ZD600 | x                          | x             | x             |            |
| ZD400 | x                          | x             | x             |            |
| ZD200 | x                          | x             | x             |            |
| ZQ600 | x                          | x             | x             |            |
| ZQ500 | x                          | x             | x             |            |
| ZQ300 | x                          | x             | x             |            |
| ZQ200 |                            |               |               | x          |

<br>

### 参考資料
[Dev Portal - Printers](https://developer.zebra.com/products/printers)

<br>

## パッケージソフト（印刷、デザイン）
プリンタのラベルデザインや印刷が可能なパッケージソフト対応表。

| \-    | Zebra Designer 3 <br>Essential | Zebra Designer 3 <br>Professional | Zebra Designer 3 <br>Developer |
| :-----: | :--------------------------: | :-----------------------------: | :--------------------------: |
| ZT600 | x                          | x                             | x                          |
| ZT500 | x                          | x                             | x                          |
| ZT400 | x                          | x                             | x                          |
| ZT200 | x                          | x                             | x                          |
| ZD600 | x                          | x                             | x                          |
| ZD400 | x                          | x                             | x                          |
| ZD200 | x                          | x                             | x                          |
| ZQ600 | x                          | x                             | x                          |
| ZQ500 | x                          | x                             | x                          |
| ZQ300 | x                          | x                             | x                          |
| ZQ200 |                            |                               |                            |


### 参考資料
[ZebraDesigner 3 ソフトウェアサポート](https://www.zebra.com/jp/ja/support-downloads/software/printer-software/zebra-designer-3-downloads.html)

<br>


## Embeded
プリンタ内に組み込み可能なプログラム対応表。

| \-    | ZBI 2.0<br>組み込みプログラム | WML<br>液晶画面カスタム | CAG<br>液晶カスタム |
| :-----: | :--------------------: | :---------------: | :-------------: |
| ZT600 | x                    |                 | x             |
| ZT500 | x                    |                 |               |
| ZT400 | x                    |                 | x             |
| ZT200 | x                    |                 | x             |
| ZD600 | x                    |                 | x             |
| ZD400 | x                    |                 |               |
| ZD200 | x                    |                 |               |
| ZQ600 | x                    | x               |               |
| ZQ500 | x                    | x               |               |
| ZQ300 | x                    |                 |               |
| ZQ200 |                      |                 |               |

### 参考資料
[Zebra Basic Interpreter (ZBI) 2.0](https://developer.zebra.com/content/Zebra-Basic-Interpreter-2)  
[Wireless Markup Language (WML)](https://docs.zebra.com/us/en/printers/software/zpl-pg/wireless-markup-language-(wml).html)
