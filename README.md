# SparkApp
## 1.画面ごとの機能
アプリを起動すると、「エフェクト」画面となる。画面下部の4つのアイコンで、画面・機能を切り替える。
1. 「エフェクト」：アンプやエフェクターを切り替えて、音作りをする画面。  
2. 「音楽」：「Smart Jam」などで、Youtube動画などを再生し、自動解析したコードが表示されるが、精度が高いわけではないので、使い道は限られる。練習の伴奏にしたいYoutube動画があれば、便利。  
3. 「録画」：演奏動画を録画する画面。  
4. 「メニュー」：LINEアウトのステレオ・モノラル切替や、ギターのPUのハイパワー・ローパワー切替など、各種設定ができる。「Tuner」がとても見やすく、合わせやすい。歯車アイコンから、「トーンプリセットをバックアップする」で、Dropbox に現状のプリセットを一式アップロードできる。  
  
## 2.エフェクトの種類・数
「エフェクト」画面では、エフェクト種別ごとの並び順は固定で、順番は入れ替えられない。  
使わないエフェクトはオフにはできるが、削除はできない。  
アプリ内課金で買わないと使えないエフェクターもある。  
エフェクト種別の並び順と、無償で使える数は以下のとおり。  
  
1. GATE（１種類）：ノイズゲート。
2. COMP/WAH（５種類）：ギター用コンプは３つ。WAHは有償。
3. DRIVE（１０種類）：オーバードライブ、ファズ、ディストーション。
4. AMP（３３種類）：クリーン、クランチ、ハイゲイン、ベース用など７カテゴリあり。
5. MOD/EQ（１２種類）：トレモロ、コーラス、フランジャー、フェイザー、ビブラート、ＥＱなど。
6. DELAY（６種類）：ディレイ、エコー、テープエコーなど。
7. REVERB（９種類）：ルーム、ホール、プレートなど。
  
## 3.[各エフェクトの概要](./EfectsMemo.md)
エフェクト種別ごとのSparkにおける独自性、設定のコツなどについて、[こちら](./EfectsMemo.md)にまとめました。
  
## 4.[全エフェクトの詳細一覧](./EfectsList.md)
エフェクトのアイコンや名前、もとになった実機などについて、[こちら](./EfectsList.md)にまとめました。  
  
## 5.[音作りの手順](./HowToMakePreset.md)
プリセットを自分でつくる手順や注意点について、[こちら](./HowToMakePreset.md)にまとめました。
  
## 6.[バックアップデータの構造](./BackupData.md)
設定画面の右上の、歯車マークから、Dropbox へ、プリセットデータをバックアップすることができる。  
バックアップデータの構造について、[こちら](./BackupData.md)にまとめました。  
データ構造を理解すると、応用的な活用法もみえてくる。  
  
## 7「プリセット・カテゴリ」を活用したプリセット構築のシナリオ
以下のことから、実際にプリセットを構築するシナリオについて、こちらにまとめました。
1. 通常の使い方であれば、「ToneCloudで、１つのプリセットを、共有したりインポートしたりする」か、「Dropboxで、全プリセットを一括で、バックアップしたり復元したりする。バックアップは常に上書きで、世代管理はできない。」となる。
2. Dropbox のバックアップデータを、さらに自分で世代管理したり、カテゴリ単位で入れ替えたりすることで、復元するバックアップを選んだり、特定のカテゴリだけ復元したりできる。
3. 本来の用途は、音色のイメージごとに振り分けるのであろうが、その考え方を離れて、例えば「Bass」にはひな型プリセットばかりを入れる、「Pop」にはライブのセットリストで使うプリセットを入れる、等の使い方もできる。

