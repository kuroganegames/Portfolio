# Portfolio

鐵火卷(クロガネ ヒマキ)のやったこと等です。 





## SNS

主にtwitterを運用しています。

twitter: https://twitter.com/Kurogane_8_Gk (旧アカウントはいくつかありますが、現在はこちらのみ運用しています。)

instagram: https://www.instagram.com/kuroganegk/



## ツール制作

### PSDファイルをwaifu2xにかけるスクリプトの制作

通常、PSDファイルを拡大する場合、元の解像度依存でぼやけてしまう問題があります。一枚絵(png, jpgファイル)の場合、waifu2xなどの機械学習を用いた超解像ツールを用いるという解決策があります。しかし、PSDファイルの場合、PSDファイルを生成することの難しさから、このような超解像ツールに入れる場合、各レイヤーを一度画像として出力し、再構成する必要があります。このスクリプトはgimp内のpythonスクリプトとして動き、PSDファイルのレイヤーを分割、waifu2xにかけ、再構築します。

[【waifu2x】立ち絵などのpsdファイルを半自動で拡大するツールを作ってみた - ニコニコ動画 (nicovideo.jp)](https://www.nicovideo.jp/watch/sm35618128)



### 配信用ツール(最低限文化的な配信用アバター(MCLA))

![mcla_scheme](https://user-images.githubusercontent.com/37547447/177958049-bd729599-1f44-4db8-ae7a-99b69016e2e8.png)

[kuroganegames/mcla_proto: easy live avatar (github.com)](https://github.com/kuroganegames/mcla_proto)
https://kurogane-gk.booth.pm/items/1853708

マイク入力を取得し、pygameの描画を切り替えることで、口パクアニメーション、自動瞬きをさせることが出来る簡易的な配信補助ツールです。

同時期に公開された「だれでもvtuber」と同等ですが、pythonで記述しているため、拡張性があります。

内部プログラムをopencvに変更変更したり、顔認識プログラムと連携することで表情に合わせて立ち絵を切り替えるなどの活用方法もあります。



### 動画制作補助ツール

#### YMM4を用いた動画制作の半自動化

以下の動画チャンネル様の動画制作補助ツールを制作しています。

動画制作時間の短縮に貢献しています。

[(5) S-1将棋ライフ shogi life - YouTube](https://www.youtube.com/channel/UCETi9J2H4BOKqK8Av2MDDmg)

現在、継続中。



#### ニコニコ動画の広告欄のスクレイピング

![scraping_ad](https://user-images.githubusercontent.com/37547447/177958044-7ccf9810-4b3d-4cdb-8b53-7288ce93da8e.png)

https://www.nicovideo.jp/watch/sm36575503

ツールは公開。seleniumを用いたスクレイピングとffmpegを組み合わせたツールを制作していました。



#### ffmpegを用いた動画の自動生成

![ffmpeg_pptx](https://user-images.githubusercontent.com/37547447/177958038-7cc6ad0c-0c41-487f-b63d-762d143949ac.png)

https://www.nicovideo.jp/watch/sm35405123

ツールは公開。powerpointファイルを処理し、ffmpegでスライドショーの表示、字幕の自動生成、読み上げ結果の埋め込みを行うツール。

#### 口頭で会話できるボットの制作

![ai_bot](https://user-images.githubusercontent.com/37547447/177958032-6e3d632e-ef05-42b9-bdab-7108c4cc60d2.png)

https://www.youtube.com/watch?v=90ynZiTDQDo

ツールは非公開。音声認識apiと自然対話apiと合成音声ソフトを活用することで、口頭で会話することが出来るボットを作成しました。SeikaCenter(廃盤)経由でVoiceroid2に発話させます。また、前述のMCLAと連携させることで、発話時に動くアバターも簡単に用意出来ます。



## 翻訳

### vagante

[Vagante日本語化 - Vagante 攻略 JP @ ウィキ - atwiki（アットウィキ）](https://w.atwiki.jp/vagante_jp/pages/46.html)

ローグライクゲーム「vagante」の**非公式日本語翻訳の補助**を行いました。

主に翻訳方法の調査、DeepL APIを使用した翻訳の下書きの作成、翻訳者への翻訳方法の提案・伝達、各翻訳者の翻訳結果をまとめるツールの作成などを行いました。


### vseeface

https://www.vseeface.icu

一部の**翻訳を補助**しました。

ツール内に名前の記載があります。





## 創作活動

### アバター作成

#### vroid studioを使用

![avatar](https://user-images.githubusercontent.com/37547447/177962028-0b57d1de-c52c-48de-b49d-734299a7b61d.jpg)

vroid studioを用いてアバターを制作しています。
顔や肌のテクスチャ、簡易な衣装は自分で描いています。


#### 変換など

アバターをVRChatに変換したり、MMD用に変換することが出来ます。



### 動画制作

### 配信

稀に配信をしています。
ニコ生: https://com.nicovideo.jp/community/co3995938
twitch: https://www.twitch.tv/kurogane_games

配信用の素材などは自作しています。



#### 動画(休止中)

現在休止していますが、簡単な動画を制作しています。

ニコニコ動画: https://www.nicovideo.jp/user/16029344

youtube: https://www.youtube.com/channel/UCpixZHX8KYRwnNhIKFt7lIg



### ブログ運営(休止中)

https://gkalumnium.com/

wordpressです。主に自分の技術メモなどを書いていました。
ピーク時は1か月の累計PV数は約6500でした。

現状、更新は停止しています。



### お絵描き(休止中)

大昔に一時的に書いていました。

[鐵 火卷 - pixiv](https://www.pixiv.net/users/564438)

現状、更新は停止しています。



## その他活動

### PUBG

#### スクリム出場経験(休止中)

アマチュアも参加することが出来るスクリムに、グループ「まきちゃんず」を立ち上げ、出場した経験があります。

#### カスタム戦績

PUBG DONCUP SOLO #33 FPP Erangel 7/61

ぬかりんぴっく 二つ名アリ ドン勝19回

ちゃんぬっけろいカスタム 優勝



### カービィのエアライド

カービィのエアライドのシティトライアルにおけるアイテム収集のスコアアタックで、13位相当の結果です。「**ゲームスピード：ふつう**」部門で実施したため、ランキングへの記載はありません。

[スコアアタック - カービィのエアライド＠走法まとめWiki (fc2.com)](https://airride.wiki.fc2.com/wiki/スコアアタック)

実際の動画

[【144/160】 琴葉葵の独り言エアライド #01【VOICEROID実況プレイ】 - ニコニコ動画 (nicovideo.jp)](https://www.nicovideo.jp/watch/sm36819928)

[[140/160\]シティトライアル個人的攻略法を広める動画 - ニコニコ動画 (nicovideo.jp)](https://www.nicovideo.jp/watch/sm33641639)
