
## Caption2Ass_PCR_pf

ＴＳファイルから字幕を抽出します。


------------------------------------------------------------------
### 使い方

Run_Caption2Ass_PCR_pf.batのショートカットを作成し、TSファイルをドロップ


### 使い方　　コマンドライン

ファイル  
Caption2Ass_PCR_pf.exe  -i "C:\video.ts"  -format srt  

パイプ  
Caption2Ass_PCR_pf.exe  -pipe  -o "C:\video.ts"  -format srt  



------------------------------------------------------------------
### 追加引数

    -p
    -pipe
パイプからデータを受けとる


    -limit 10.0
ファイル読込み速度を10.0 MiB/secに制限


    -NonCapTag
tsファイルに字幕が含まれてない場合に空のファイル .noncapを作成



------------------------------------------------------------------
### 引数

    -format srt
    -format ass
字幕ファイルの形式  
文字コード　UTF-8 bom  


    -detect_length 300
300×10,000パケットを探索して字幕が見つからなければ終了します。  
およそ３～５分間のデータ量に相当  
-detect_lengthの指定が無いときの初期値は300  


その他の引数はソースコード内の   
"Caption2Ass_PCR_pf\readme history\Caption2Ass_PCR.exe の Readme.txt"  
に記載されています。



------------------------------------------------------------------
### 謝辞
maki/maki_rxrz版のCaption2Ass_PCRを元に作成しました。  
オリジナル及び改良版の開発に関わった方々にお礼申し上げます。  

