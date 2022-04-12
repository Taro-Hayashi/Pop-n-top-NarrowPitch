# ファームウェアを更新する方法

両手側共に同じファームウェアをインストールして使います。  
USB経由でしか更新ができないので、一度TRRSケーブルを外して片手ずつUSBケーブルを繋いで、計2回ファームウェアを更新します。

## Windows以外の場合
キーボードを接続した状態でRemapのファームウェアのページにアクセスしてください。  
- [Pop'n Top NarrowPitch - Remap ](https://remap-keys.app/catalog/1fWEWCmfpZw3S95DBEu1/firmware)

使用するファームウェアのFLASHを選んでください。  
![](img/flash.png)  
Bootloaderをdftに変更します。  
![](img/dfu.png)  
FLASHを押すとダイアログが出てくるのでキーボード裏面のリセットボタンを押してください。 　
![](img/IMG_6713b.jpg)  
出てきたAtm32U4DFUを選択して接続します。  
![](img/connect.png)  
更新が完了したらCLOSEで閉じてください。  
![](img/close.png)  
上手くいかない場合はWindwosの場合と同様にQMK Toolboxを使ってください。  
## Windowsの場合
キーボードを接続した状態でRemapのファームウェアのページにアクセスしてください。  
- [Pop'n Top NarrowPitch - Remap ](https://remap-keys.app/catalog/1fWEWCmfpZw3S95DBEu1/firmware)

使用するファームウェアのDownloadをクリックしてファームウェアをダウンロードしてください。  
![](img/download.png)   
QMK Toolboxのreleaseページから最新版をダウンロードしてインストールください（Betaはおすすめしません）。  
- [Releases・qmk/qmk_toolbox](https://github.com/qmk/qmk_toolbox/releases)

![](img/release.png)  
起動したらOpenを押してダウンロードしたファームウェアを指定し、キーボード裏面のリセットボタンを押します。  
![](img/qmktoolbox1.png)   
新しく黄色の文字が出てきたらFlashを押します。  
![](img/qmktoolbox2.png)  

Thank youの後に黄色い文字が出たら更新完了です。  
![](img/qmktoolbox3.png)   

ブラウザの機能で戻ってください。  
