# SparkApp
## 1.画面ごとの機能
アプリを起動すると、「エフェクト」画面となる。画面下部の4つのアイコンで、画面・機能を切り替える。
1. 「エフェクト」：アンプやエフェクターを切り替えて、音作りをする画面。  
2. 「音楽」：「Smart Jam」などで、Youtube動画などを再生し、自動解析したコードが表示される。精度が高いわけではないので、使い道は限られる。  
3. 「録画」：演奏動画を録画する画面。  
4. 「メニュー」：各種設定など。「Tuner」がとても見やすく、合わせやすい。歯車アイコンから、「トーンプリセットをバックアップする」で、Dropbox に現状のプリセットを一式アップロードできる。  
  
## 2.エフェクトの種類・数
「エフェクト」画面では、エフェクト種別ごとの並び順は固定で、順番は入れ替えられない。  
使わないエフェクトはオフにはできるが、削除はできない。  
アプリ内課金で買わないと使えないエフェクターもある。  
エフェクト種別の並び順と、無償で使える数は以下のとおり。  
  
1. GATE（１種類）
2. COMP/WAH（５種類）
3. DRIVE（１０種類）
4. AMP（３３種類）
5. MOD/EQ（１２種類）
6. DELAY（６種類）
7. REVERB（９種類）
  
## 3.エフェクトの詳細一覧
エフェクトの詳細な一覧は、[こちら。](./EFECTS.md)  
  
## 4.音作りの手順
1. 流れとしては、「AMPを選ぶ」「DRIVEを選ぶ」「REVERBを選ぶ」、「COMPを選ぶ」、必要に応じてほかのエフェクトを選ぶ、が基本となる。「AMP」モデルのツマミは共通で、実機アンプのような「チャンネル切替」や「リバーブ」などは一切ないので、AMPで大まかな歪み量・方向性を決めたあとは、すべてエフェクターで音作りすることになる。
2. まず、基本となるプリセットを作る。各エフェクトで、とりあえず好みのものを選択したうえで、AMPだけをONにして、他をOFFにする。
3. 「AMP」を決めるにあたっては、もとになったモデルを参考に、音を確認して決めていく。
4. 「AMP」の設定は、Gain とVolume で音を作るが、ツマミはすべて12時から始めるとよい。ゲイン抑え目、ゲイン１２時、ゲイン上げ目、の３通りぐらいオーディションするとよい。主にはGain で歪み量・音の方向性が決まるが、Volume でも変わる。最終的な音量は、Spark 本体のボリュームツマミで調節できるが、ほかのプリセットと音量を揃えるため、Spark本体のボリュームツマミを回して、アプリ上のボリュームメーターが中央になるぐらいで固定すると、現場での音量調整を本体ボリュームでできる余地になる。また、ギター本体のボリュームは１０ではなく、６～８ぐらいでしたほうが、ギター本体のボリュームで歪み量を微調整する余地を持った設定にaできる。
5. 可能であればスタジオでミキサーにつなぐなどして大音量を出して、低音がつぶれたらBassをカット、高音がキンキンすればTrebleをカットするなど、音が心地よくクリアに聴こえるように調節する。
6. 以上の調整を、いくつかのアンプモデルにおいてやっておき、各アンプの設定ひな型として残しておくとよい。
7. 「Drive」をONにして、歪み量や音量を調節する。ツマミをすべて１２時にして、Gainを「０、９時、１２時、１５時、フルテン」など試す。Gain量が決まったら、On／Offで音量が大きく変わらないように、Levelを調節する。ここで「AMP」やSpark 本体のボリュームツマミで調節してしまうと、ほかのプリセットとのバランスが悪くなるので注意。
8. REVERBをONにして、残響音を調整する。ROOM、HALL、PLATEがある。（SPRINGは無い？）
9. 「COMP」をONにして、バランスをみる。１２時から、１０時や１４時を試してみる。一度OFFにしてみて、ONにしたときとの違いを確認する。
10. 必要に応じて、他のエフェクトをONにして調整する。「MOD」は、ごくうっすらと掛けると、音に奥行きが出る。
11. ある程度、設定が固まったら、そのプリセットをひな型にする。別のAMPやDRIVEを試すなど設定を変更したら、「上書き」ではなく、「新規保存」すると、別名保存できて、ひとつひとつの設定を初期値から変更する手間が省ける。
  
## 5.AMPの概要
1. AMP のモデルは、０１～３９の３９種類あるが、うち６種類は有償なので、実質は３３種類。  
2. 有償なのは、（０６、０７、１３、１４、１９、２０）の６種類。  
3. 設定つまみは、全モデル共通で、「Gain、Bass、Middle、Treble、Volume」の５つ。
4. アンプのキャラクターのカテゴリーとして、「Clean」「Glassy」「Crunch」「High Gain」「Metal」「Acoustic」「Bass」の７種類ある。３３種類を網羅的に試さなくても、「参照モデル」や「カテゴリー」から、試すアンプを絞ると効率がよい。
  
## 6.REVERBの概要
1. REVERB のモデルは０１～０９の９種類。ROOM、HALL、PLATE。SPRINGは無い？
2. 設定つまみは、全モデル共通で、「LEVEL、DAMPING、DWELL、TIME、LOW CUT、HIGH CUT」の６つ。
3. 「LEVEL」は、残響音の音量。
4. 「DAMPING」は、残響音が吸収される周波数。空間に人などがいる場合の響き方。
5. 「DWELL」は、減衰の長さ。
6. 「TIME」とは、残響音の長さ。

## 7.NOISE GATE の概要

## 8.COMP/WAH の概要
音がはっきり、芯が太くなるので、必要に応じてONにする。  
## 9.MOD/EQ の概要
トレモロ、フランジャー、フェイザー、ビブラートなど、かなり音が変わるので、必要に応じてONにする。  
ごくごく弱く掛けてもよい。  
  
## 10.DELAY の概要
もとになったモデルがある程度わかっているので、[詳細一覧表](./EFECTS.md)を参考に、設定する。


