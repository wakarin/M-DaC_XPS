# 「NIMS Materials Data Conversion Tools (M-DaC)」について

国立研究開発法人物質・材料研究機構（以下、NIMS）では、物質・材料研究の一環として、実験データの効率的な収集と高付加価値化の技術開発を行っています。本開発で提供される「NIMS Materials Data Conversion Tools (M-DaC)」とは、NIMS が計測機器メーカーの協力を得て開発した実験の主要条件やメタデータの自動抽出とその翻訳作業（可読化）の自動化、ならびに多次元の数値データ行列の Schema on Read 型の可読化を行うことができるプログラムおよびソースコード群を指します。

今回開発した M-DaC を研究者等に広く使用または利用いただき、関連の技術開発をさらに推し進めることができるよう、試験用プログラム、試験用ソースコード及びサンプルデータ等（以下まとめて「本プログラム等」という）を無償で公開します。

### チュートリアル

  *M-Dac チュートリアル:* https://nims-dpfc.github.io/M-DaC_doc
 
  *M-Dac for XPS:*  https://nims-dpfc.github.io/M-DaC_doc/xps.html

### 対象装置およびメーカ　（2019年１月30日現在）

　X線光電子分光/ X-ray Photoelectron Spectroscopy (XPS)　（アルバック・ファイ株式会社）

　X線回折/ X-ray Diffraction (XRD) （株式会社リガク）



### 動作環境

　python 3.X

　Jupyter Notebook (http://jupyter.org/)



### 操作方法

* 作業ディレクトリに一式をダウンロードしてから、以下のチュートリアルのサンプルデータで一連のフローを試してください。<br />
<https://nims-dpfc.github.io/M-DaC_doc/xps.html>

* 各メーカーのお手持ちのデータがあれば、同様に処理を進めることができます。



### 利用ルールおよびライセンス

* 本プログラム等のうち、サンプルデータおよび記事コンテンツについては、「[クリエイティブ・コモンズ・ライセンスの表示-非営利4.0国際](https://creativecommons.org/licenses/by-nc/4.0/deed.ja)」のもとで「CC-BY-NC」での利用ができます。

* 本プログラム等のうち、ライセンス欄に「MITライセンス」の表記のある試験用ソースコードは別に示される『LICENSE_MIT.txt』に示されるMITライセンスのもと利用できます。

* アルバック・ファイ株式会社による試験用プログラム（MPExport.exe）は、別に示される『使用許諾書』の範囲において使用できます。

* 詳細は『Terms of Use and License_JP.md』をお読みください。



### 論文などにおける引用の表記

* M-DaCを使った研究や開発では、下記の引用例を参照してください。

日本語引用文例）　

長尾浩子, 鈴木峰晴, 吉川英樹：”NIMS Materials Data Conversion Tools (M-DaC)”, 2018 (https://github.com/nims-dpfc/M-DaC_XPS   or   https://github.com/nims-dpfc/M-DaC_XRD)

英語引用文例）

H. Nagao, M. Suzuki, and H. Yoshikawa: "NIMS Materials Data Conversion Tools (M-DaC)", 2018, (https://github.com/nims-dpfc/M-DaC_XPS   or   https://github.com/nims-dpfc/M-DaC_XRD)



### M-DaCに関するお問い合わせ

ライセンスや本プログラム等の利用方法やライセンスに関することで不明な点につきましては、以下にお問い合わせください。



国立研究開発法人物質・材料研究機構　

 　統合型材料開発・情報基盤部門 材料データプラットフォームセンター　

　 データ解析グループ（M-DaC 担当） E-mail: m-dac@ml.nims.go.jp
