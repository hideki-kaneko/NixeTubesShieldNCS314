# ダイバージェンスメーター　日本用カスタムファームウェア

## 説明
ニキシー管時計NSC314（HW2.0～2.2）用のカスタムファームウェアです。オリジナル版との相違は以下の通りです。

- 音楽「Gate of steiner」を追加、デフォルトの曲をこれに変更
- 日付フォーマットを日本式YY:MM:DDに変更（日付のモード切り替えを利用してください）
- 消灯機能追加（down ボタン長押しでニキシー管の点灯切替可能　アラームをセットすると、時間になったら点灯します）
- LED関連のボタン変更（up ボタン長押しでON/OFF切り替え　その他は同じ）

# Nixe Tubes Shield NCS314 and NCS312
Sketch for Arduino UNO and Nixie Tubes Shield NCS314 and NCS312 by GRA &amp; AFCH
1. This repository content sources of project for Nixie Clock developed by GRA & AFCH.

	Folders description:
  
	FIRMWARES - source code that must be complied in Arduino IDE, and allready compiled Binary files in *.hex format ready to be uploaded on to property board by flasher.
  
	GRA & AFCH Compiled Firmware Flasher - flasher (uploader) that must be used in prevois step.
  
	LIBRARIES - Arduino libraries without which compiling will be failed. That folders must be copied to Arduino LIBRARIES folder, (default path: C:\Users\USER_NAME\Documents\Arduino\libraries)
  
	SCHEMES - electrical shemes for boards: for Nixie Clock Main Units - MCU, and for Nixie Tubes Boards
  
	USB DRIVERS - drivers for USB-to-SERIAL(UART) converters
  
	USER MANUAL - end user's manuals.

2. Link to YouTube video with preparing, compiling and uploading firmware to clock:
https://youtu.be/DQZWPn0iAHw

3. Compatibility:

	Nixie Clock Shield for Arduino - <b>NCS314</b> (Hardware Versions: HW1.0, HW1.1, HW1.2, HW2.0, HW2.2) <br>
	Nixie Clock Shield for Arduino - <b>NCS312</b> (Hardware Versions: HW1.0 - HW1.3) - use the firmware for NCS314 version 2.0
	
3. eBay stores:
First (gra_and_afch) - https://www.ebay.com/sch/gra_and_afch/m.html?_nkw=&_armrs=1 <br>
Second (gra_and_afch_2) - http://stores.ebay.com/graandafch2/

4. Our own on-line store: http://gra-afch.com

5. E-mail: fominalec@gra-afch.com
