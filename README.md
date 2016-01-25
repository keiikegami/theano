# theanoを使ってDCDP

##やること

[消費生活に関するパネルデータ](http://www.kakeiken.or.jp/jp/index.html)
を使って、Yamaguchi(2015)の結果を再現します。

パラメータ推定には、deep leaning界隈で使われているtheanoを使ってみる。

全体のアルゴリズムはRust(1987)のNFXPを用いるが、Yamaguchi(2015)に合わせてDPを解く際に以下の手法を組み込む
[Kasahara and Shimotsu](http://faculty.arts.ubc.ca/hkasahara/workingpapers/sequential_estimation.pdf)

##できたらやることと

自分の書いたコードで、別のパネルデータを用いてNFXPをやってみる。

例えば、以下のようなパネルデータが存在する
[日本子どもパネル調査](http://www.pdrc.keio.ac.jp/open/post.html)
[東日本大震災に関する特別調査](http://www.pdrc.keio.ac.jp/open/about-shinsai-panel.html)
