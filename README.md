**APP-LCD-1.8 是一個使用 Arduino UNO 相容介面的擴充板，上面有如下的豐富資源**
1.  一個使用 SST7735 LCD Controller 的 1.8" TFT LCD，RGB 信號使用 565 格式
2.  MCP79411 RTCC
3.  MCP9808A5 - 溫度感測器
4.  KXTJ3 - 3 軸加速度計
5. 蜂鳴器

![image](https://github.com/CalvinHoMicrochip/APP-LCD-1.8-TFT-and-RTCC/assets/20454551/bd8e60d1-f85f-4493-b57f-d4cd97d76b33)
![image](https://github.com/CalvinHoMicrochip/APP-LCD-1.8-TFT-and-RTCC/assets/20454551/5bf582f5-9aea-48e8-8c38-97f0e2bca427)

APP-All MCU 2023 是一個泛用型的實驗板，上面有 3 個預置的 MCU，分別為
-  AVR128DA48
   (https://www.microchip.com/en-us/product/AVR128DA48)
-  dsPIC33CK256MP505
-  PIC32CM2532

AVR128DA48 雖為一個 8 位元的 MCU，但其 24 MIPS 的效能以及豐富的周邊，我們希望透過更多的外部周邊元件的整體運作展示，來讓有興趣的使用者可以藉此評估使用此系列 MCU 的可能性

以下為本範例的 MCC Melody Builder 的內容及 Pin 腳的設定，請下載附件中的 APP-LCD-1.8 線路圖來了解為何定義這樣的接腳安排

![image](https://github.com/CalvinHoMicrochip/APP-LCD-1.8-TFT-and-RTCC/assets/20454551/ae137553-7a51-4cd6-91fb-cc62cc92cd0a)

執行的結果如下 : 

![image](https://github.com/CalvinHoMicrochip/APP-LCD-1.8-TFT-and-RTCC/assets/20454551/dae7b1f6-f2e3-4809-802d-110a138da2a5)

MCC Content Manager 的使用版本如下 :
![image](https://github.com/CalvinHoMicrochip/APP-LCD-1.8-TFT-and-RTCC/assets/20454551/354f3c7f-e1c2-4ea2-8aff-bc1090f8a3b6)

![image](https://github.com/CalvinHoMicrochip/APP-LCD-1.8-TFT-and-RTCC/assets/20454551/34a7a3a6-dbd6-46eb-8a27-1391da4a74b3)



