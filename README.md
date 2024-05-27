# 2024年度財政経済理論研修 「国際貿易論」

## 講義概要・講義目標
概要: 現代のグローバル経済について経済学の視点から講義し、国際貿易論の考え方を解説します。また、国際貿易論において膨大な研究蓄積のある重力方程式の推定に重点を置き、統計ソフトを用いてグローバル経済を分析する基本を習得します。重力方程式は、貿易・外国直接投資・移民・観光などグローバル化の諸層を分析する基盤であり、政策効果推定にも多用されています。

目標: 重力方程式の推定手法を習得するとともに、経済学の視点からグローバル化を理解できるようになることを目標とします。

## 講義計画・講義内容

- 教科書に沿って講義します。毎回、R（[Posit Cloud](https://posit.cloud)）による実習を行います。教科書45分、R実習40分。
- 状況に応じて、内容や進度を変更します。
- 講義資料を随時更新（変更・追加等）する可能性があります。
- 講義資料は本研修のために公開しており、研修生限りとし、第３者に提供しないようにお願いします。

## 講義（90分、全８回）

1.	５月13日（月）15:20～16:50　　 [序章 グローバル化とは](slides/00国際経済学は社会にどう役立つか.pptx)、[重力方程式](slides/trade2-03-gravity.pdf)、[StataとRの利点](slides/StataとRの利点.pptx) 
1.	５月14日（火）15:20～16:50　　 [3 章 企業のグローバル化](slides/03企業のグローバル化.pptx)
1.	５月20日（月）15:20～16:50　　 [4 章 技術が貿易を決める: リカード・モデル](slides/04技術が貿易を決めるリカードモデルv2.pptx) ＊レポート説明。
1.	５月21日（火）15:20～16:50　　 [5 章 生産要素が貿易を決める: 要素比率理論](05生産要素が貿易を決めるv2.pptx)
1.	５月27日（月）15:20～16:50　　 [7 章 新・新貿易理論](slides/07新・新貿易理論.pptx)
1.	５月28日（火）15:20～16:50　　 [8 章 貿易政策（基礎編）](slides/08貿易政策_基礎編.pptx)
1.	６月３日（月）15:20～16:50　　 [11 章 グローバル化と格差](slides/11グローバル化と格差.pptx)
1.	６月４日（火）15:20～16:50　　 重力方程式と研究レポートの書き方: Google Scholarとの連携等

  - 参考）[新貿易理論](slides/trade2-01-new-trade-theory.pdf)
  - 参考）[税関データの利用についての若杉先生のスライド](slides/comment2024_Prof_Wakasugi.pdf)

### レポート
- 字数：1000字以上。
- 締切・提出先：財総研。
- 以下のいずれか１つ。標準はテーマ１。逃げ道としてテーマ２。
- テーマ1: 重力方程式を用いた政策効果分析について。R/Rマークダウンによる。詳細は5/20に説明予定。
  - [レポート・テンプレート圧縮ファイル](report.zip)を用いて下さい。
- テーマ2: 教科書の章末にある「Report assignment レポート課題」から１つ選択。
  - テーマ2選択の場合の評価上限は、C（可）になります。
  - Word（タイトル・氏名明記）で作成して下さい。

## R実習

### 準備

第2回開始までに、以下の資料でR/Posit Cloudの基本的な使い方を習得して下さい。
- [R01_Posit_Cloudアカウント作成方法.pdf](R_practice/R01_Posit_Cloudアカウント作成方法.pdf)
- [R02_Posit_CloudのProjectの共有方法.pdf](R_practice/R02_Posit_CloudのProjectの共有方法.pdf)
- [R03_Posit_Cloud_Project作成とDownload方法.pdf](R_practice/R03_Posit_Cloud_Project作成とDownload方法.pdf)
- [R04_R_Markdownの使い方.pdf](R_practice/R04_R_Markdownの使い方.pdf)
- [R05_Data読み込み方法.pdf](R_practice/R05_Data読み込み方法.pdf)  | [trade2013.csv](R_practice//trade2013.csv)
- [R06_packagesのインストール方法.pdf](R_practice/R06_packagesのインストール方法.pdf)  **5/13追加**
- [R07_reference作成方法.pdf](R_practice/R07_reference作成方法.pdf)  **5/20追加、6/4説明予定**

### 重力方程式

- 第2回以降以下のトピックを１つずつ進めて行ければ理想的ですが、実際には状況を見ながら、できる範囲で進めていきます。
- 実習に用いるデータは[ここ](R)からダウンロードできます。
- Posit Cloudのプロジェクトページ見本は、[こちら](https://posit.cloud/content/8176658)にあります。個々のファイルは[ここ](8176658)からダウンロードできます。圧縮ファイルは[こちら](8176658.zip)からダウンロードできます。

1. [貿易データの分析](https://rpubs.com/ayumuR/trade_data)  担当：田中さん
2. [伝統的な重力方程式の推定](https://rpubs.com/ayumuR/gravity_explanation)  担当：伊藤さん
3. [現代的な重力方程式の推定 with fixest](https://rpubs.com/ayumuR/gravity_fixest)  担当：山口さん、福室さん
4. [現代的な重力方程式のパネル推定 with fixest](https://rpubs.com/ayumuR/gravity_fixest_panel)  担当：正司さん、吉田さん
5. [重力方程式を用いた2元固定効果差の差推定](https://rpubs.com/ayumuR/gravity_fixest_twfe)  担当：秋元さん、浦田さん
6. [重力方程式を用いた多期間差の差推定](https://rpubs.com/ayumuR/gravity_fixest_es)  担当：多部さん、細江さん
7. [ggplot2で貿易フローの地図を作成](https://rpubs.com/ayumuR/trade_flow_ggplot2)  担当：知田さん、野坂さん

### 参考
- [R Markdown入門](https://kazutan.github.io/kazutanR/Rmd_intro.html)
- [Posit Cloud入門](https://shunichinomura.github.io/cloud.html)


## 教科書
伊藤萬里・田中鮎夢（2023）[『現実からまなぶ国際経済学』](https://www.yuhikaku.co.jp/books/detail/9784641200012)（有斐閣）

- 正誤表が出版社のHPにあります。

## 参考文献
- 田中鮎夢（2015）『新々貿易理論とは何か: 企業の異質性と21世紀の国際経済』ミネルヴァ書房。
  - 元原稿：RIETI、[国際貿易と貿易政策研究メモ](https://www.rieti.go.jp/users/tanaka-ayumu/serial/index.html)
- 田中鮎夢（2017）[「やさしい経済学―国際貿易論の新しい潮流」](https://www.rieti.go.jp/jp/papers/contribution/yasashii23/index.html)

その他、教科書巻末に文献紹介があります。



