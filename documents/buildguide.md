# PMW3360ブレイクアウトボードビルドガイド

### 付属しているもの

|名称|数量|備考|
|----|:---:|----|
|PMW3360ブレイクアウトーボード|1個||
|PMW3360DM-T2QU|1個|レンズ付き|
|ステンレスミニアチュアベアリング(3×6×2.5mm)|3個||
|六角ナット(M3 厚さ2.4mm)|3個||
|(+)ナベ頭小ねじ(M3 10mm)|3個||
|トラックボールケース|2個| 	ローマウントとハイマウント1個ずつ|
|M2 6mmスペーサー(ARB-2006E)|3個|丸型両メネジ|
|M2 10mmスペーサー(ARB-2010E)|3個|丸型両メネジ|
|M2 10mmネジ|3本|
  
左：ローマウント  右：ハイマウント  
![001](https://github.com/kushima8/Reex/assets/58157342/8a78b063-16f9-4286-8d3e-3098f63cdd9f)

※以下のPro Microでのみ動作確認済み
　https://shop.yushakobo.jp/products/pro-micro?variant=42225070768359

## PMW3360はんだ付け 

![002](https://github.com/kushima8/Reex/assets/58157342/4637c450-5275-44bb-b1aa-09bb3c98bc29)

左から  ブレイクアウトボード、PMW3360、レンズ  

![003](https://github.com/kushima8/Reex/assets/58157342/f40630b1-ba37-4f84-9b5e-92b727c7bb9a)

ブレイクアウトボードの既にICがはんだ付けされている⾯を表にし、4PINが2列になっている方を左側してください。
センサーチップの⽂字が書かれている⽅を下にして基盤にセットしたあと、裏面からはんだ付けをしてください。

## ケースの作成

ケースは突起のある方が表側、その突起が2つある⽅が上、突起が1つの方が下となります。  
初めに上側のネジ⽳にM2 ネジを⼀つづ⼊れます。  
このM2ネジは使用用途にあわせてご自身でご用意ください。<br>
![007](https://user-images.githubusercontent.com/58157342/234977202-8e4176d8-7a0e-4f62-ad2a-53df21a2acc8.JPG)
その後ベアリングを入れたM3 10mmネジを突起の穴に入れます。  
入れる方向などは下記画像を参考にしてください。  
設置後、六角ナットで固定してください。  
固定する際突起部分とベアリング部分を完全に密着せず若干ながら隙間を作るようにしてください。  
密着しすぎるとベアリングがうまく回らない場合があります。<br>
![007](https://user-images.githubusercontent.com/58157342/234977353-ee923e26-73f6-49c2-a75a-65f784d3f31f.JPG)
ケースを裏返して、M2 10mmネジを画像の三箇所に挿入してください。  
挿入後、M2 6mmスペーサー、M2 10mmスペーサーの順でネジに取り付けます。  
これは玉飛び出し防止用の支柱になります。<br>
![007](https://user-images.githubusercontent.com/58157342/234977419-2490f4e2-41cc-4ec2-8b80-28b67c1d7c68.JPG)
![007](https://user-images.githubusercontent.com/58157342/234977441-af8062cf-d598-4191-a983-1763e4bfcdbd.JPG)
一旦この状態でトラックボールを置き、干渉の確認をしてください。  
ケース本体は3Dプリンタで製造しており、玉と支柱のクリアリングは非常にタイトな設計な為、個体差によっては玉と支柱が干渉する場合があります。  
干渉する場合、支柱取り付けようのネジ穴を棒ヤスリなどで外側へ拡張し、干渉しない用に加工してください。  
下部にトラックボールユニットを取り付ける場合は親指が触れる位置の支柱を取り除くことをオススメします。  