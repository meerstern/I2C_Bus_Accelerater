# I2Cバスアクセラレータ
I2C(Grove) adapter with a bus accelerater IC, LTC4311

## 概要 
  * 本基板は[LTC4311][1]を使用したI2C通信の信号波形を改善するバスアクセラレータです  
  * I2Cケーブルを延長する場合や多数デバイスを接続する場合に通信を安定させます  
  * 400pFのI2C仕様を大きく上回るバス負荷条件においてデータ伝送速度と信頼性を向上させます  
  * 最大400kHz動作です  
  * 電源範囲は1.6V～5.5Vです  
  * I2Cバスラインに挿入して使用します  
  * Grove互換コネクタを搭載しており、既存のデバイスに容易に接続できます  
  * 基板サイズ20mm x20mm、固定穴M3x4 幅15mm

## 注意
  * I2C信号によっては改善できない場合があります    
  * 本基板のGrove互換コネクタは2つとも共通です  
  * デバイス側/マイコン側の区別はないため、どちらに接続しても構いません 
  * I2Cハブ等で分岐して使用する場合は片側のみの接続でも構いません  
  * 本基板は目安として数m~10m程度までの延長に向いています  
  * 数10m以上延長する場合は高ドライブ電流バスバッファPCA9600D等が最適です  
   
## 販売サイト
  * [スイッチサイエンス][2] 
  
<img src="https://raw.githubusercontent.com/meerstern/I2C_Bus_Accelerator/master/IMG/img1.jpg" width="360">  
<img src="https://raw.githubusercontent.com/meerstern/I2C_Bus_Accelerator/master/IMG/img2.jpg" width="360">  
   
   
 [1]: https://www.analog.com/jp/products/ltc4311.html "*1"
 [2]: https://www.switch-science.com/products/7560
