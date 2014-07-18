# 目次  

## [第0回 顔合わせと実力テスト](#section0)  
## [第1回 Topic 1 - P35 〜 61 Standard Deviation](#section1)  
* [DOTPLOTS](#dotplots)  
* [BAR CHARTS](#BarCharts)  
* [HISTOGRAMS](#histograms)  
* [STEMPLOTS](#stemplots)  
* [CENTER AND SPREAD](#center_and_spread)  
* [Cluster And Gaps](#clusters_and_gaps)  
* [OUTLIERS](#outliers)  
* [CUMULATIVE RELATIV FREQUENCY AND SKEWNESS](#cumulative_relativ_frequency_and_skewness)  
* [Free-Response Questions](#free-response_questions)  

## <a name ="section0"> 第0回 顔合わせと実力テスト  

2014-06-28 AP statistics  
担当も決めます。別途FB参照  

## 基礎をみっちりと  
統計検定２級相当をしっかりやりこむ会  

* 反転授業でやっていく  
AP statistics アメリカで優秀な高校生がやる  
3期に渡って、予習して準備してやる。  

### AP statistics  
アメリカの大学は、単位ごとにお金が必要。  
このぶっとい教科書は、オーストラリアはその2倍。  
高校生はこのテキストでしっかり勉強して基準点を満たすと、お金をかけずに単位がもらえる。  
日本もこの制度入れるべきでしょう…  

### Topic1 (1回目)は35pからやる  
dotplotからsummaryまで。p44  

* 51ページに問題がある  
free-Response Questionをやる  
答えは自分で考える、記述問題。  

* p53からは回答  

* 1回ごとの範囲としては、Free-response Questionはやる。問題は不要  
個人的に問題やってみよう  

* 5回で統計検定3回相当  
確率は含まれていない。確率は別途勉強しよう。  
5回目の最終日は、統計検定3級の受付をやっている。  

* Topic1〜5(記述統計)が統計検定3級  
不足している確率は、Topic6-12(調査、確率)  
Topic13-15(推測統計 統計の目玉)  
Topic1-5が入門コース  
Topic6以降がしんどい  
がんばろう  

* 全部で54週。約一年かかる。  

* 英語の教科書を選んだ理由  
普通のじゃ面白くない  

* 統計は数学ではない。。。  
数学者から統計者は異端に見られる  
日本には統計家はいない。  

### 第1期の範囲  
できるだけ、紙の教科書があったほうがいい。  
二人一組でやる。  
なので、1回の範囲を半分発表  
発表するだけで、必ず勉強してくる  

* 1回目  
P.35-P.61  
7/19  

* 2回目  
P.62(Z-Score)-Topic2最後まで
8/9  

* 3回目  
Topic3  
8/30  

* 4回目  
Topic4  
9/20  

* 5回目  
Topic5  
10/11  


* 場所は引き続き今日の場所でやる 

----------------
### メモ  
* 統計学入門  
東大生が読む本  
kindleで探してみる  
->なかった。  

* 統計検定  
ひとまずの目標として、3級うけてみる。  

----------------

## <a name ="section1"> 第1回 Topic 1 - P35 〜 61 Standard Deviation  
データを体系化し、配置する方法は多岐にわたる  
多くの情報は表に入れることができるが、それらは、なんの配慮もされていないデータの羅列である傾向がある  
図解をすることで、パターンや形状を即座に読み取ることができる。  
最も一般的なデータの視覚化は、[dotplots](http://goo.gl/faf9qw),棒グラフ,ヒストグラム,そしてstemplots[(幹葉表示)](http://www.toukei.metro.tokyo.jp/manabou/tyuu/sirou2/tokutyou2/ma1206t24h.htm)がある。  
これらすべての視覚化表現は、明確化されていることが重要で、図が表していることに誤りがないようにすべき。  
タイトルとラベルが欠けた図は減点対象です。  


### <a name = "dotplots"> DOTPLOTS    
[Dotplots](http://goo.gl/faf9qw)と棒グラフは、[カテゴリー変数(質的変数)](http://kccn.konan-u.ac.jp/sociology/research/01/4_1.html)に関して特に有用である  
カテゴリー変数とは、個々が属しているカテゴリーを意味する。  
カテゴリー変数は、数値についての見解を意味する量的変数と対称である。  
-質的変数  
データに優劣が無く大小の比較ができないもの  
男女とか好き嫌いとか。  

-量的変数  
データ間に優劣や大小が存在する  
点数とか。  

* Example 1.1  
1クラス35人だとして、好きなスポーツを選んだ結果をdotplotで表現してみる。  
それぞれの結果の度数は、表示されているドットの数で表される。  
dotplotはvertical axis(縦軸)と横列のドットで描くことができる。  
実際は、ほとんどすべての場合でタテとヨコは交換可能であり、ページに適した形で読みやすく見やすければよい。  
この例だと、好きなスポーツというカテゴリーに対象者をドットでプロットしただけの散布図  


### <a name = "BarCharts"> BAR CHARTS  
カテゴリー、またはグループのサイズを比較する一般的なvisual display(画像表示)は、棒グラフである。  
サイズは、[度数(frequency)](http://goo.gl/TFOQ2x)または割合(パーセント)で、測定できる。  

-度数  
同じカテゴリに含まれるデータの個数のこと  

-度数分布  
すべてのカテゴリについて度数をまとめたもの  
これを表にまとめると、度数分布表  

* Example 1.2  
支持率調査結果?を棒グラフで表示  
(異なる)結果の相対的な度数は、棒グラフの高さによって表現される。  

### <a name = "histograms"> HISTOGRAMS  
ヒストグラムは量的変数を含む、大規模データ・セットに有用です。  
数またはパーセントで表すということは、正確(特定)の値か、正確(特定)の値の間のどちらとなる。  
->なんのこっちゃ？  
AP statistics の例では、ヒストグラムは書かずに、解釈する問題がしばしば出題される。  
->これは解釈のほうが大切だから？  
ツールを使ってヒストグラムを作成する手順が書かれている模様。  

* Example 1.3  
縦軸のラベルの代わりに、度数を用いることがある。  
これは、[相対度数(relative frequency)](http://www.stat.go.jp/teacher/c2dic.htm)を使うにあたり、より便利な、または意味を持った表現である。  
相対度数とは、度数を母集団の総数で割ったもの。  
縦軸がラベル付き度数、あるいは相対度数であろうとなかろうと、ヒストグラムの形状が意味するところは同じである。  
ときどき、我々は度数と相対度数の両方を同じグラフで表示することがる。  


* Example 1.4  
大企業のトップレベルの幹部に支払われる40のサラリーを表している。  
ヒストグラムからは何を学び取ることができるのか？  
例えば、$90×1000を稼いでいる幹部はおらず、また、$20×1000を下回っているものもない。  
12人が$50×1000と$60×1000の間で稼いでおり、25%が、$40×1000と$50×1000の間で稼いでいる。  
どのように、ヒストグラムはアイテム(salaries)の数を特定の値の間に落とし込んだのか。  
一方で、前の家族の数を表したヒストグラムは、それぞれの値に落とし込んでいた。  
例えば、Example 1.4だと、10人は、$40×1000と$50×1000の間の「どこか」にいる。  
Example 1.3では、700人の家族が、厳密に二人の子供を持っている。  
-> 同じヒストグラムで、正確な値をもつものと、特定の値の間という表現をしている２種類がある。  

* Example 1.5  
縦軸にラベルのない、ヒストグラムがある。  
これから何を読み取れるか？  
Answer: 実際の度数を見つけ出すことは不可能だ。  
しかし、すべてのエリアの任意の間隔の、ごく一部の範囲に注目することで、相関度数を見つけ出すことはできる。  
我々は、エリアを10等分に分割することができる。  
そして、10等分にされた1つは、10分の1、つまり10％を意味するのは、ヒストグラムの25-26の部分に相当する。  
26-27は20%,27-28は40%,28-29は30%である。  
とはいえ、通常は、ヒストグラムを綺麗に10分割することは出来ない。  
相対度数の原則は、相対的なエリアに適用したものと一致する。  
** 相対度数は、通常、異なるサイズの母集団の分布を比較するときに選択される。**   

### <a name = "stemplots"> STEMPLOTS  
ヒストグラムは、どのくらいのスコアが、それぞれのグループ、または、間隔に割り当てられているかを表すが、  
しばしば、個々のスコアの正確な値を失う。  
代替手段として、stem(葉柄という意味)plotsと呼ばれる、個々の情報を保持する表示方法がある。  

* Example 1.6  
10,20,30,40,50の代わりに、1,2,3,4,5を使い、リストは、オリジナルに適した代替手段を適用したあとの各値の最後の桁。  
外周にそって、線を引いていくと、水平方向のヒストグラムになる。  
->やっていることは同じだけど、見せ方が違うので、情報の残り方が違う。  
stemplotsは、形状はヒストグラムのようだが、オリジナルデータを指し示す部分が、ヒストグラムではない。  
ときどき、それぞれの行を照準で並び替えることによって、更に構造が見て取れる。  
この並び替えられた表示は、オリジナルのstemplotsから第二のレベルの情報を表している。  
->stemplotsよりも、より多くの情報を持っているという意味？英語難しい。むしろ英語が難しい。  

* Example 1.7  
4.07を100倍して407にして、stemplotsした図  
同じルールでstemplotsしている。  


### <a name = "center_and_spread"> CENTER AND SPREAD
Center と Spreadは常に一緒に語られる。  
グラフを見ていると、２つの重要な一般的なパターンの外見が見える。  
1. センター(中心)とは、値をおおよそ半分に分ける、(または、ヒストグラムの場合は、曲線の下の領域)  
-> ヒストグラムの場合というのがイメージできない。  
2. spread(発散)は、値の最小と最大の範囲のこと。  
Example 1.3のヒストグラムでは、センターが2childrenで、spreadが0から6のchildrenである。  
Example 1.4のヒストグラムでは、センターが$50×1000から、$60×1000の間で、spreadが、$20×1000から、$90×1000となる。  
Example 1.5のヒストグラムでは、センターが27と28の間で、spreadが、25から29である。  
Example 1.6のstemplotでは、センターが28%、spreaddが13％から、50％  
Example 1.7では、センターが、5.46で、spreadが4.07から5.86となる。  


### <a name = "clusters_and_gaps"> CLUSTERS AND GAPS  
一般的なパターンで他にも重要な見せ方がある。  
1.clusters(クラスタ),自然な形でサブグループに分類する方法。  
例えば、学校のランクが異なる教師が3人いて、その給料をみると、給料が高い傾向の集団と低い傾向の集団があるので、それらはグループ化できる？  
2.gaps(隔たり？),落としこむ場所のない穴。  
->なにこれ。  
例えば、Deanのオフィスは生徒に手紙を送ることを名誉ある役職だと思っているが、受け取る生徒は、グレードの低いものだと警戒している。  
それ故に、DEANから手紙を受け取った生徒のGPA分布は、中央に巨大なギャップがある。 
->よくわからない ???  

*  Example 1.8  
分布の中央付近、42のあたりは、spreadは31-52だが、明確に間違っている。  
この図は2つの明確に違うclustersで、隔たりがある。  


### <a name = "outliers"> OUTLIERS  
outliersと呼ばれる、極地は、多くの分布が見られる。  
ときどき、精密な調査をしても、測定結果にエラーがあることがる。  
しかし、outliersは、偶然の結果であることもある。  
outliersは分布の両端に位置する。  
Example 1.7にあるstemplotsの4.07は、明確にoutliers.  


### <a name = "cumulative_relativ_frequency_and_skewness"> CUMULATIVE RELATIV FREQUENCY AND SKEWNESS  
累積相対度数とゆがみ  
左側が歪んだ分布図は、累積度数プロットが、最初ゆっくり上昇し、そしてあとから急になる。  
右側が歪んだ分布図は、累積度数プロットが、最初が急で、あとからゆっくりとなる。  

* Example 1.11  
度数とスコアをもった3つの関係を、累積度数とスコアの関係にまとめると、分かりやすいかも。  

### <a name = "Free-response_questions"> Free-Response Questions  










