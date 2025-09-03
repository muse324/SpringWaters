# SpringWaters
S.ラフマニノフ作曲の歌曲「春の水」を、ピアノソロとMIDIシステム（Max）で独奏するための
インタラクティブ演奏システムです。

https://youtu.be/pmeRmOh22Ls?si=OTXtofPOo0KybE3J

## 対象楽曲
12 Romances, Op.14 (Rachmaninoff, Sergei)より、第11曲「Spring Waters」
https://imslp.org/wiki/12_Romances,_Op.14_(Rachmaninoff,_Sergei)

## 動作環境
### 必須
- Max8/9 が導入済みで、Max8/9の基本的な操作ができること
- MIDI入出力が可能な電子ピアノを使えること
  - 88鍵フルサイズを想定しています。鍵盤数が少ない場合、一部の機能が動作しません
### オプション（なくても演奏はできます）
- スクリーン＆プロジェクタ
  - スクリーンにパッチや画像を投影したい場合に使用
- webカメラ
  - スクリーンに演奏の様子を投影したい場合に使用

## 起動方法
- 右サイドバーの release 一覧より、ファイル一式をダウンロード（zip または tar.gz）
- zip/tar.gzを展開し、SpringWaters.maxproj をダブルクリック

## 操作
- システム初期化：「r」キー、または 88鍵盤の最低音（A0、いちばん左)
- 演奏開始：　弾け。
  - 参考楽譜：ピアノソロ譜-抜粋.pdfを参照。
  - 開発者本人仕様のアレンジのため、フル楽譜は作成していません。[IMSLP楽譜](https://imslp.org/wiki/12_Romances,_Op.14_(Rachmaninoff,_Sergei))あたりを参照してください
  
- 後半部へジャンプ：A4, A5（オクターブ）を押したまま、ダンパーペダル（右）を踏んで離す
  
### ちょっとしたチュートリアル
[弾き手のためのずぼらな自動伴奏を構築する手法.pdf](弾き手のためのずぼらな自動伴奏を構築する手法.pdf) 
