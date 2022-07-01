主に日本語で書かれた文法誤り訂正分野の文献を収集・分類することを目的としています．

査読有りの文献には査読カラムに「有」と表記されます．

# 目次

* [まとめ・サーベイなど](https://github.com/gotutiyan/GEC-Info-ja#%E3%81%BE%E3%81%A8%E3%82%81%E3%82%B5%E3%83%BC%E3%83%99%E3%82%A4%E3%81%AA%E3%81%A9)
* [英語を対象とするもの](https://github.com/gotutiyan/GEC-Info-ja#%E8%8B%B1%E8%AA%9E%E3%82%92%E5%AF%BE%E8%B1%A1%E3%81%A8%E3%81%99%E3%82%8B%E3%82%82%E3%81%AE)
    * [評価尺度](https://github.com/gotutiyan/GEC-Info-ja#%E8%A9%95%E4%BE%A1%E5%B0%BA%E5%BA%A6)
    * [モデル](https://github.com/gotutiyan/GEC-Info-ja#%E3%83%A2%E3%83%87%E3%83%AB%E6%8F%90%E6%A1%88)
    * [データセット](https://github.com/gotutiyan/GEC-Info-ja#%E3%83%87%E3%83%BC%E3%82%BF%E3%82%BB%E3%83%83%E3%83%88)
    * [アノテーション](https://github.com/gotutiyan/GEC-Info-ja#%E3%82%A2%E3%83%8E%E3%83%86%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3)
    * [擬似データ生成](https://github.com/gotutiyan/GEC-Info-ja#%E6%93%AC%E4%BC%BC%E3%83%87%E3%83%BC%E3%82%BF%E7%94%9F%E6%88%90)
    * [データクリーニング](https://github.com/gotutiyan/GEC-Info-ja#%E3%83%87%E3%83%BC%E3%82%BF%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%8B%E3%83%B3%E3%82%B0)
    * [分析](https://github.com/gotutiyan/GEC-Info-ja#%E5%88%86%E6%9E%90)
    * [誤り検出](https://github.com/gotutiyan/GEC-Info-ja#%E8%AA%A4%E3%82%8A%E6%A4%9C%E5%87%BA)
    * [文法誤り訂正・検出以外の学習者英語を対象とした話題](https://github.com/gotutiyan/GEC-Info-ja#%E6%96%87%E6%B3%95%E8%AA%A4%E3%82%8A%E8%A8%82%E6%AD%A3%E6%A4%9C%E5%87%BA%E4%BB%A5%E5%A4%96%E3%81%AE%E5%AD%A6%E7%BF%92%E8%80%85%E8%8B%B1%E8%AA%9E%E3%82%92%E5%AF%BE%E8%B1%A1%E3%81%A8%E3%81%97%E3%81%9F%E8%A9%B1%E9%A1%8C)
* [日本語を対象とするもの](https://github.com/gotutiyan/GEC-Info-ja#%E6%97%A5%E6%9C%AC%E8%AA%9E%E3%82%92%E5%AF%BE%E8%B1%A1%E3%81%A8%E3%81%99%E3%82%8B%E3%82%82%E3%81%AE)
    * [モデル](https://github.com/gotutiyan/GEC-Info-ja#%E3%83%A2%E3%83%87%E3%83%AB%E6%8F%90%E6%A1%88-1)
    * [データセット](https://github.com/gotutiyan/GEC-Info-ja#%E3%83%87%E3%83%BC%E3%82%BF%E3%82%BB%E3%83%83%E3%83%88-1)
    * [擬似誤り生成](https://github.com/gotutiyan/GEC-Info-ja#%E6%93%AC%E4%BC%BC%E8%AA%A4%E3%82%8A%E7%94%9F%E6%88%90)
    * [分析](https://github.com/gotutiyan/GEC-Info-ja#%E5%88%86%E6%9E%90-1)
    * [誤り検出](https://github.com/gotutiyan/GEC-Info-ja#%E8%AA%A4%E3%82%8A%E6%A4%9C%E5%87%BA-1)
    * [システム開発](https://github.com/gotutiyan/GEC-Info-ja#%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E9%96%8B%E7%99%BA)
* [中国語を対象とするもの](https://github.com/gotutiyan/GEC-Info-ja#%E4%B8%AD%E5%9B%BD%E8%AA%9E%E3%82%92%E5%AF%BE%E8%B1%A1%E3%81%A8%E3%81%99%E3%82%8B%E3%82%82%E3%81%AE)
* [ロシア語を対象とするもの](https://github.com/gotutiyan/GEC-Info-ja#%E3%83%AD%E3%82%B7%E3%82%A2%E8%AA%9E%E3%82%92%E5%AF%BE%E8%B1%A1%E3%81%A8%E3%81%99%E3%82%8B%E3%82%82%E3%81%AE)
* [多言語を対象とするもの](https://github.com/gotutiyan/GEC-Info-ja#%E5%A4%9A%E8%A8%80%E8%AA%9E%E3%82%92%E5%AF%BE%E8%B1%A1%E3%81%A8%E3%81%99%E3%82%8B%E3%82%82%E3%81%AE)
* [関連タスク](https://github.com/gotutiyan/GEC-Info-ja#%E9%96%A2%E9%80%A3%E3%82%BF%E3%82%B9%E3%82%AF)
    * [解説文生成](https://github.com/gotutiyan/GEC-Info-ja#%E8%A7%A3%E8%AA%AC%E6%96%87%E7%94%9F%E6%88%90)
* [プロジェクト・企画など](https://github.com/gotutiyan/GEC-Info-ja#%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E4%BC%81%E7%94%BB%E3%81%AA%E3%81%A9)
* [解説記事・学会記事など](https://github.com/gotutiyan/GEC-Info-ja#%E8%A7%A3%E8%AA%AC%E8%A8%98%E4%BA%8B%E5%AD%A6%E4%BC%9A%E8%A8%98%E4%BA%8B%E3%81%AA%E3%81%A9)

# まとめ・サーベイなど

|タイトル|リンク|Note|
|:--|:--|:--|
|私のブックマーク 「自然言語処理による文法誤り訂正」|[[website]](https://www.ai-gakkai.or.jp/resource/my-bookmark/my-bookmark_vol33-no6/) [[pdf]](https://www.jstage.jst.go.jp/article/jjsai/33/6/33_893/_pdf/-char/ja)|2011-2018ごろの文法誤り訂正の動向を追うのに有用．|

# 英語を対象とするもの

### 評価尺度

|キーワード/概要|Year|論文|査読|Note|
|:--|:--|:--|:--|:--|
||2017|[文法誤り訂正のためのリファレンスレス評価](https://www.anlp.jp/proceedings/annual_meeting/2017/pdf_dir/E6-4.pdf)|||
||2018|[文法性・流暢性・意味保存性に基づく文法誤り訂正の参照無し評価](https://www.jstage.jst.go.jp/article/jnlp/25/5/25_555/_article/-char/ja)|有||
||2020|[訂正難易度を考慮した文法誤り訂正のための性能評価尺度](https://www.anlp.jp/proceedings/annual_meeting/2020/pdf_dir/P2-3.pdf)|||
||2021|[文法誤り訂正の参照文を用いない自動評価の人手評価への最適化](https://www.jstage.jst.go.jp/article/jnlp/28/2/28_404/_article/-char/ja)|有||
||2022|[IMPARA: パラレルデータにおける修正の影響度に基づいた文法誤り訂正の自動評価法](https://www.anlp.jp/proceedings/annual_meeting/2022/pdf_dir/G2-3.pdf)|||
||2022|[論述リビジョンのためのメタ評価基盤](https://www.anlp.jp/proceedings/annual_meeting/2022/pdf_dir/E3-3.pdf)|||

### モデル

|キーワード/概要|Year|論文|査読|Note|
|:--|:--|:--|:--|:--|
||2011|[自動獲得されるルールに基づく英文冠詞誤り校正手法における最大エントロピー分類器の利用](https://www.anlp.jp/proceedings/annual_meeting/2011/pdf_dir/P3-2.pdf)|||
||2012|[大域的文脈情報を用いた英語時制誤りの検出と訂正](https://www.anlp.jp/proceedings/annual_meeting/2012/pdf_dir/A2-4.pdf)|||
||2012|[冠詞誤り訂正時における訂正根拠の提示](https://www.anlp.jp/proceedings/annual_meeting/2012/pdf_dir/A2-3.pdf)|||
||2013|[学習者の誤り傾向を反映した英語動詞選択誤りへの訂正候補推薦](https://www.anlp.jp/proceedings/annual_meeting/2013/index.html)|||
||2013|[前置詞誤り検出／訂正のための誤り格フレームの生成](https://www.anlp.jp/proceedings/annual_meeting/2013/index.html)|||
||2014|[定冠詞の前方照応用法を考慮した冠詞誤り訂正](https://www.anlp.jp/proceedings/annual_meeting/2014/pdf_dir/P4-9.pdf)|||
||2014|[誤りに関する説明を提示可能な前置詞誤り訂正手法](https://www.anlp.jp/proceedings/annual_meeting/2014/pdf_dir/P2-10.pdf)|||
||2015|[高度な英文訂正への統計的機械翻訳技術の適用](https://www.anlp.jp/proceedings/annual_meeting/2015/pdf_dir/A3-1.pdf)|||
||2016|[文脈を考慮した前置詞誤り訂正に向けた前置詞とその潜在意味関係の同時解析](https://www.anlp.jp/proceedings/annual_meeting/2016/pdf_dir/E3-2.pdf)|||
||2016|[リランキングによる文法誤り訂正/訂正候補提示の性能改善](https://www.anlp.jp/proceedings/annual_meeting/2016/pdf_dir/P3-2.pdf)|||
||2017|[学習者英語のための綴り誤り訂正手法と綴り誤り分析への応用](https://www.anlp.jp/proceedings/annual_meeting/2017/pdf_dir/E6-3.pdf)|||
||2017|[文法誤り訂正のための疑似誤り生成によるラベルなしコーパスの利用](https://www.anlp.jp/proceedings/annual_meeting/2017/pdf_dir/P15-2.pdf)|||
||2018|[ニューラル機械翻訳モデルを用いたマルチソース文法誤り訂正](https://www.jstage.jst.go.jp/article/pjsai/JSAI2018/0/JSAI2018_4Pin123/_article/-char/en)|||
||2018|[パイプライン処理によるニューラル英語文法誤り検出と訂正](https://www.anlp.jp/proceedings/annual_meeting/2018/pdf_dir/P4-23.pdf)|||
||2019|[教師なし文法誤り訂正](https://www.anlp.jp/proceedings/annual_meeting/2019/pdf_dir/P8-1.pdf)|||
||2019|[文法誤り訂正における単語編集率を用いた訂正度の制御](https://www.anlp.jp/proceedings/annual_meeting/2019/pdf_dir/P3-32.pdf)|||
||2020|[学習者の誤り傾向を考慮した擬似データを用いた文法誤り訂正](https://www.anlp.jp/proceedings/annual_meeting/2020/pdf_dir/P5-9.pdf)||ロシア語の実験もあり|
||2020|[大規模疑似データを用いた高性能文法誤り訂正モデルの構築](https://www.anlp.jp/proceedings/annual_meeting/2020/pdf_dir/D4-1.pdf)|||
||2020|[分類器による英文前置詞誤り訂正の学習法](https://www.anlp.jp/proceedings/annual_meeting/2020/pdf_dir/P1-25.pdf)|||
||2021|[文法誤り訂正における訂正度を考慮した多様な訂正文の生成](https://www.jstage.jst.go.jp/article/jnlp/28/2/28_428/_article/-char/ja)|有||
||2021|[高再現率な文法誤り訂正システムの実現に向けて](https://www.anlp.jp/proceedings/annual_meeting/2021/pdf_dir/B8-3.pdf)|||
||2021|[L1-aware Grammatical Error Correction via Multitasking with Native Language Estimation](https://www.anlp.jp/proceedings/annual_meeting/2021/pdf_dir/D5-3.pdf)|||
||2022|[Masked Language Model による系列確率に基づく文法誤り検出](https://www.anlp.jp/proceedings/annual_meeting/2022/pdf_dir/PT4-17.pdf)|||

### データセット

|キーワード/概要|Year|論文|査読|Note|
|:--|:--|:--|:--|:--|
|KJコーパス|2011|[文法誤り情報および品詞／句情報付き英語学習者コーパスの構築](https://www.anlp.jp/proceedings/annual_meeting/2011/pdf_dir/A3-1.pdf)|||
||2017|[綴り誤り研究のための日本人英語学習者コーパスの構築](https://www.anlp.jp/proceedings/annual_meeting/2017/pdf_dir/P18-6.pdf)|||

### アノテーション

|キーワード/概要|Year|論文|査読|Note|
|:--|:--|:--|:--|:--|
||2015|[英語学習者の作文における誤りタグの自動付与](https://www.anlp.jp/proceedings/annual_meeting/2015/pdf_dir/E6-4.pdf)|||
||2015|[英語学習者コーパスのための句構造アノテーション](https://www.anlp.jp/proceedings/annual_meeting/2015/pdf_dir/P1-6.pdf)|||

### 擬似データ生成

|キーワード/概要|Year|論文|査読|Note|
|:--|:--|:--|:--|:--|
||2021|[ニューラル文法誤り訂正のための多様な規則を用いる人工誤り生成](https://www.anlp.jp/proceedings/annual_meeting/2021/pdf_dir/P5-18.pdf)|||
||2021|[文法誤り訂正モデルのエラー分析に基づく疑似データ生成の効果検証](https://www.anlp.jp/proceedings/annual_meeting/2021/pdf_dir/D7-4.pdf)|||
||2022|[多様な規則を活用した文法誤り訂正のデータ拡張に関する分析](https://www.jstage.jst.go.jp/article/jnlp/29/2/29_542/_article/-char/ja)|有||

### データクリーニング

|キーワード/概要|Year|論文|査読|Note|
|:--|:--|:--|:--|:--|
||2020|[文法誤り訂正のための自己改良戦略に基づくノイズ除去](https://www.anlp.jp/proceedings/annual_meeting/2020/pdf_dir/D4-2.pdf)|||

### 分析

|キーワード/概要|Year|論文|査読|Note|
|:--|:--|:--|:--|:--|
||2010|[英文冠詞誤りの自動校正手法におけるアプローチの違いによる傾向分析](https://www.anlp.jp/proceedings/annual_meeting/2010/pdf_dir/PA1-38.pdf)|||
||2014|[統計的機械翻訳に基づく英語文法誤り訂正におけるフレーズベースと統語ベースの比較と分析](https://www.anlp.jp/proceedings/annual_meeting/2014/pdf_dir/P4-12.pdf)|||
||2016|[文法誤り訂正における問題点の考察と新タスクの提案](https://www.anlp.jp/proceedings/annual_meeting/2016/pdf_dir/E3-3.pdf)||
||2017|[英語学習者の文法誤りパターンと正誤情報を考慮した単語分散表現学習](https://www.anlp.jp/proceedings/annual_meeting/2017/pdf_dir/P15-6.pdf)|||
||2019|[文法誤り訂正のコーパス横断評価 : 単一コーパス評価で十分か?](https://www.anlp.jp/proceedings/annual_meeting/2019/pdf_dir/C5-2.pdf)|||
||2019|[⽂法誤り訂正における反復訂正の効果検証](https://www.anlp.jp/proceedings/annual_meeting/2019/pdf_dir/P3-17.pdf)|||
||2021|[文法誤り訂正モデルは訂正に必要な文法を学習しているか](https://www.anlp.jp/proceedings/annual_meeting/2021/pdf_dir/D4-4.pdf)|||
||2021|[文法誤り訂正における複数の逆翻訳モデルを利用した訂正傾向の比較](https://www.anlp.jp/proceedings/annual_meeting/2021/pdf_dir/P5-19.pdf)|||
||2021|[文法誤り訂正モデルの横断評価](https://www.jstage.jst.go.jp/article/jnlp/28/1/28_160/_article/-char/ja)|有||
||2022|[文法誤り訂正への訂正重要度の導入](https://www.anlp.jp/proceedings/annual_meeting/2022/pdf_dir/E3-1.pdf)|||
||2022|[ニューラル文法誤り訂正システムにおけるリランキングの改善に向けたオラクル分析](https://www.anlp.jp/proceedings/annual_meeting/2022/pdf_dir/G4-2.pdf)|||

### 誤り検出

|キーワード/概要|Year|論文|査読|Note|
|:--|:--|:--|:--|:--|
||2010|[学習効果を最大とするための英文誤り検出の性能評価](https://www.anlp.jp/proceedings/annual_meeting/2010/pdf_dir/A4-4.pdf)|||
||2011|[Stativity判定に基づいた時制誤り検出](https://www.anlp.jp/proceedings/annual_meeting/2011/pdf_dir/A5-4.pdf)|||
||2018|[正誤情報と文法誤りパターンを考慮した単語分散表現を用いた文法誤り検出](https://www.jstage.jst.go.jp/article/jnlp/25/4/25_421/_article/-char/ja)|有||
||2019|[深層言語表現モデルに対するマルチヘッド・多層アテンションによる英語文法誤り検出](https://www.anlp.jp/proceedings/annual_meeting/2019/pdf_dir/P1-36.pdf)|||
||2022|[大規模マスク言語モデルの文法誤り認識能力](https://www.anlp.jp/proceedings/annual_meeting/2022/pdf_dir/PT1-16.pdf)|||

### 文法誤り訂正・検出以外の学習者英語を対象とした話題

|キーワード/概要|Year|論文|査読|Note|
|:--|:--|:--|:--|:--|
||2013|[前方文脈を考慮した冠詞の推定](https://www.anlp.jp/proceedings/annual_meeting/2013/pdf_dir/P4-18.pdf)|||
||2014|[非母語話者英語における母語の親縁関係の保持](https://www.anlp.jp/proceedings/annual_meeting/2014/pdf_dir/E6-3.pdf)|||
||2015|[英語学習者コーパスにおける名詞句発達分析](https://www.anlp.jp/proceedings/annual_meeting/2015/pdf_dir/E5-4.pdf)|||
||2015|[運用能力レベル別に見る英語学習者発話の情報構造](https://www.anlp.jp/proceedings/annual_meeting/2015/pdf_dir/E5-3.pdf)|||
||2016|[日本語学習者の作文における誤用タイプの階層的アノテーションに基づく機械学習による自動分類](https://www.jstage.jst.go.jp/article/jnlp/23/2/23_195/_article/-char/ja)|有||
||2016|[英語動詞の適切な使い分けを支援するシステムの開発](https://www.anlp.jp/proceedings/annual_meeting/2016/pdf_dir/A3-2.pdf)|||
||2016|[冠詞推定のための情報構造仮説の検討](https://www.anlp.jp/proceedings/annual_meeting/2016/pdf_dir/P12-3.pdf)|||
||2017|[スペル誤りに着目した学習者の英語に対する品詞タグ付け・チャンキングの性能調査](https://www.anlp.jp/proceedings/annual_meeting/2017/pdf_dir/P9-5.pdf)|||
||2018|[品詞解析の学習者英語への分野適応](https://www.anlp.jp/proceedings/annual_meeting/2018/pdf_dir/E3-3.pdf)|||
||2018|[綴り誤りが語彙の豊富さの指標に与える影響の分析](https://www.anlp.jp/proceedings/annual_meeting/2018/pdf_dir/P6-4.pdf)|||


# 日本語を対象とするもの

### モデル

|キーワード/概要|Year|論文|査読|Note|
|:--|:--|:--|:--|:--|
||2009|[重み付き有限状態トランスデューサーを用いた文字誤り訂正](https://www.anlp.jp/proceedings/annual_meeting/2009/pdf_dir/C2-5.pdf)|||
||2011|[大規模添削コーパスを用いた統計的機械翻訳手法による日本語誤り訂正](https://www.anlp.jp/proceedings/annual_meeting/2011/pdf_dir/E4-5.pdf)|||
||2012|[日本語学習者の作文の誤り訂正に向けた単語分割](https://www.anlp.jp/proceedings/annual_meeting/2012/pdf_dir/A1-7.pdf)|||
||2012|[識別的系列変換を用いた日本語助詞誤りの訂正](https://www.anlp.jp/proceedings/annual_meeting/2012/pdf_dir/A1-5.pdf)|||
||2012|[日本語学習者の誤り傾向を反映した格助詞訂正](https://www.anlp.jp/proceedings/annual_meeting/2012/pdf_dir/A1-4.pdf)|||
||2013|[日本語学習者の作文自動誤り訂正のための語学学習SNSの添削ログからの知識獲得](https://www.jstage.jst.go.jp/article/tjsai/28/5/28_B-C76/_article/-char/ja)|有||
||2014|[小規模誤りデータからの日本語学習者作文の助詞誤り訂正](https://www.jstage.jst.go.jp/article/jnlp/19/5/19_381/_article/-char/ja)|有||
||2014|[Particle Error Correction from Small Error Data for Japanese Learners](https://www.jstage.jst.go.jp/article/jnlp/21/4/21_941/_article/-char/ja)|有||
||2019|[分類モデルを用いた日本語学習者の格助詞誤り訂正](https://www.anlp.jp/proceedings/annual_meeting/2019/pdf_dir/C4-8.pdf)|||
||2022|[高速な文法誤り訂正機能を持つ日本語ライティング支援システムの構築](https://www.jstage.jst.go.jp/article/tjsai/37/1/37_37-1_B-L22/_article/-char/ja)|有||

### データセット

|キーワード/概要|Year|論文|査読|Note|
|:--|:--|:--|:--|:--|
||2020|[日本語学習者の文法誤り訂正のための評価コーパス構築](https://www.anlp.jp/proceedings/annual_meeting/2020/pdf_dir/P2-1.pdf)|||
||2021|[日本語Wikipediaの編集履歴に基づく入力誤りデータセットと訂正システムの改良](https://www.anlp.jp/proceedings/annual_meeting/2021/pdf_dir/E8-3.pdf)|||
||2022|[日本語文法誤り訂正の流暢性評価に向けたデータ作成](https://www.anlp.jp/proceedings/annual_meeting/2022/pdf_dir/PT4-3.pdf)|||
||2022|[日本語 Wikipedia の編集履歴に基づく入力誤りデータセットと訂正システムの構築](https://www.jstage.jst.go.jp/article/jnlp/28/4/28_995/_article/-char/ja)|有||

### 擬似誤り生成

|キーワード/概要|Year|論文|査読|Note|
|:--|:--|:--|:--|:--|
||2018|[誤り文の自動生成による校正エンジンの学習](https://www.anlp.jp/proceedings/annual_meeting/2018/pdf_dir/C7-2.pdf)|||
||2020|[日本語文法誤り訂正における誤り傾向を考慮した擬似誤り生成](https://www.anlp.jp/proceedings/annual_meeting/2020/pdf_dir/F2-3.pdf)|||

### 分析

|キーワード/概要|Year|論文|査読|Note|
|:--|:--|:--|:--|:--|
||2012|[外国語母語話者が作成する日本語技術文書を対象とした訂正履歴の分析](https://www.anlp.jp/proceedings/annual_meeting/2012/pdf_dir/A1-9.pdf)|||
||2013|[論文作成支援のための学生論文における不適切な表現の分析](https://www.anlp.jp/proceedings/annual_meeting/2013/pdf_dir/P5-4.pdf)|||
||2013|[Data Coverage vs. Data Size: A comparison of two large-scale corpora in Collocation Suggestion for Japanese Second Language Learners](https://www.anlp.jp/proceedings/annual_meeting/2013/pdf_dir/X1-4.pdf)|||
||2020|[日本語文法誤り訂正における最適な分割単位の調査](https://www.anlp.jp/proceedings/annual_meeting/2020/pdf_dir/P6-6.pdf)|||

### 誤り検出

|キーワード/概要|Year|論文|査読|Note|
|:--|:--|:--|:--|:--|
||2012|[複数分野の文書を用いた日本語誤り表現の検出](https://www.anlp.jp/proceedings/annual_meeting/2012/pdf_dir/P2-12.pdf)|||
||2014|[保険関連文書を対象とした文章校正支援のための変換誤り検出](https://www.anlp.jp/proceedings/annual_meeting/2014/index.html)|||
||2017|[マイクロブログを対象とした形態素解析誤りの自動検出と誤り分析](https://www.anlp.jp/proceedings/annual_meeting/2017/pdf_dir/P5-3.pdf)|||
||2019|[小論文採点支援システムにおける文字誤り検出モジュールの構築](https://www.anlp.jp/proceedings/annual_meeting/2019/pdf_dir/C4-3.pdf)|||
||2022|[日本語学習者向けの文法誤り検出機能付き作文用例検索システム](https://www.jstage.jst.go.jp/article/tjsai/35/5/35_35-5_A-K23/_article/-char/ja)|有||

### システム開発

|キーワード/概要|Year|論文|査読|Note|
|:--|:--|:--|:--|:--|
||2014|[第二言語学習者の作文誤り訂正タスクのためのユーザインターフェース](https://www.anlp.jp/proceedings/annual_meeting/2014/pdf_dir/P4-8.pdf)|||
||2016|[日本語学習支援のためのコーパス構築システム](https://www.anlp.jp/proceedings/annual_meeting/2016/pdf_dir/E3-5.pdf)|||
||2018|[Lang-8を用いた日本語学習者向けの誤用検索システムの構築](https://www.anlp.jp/proceedings/annual_meeting/2018/pdf_dir/P1-23.pdf)|||
||2019|[日本語学習者向けの文法誤り検出機能付き誤用例文検索システム](https://www.anlp.jp/proceedings/annual_meeting/2019/pdf_dir/P5-16.pdf)|||

# 中国語を対象とするもの

|キーワード/概要|Year|論文|査読|Note|
|:--|:--|:--|:--|:--|
||2020|[事前学習モデルを用いた中国語文法誤り訂正](https://www.anlp.jp/proceedings/annual_meeting/2020/pdf_dir/P4-1.pdf)|||

# ロシア語を対象とするもの

|キーワード/概要|Year|論文|査読|Note|
|:--|:--|:--|:--|:--|
||2020|[言語間での転移学習を用いたロシア語文法誤り訂正](https://www.anlp.jp/proceedings/annual_meeting/2020/pdf_dir/P6-3.pdf)|||

# 多言語を対象とするもの

|キーワード/概要|Year|論文|査読|Note|
|:--|:--|:--|:--|:--|
||2022|[言語間での転移学習のための事前学習モデルと多言語の学習者データを用いた文法誤り訂正](https://www.jstage.jst.go.jp/article/jnlp/29/2/29_314/_article/-char/ja)|有||

# 関連タスク

### 解説文生成

|キーワード/概要|Year|論文|査読|Note|
|:--|:--|:--|:--|:--|
||2019|[英語ライティング学習支援のための前置詞誤り解説生成](https://www.anlp.jp/proceedings/annual_meeting/2019/pdf_dir/C4-9.pdf)|||
||2019|[解説文生成研究のためのライティング技術解説付き学習者コーパス](https://www.anlp.jp/proceedings/annual_meeting/2019/pdf_dir/P1-1.pdf)|||
||2020|[文法誤り解説文生成とはどのようなタスクなのか?](https://www.anlp.jp/proceedings/annual_meeting/2020/pdf_dir/F2-5.pdf)|||
||2021|[仮想的な誤りタイプの割り当てによる解説文生成の性能向上](https://www.anlp.jp/proceedings/annual_meeting/2021/pdf_dir/D4-1.pdf)|||
||2021|[英語学習者のための解説文生成手法の調査](https://www.anlp.jp/proceedings/annual_meeting/2021/pdf_dir/D7-3.pdf)|||

# プロジェクト・企画など

|キーワード/概要|Year|リンク|Note|
|:--|:--|:--|:--|
|GECアドベントカレンダー|2021|[GEC (Grammatical Error Correction) Advent Calendar 2021](https://qiita.com/advent-calendar/2021/gec)||

# 解説記事・学会記事など

|タイトル|Year|Note|
|:--|:--|:--|
|[事前学習済みマスク言語モデルを組み合わせた符号化復号化文法誤り訂正モデル](https://www.jstage.jst.go.jp/article/jnlp/27/3/27_683/_article/-char/ja)|2020||
|[Stronger Baselines for Grammatical Error Correction Using a Pretrained Encoder-Decoder Model](https://www.jstage.jst.go.jp/article/jnlp/28/1/28_276/_article/-char/ja)|2021||
|[Do Grammatical Error Correction Models Realize Grammatical Generalization?](https://www.jstage.jst.go.jp/article/jnlp/28/4/28_1331/_article/-char/ja)|2021||
|[Exploring Methods for Generating Feedback Comments for Writing Learning](https://www.jstage.jst.go.jp/article/jnlp/29/1/29_270/_article/-char/ja)|2022||