---
title: 研究
layout: single
sidebar:
  nav: "research"
---
## 研究概要
当研究室の主な研究分野は，人工知能の一分野である知識工学と自然言語処理です．当研究室では，計算機が利用・共有可能な知識の構築と洗練，異なる知識の統合，推論を用いた知識の導出，知識推論を利用した計算機システム，自然言語処理の応用に関する研究を行っています．

人間の知的作業を支援する計算機システムを構築するためには，知識を計算機が処理できるように形式化すること（知識表現）が必要です．知識表現モデルには，知識グラフ（概念や具体物間の関係を記述したグラフ），ワークフロー（業務の処理手順を定義したもの），ルール（規則・条件・判断基準などを記述したもの）などがあり，質問応答，音声対話，意味検索，知識継承，知識マネジメント，ソフトウェア開発，自動運転，エキスパートシステム（専門家の知識に基づいて，推論や問題解決が可能な計算機システム），セマンティックWeb（計算機が自律的にWebページの意味を理解可能なWeb）など，様々な領域に応用されています．しかしながら，知識表現モデルの構築コストが高いことが課題となっており，Webページ，専門文書，大規模言語モデルなどから，自動的に知識表現モデルを構築するための手法が求められています．以上より，当研究室では「知識表現モデルの自動構築」に焦点を当てて研究を進めています．また，知識表現モデルを利用した計算機システムの研究開発も行います．さらに，自然言語処理の応用を通して，自然言語における「意味」のもつ複雑性を人工知能が把握できるようにするための研究も行っています．

{: align="center"}
![研究概要](/assets/images/research_overview.png)  
研究概要

## 主な研究テーマ

### 1. 知識グラフ構築支援
現状のWebページはHTMLにより，人間向けに記述されているため，ソフトウェアがWebページの内容を直接理解することは困難です．セマンティックWebでは，オントロジー（ソフトウェアが意味理解可能な辞書）を参照しながら，RDF（リソースを記述するためのデータモデルと記述言語）を用いて，Webページのメタデータを記述し，知識グラフを構築することにより，推論技術を用いた情報検索や情報統合などが実現できると期待されています．

知識グラフの構築コストが高いことがセマンティックWeb実現の課題であることから，自然言語文，Webページ，大規模言語モデルなどから，知識グラフの自動構築を行うための手法を研究しています．知識グラフ自動構築の基礎研究として，テキスト中のエンティティ名（人や物の名前）を知識グラフ中のリソースに結びつけるタスクであるエンティティリンキングの研究や自動構築された知識グラフには欠落や誤りが含まれるため，知識グラフの補完や訂正をする手法についても研究しています．

### 2. 知識グラフを利用した計算機システム
表情変化が可能なソーシャルロボット [Furhat](https://furhatrobotics.com/) やチャットボットなどのソフトウェアエージェントを用いた質問応答システムや音声対話システムを研究開発します．家庭シミュレータ[VirtualHome](http://virtual-home.org)上で，常識・行動・領域知識に基づき家庭内行動を推論する対話エージェントシステムの研究開発もしています．

### 3. 自然言語処理の応用
入力された自然言語文の「意味」に即した汎用的な処理を行えるシステムは，近年の深層学習技術の進展にかかわらず工学的には未達成の課題となっています．本テーマでは，大規模言語モデルに基づく意味処理システムの開発を行います．具体的には，日常生活に関する様々な抽象度の説明文から家庭シミュレータVirtualHome上でエージェントを動作させるために必要なアクションスクリプト（アクションとその対象オブジェクトから構成）を自動生成する手法を研究します．また，高齢者にとって事故につながる可能性の高い環境や行動などを検出し，その根拠や解決策を提示する手法を研究します．さらに，人の発話の意味を考えて議論可能な議論システムを研究開発します．

## 修士研究テーマ
### 2023年度修士研究テーマ
* マルチモーダル大規模言語モデルと画像キャプションに基づく描画内容に即した併置型駄洒落の認識
* 大規模知識グラフを対象とした英語エンティティリンキングモデルの日本語対応
* 大規模言語モデルに基づくWikipediaから抽出した未知エンティティを用いたDBpediaの拡張

### 2021年度修士研究テーマ
* 家庭環境知識と常識推論に基づく双方向型対話ナビゲーションシステムの開発
* 知識グラフに基づく質問応答システムにおける論理形式パターンを用いた論理形式検索の改善

## 卒業研究テーマ

### 2023年度卒業研究テーマ
* Wikipediaの赤リンクを用いたDBpediaにおける未知エンティティの抽出
* 文章生成AIが生成した家庭内危険行動の理由に対する根拠提示システム
* LangChainのメモリに基づくGPTの日本語対話継続能力の分析
* 文章生成AIに基づく家庭内行動の推論と対話型ナビゲーション
* GPTに基づく併置型駄洒落生成
* マルチモーダル大規模言語モデルに基づく画像に関連する併置型駄洒落生成
* 種表現と文字単位N-gramの音韻類似性を用いた駄洒落認識
* Wikidataを対象としたGPTに基づくエンティティリンキング
* 大規模言語モデルに基づく複数のITS標準規格を横断した類似用語検索システム
* 知識グラフに基づく対話型質問応答データセットを対象としたGPTの質問応答能力の分析

### 2022年度卒業研究テーマ
* VirtualHomeを対象とした日常生活行動説明文からのアクションスクリプト自動生成
* 店舗と商品とレシピ知識グラフに基づくソーシャルロボットを用いた商品棚案内システム
* 人名を対象とした日本語エンティティリンキングの改善
* 常識的知識グラフに基づく理解容易性及びユーモア性を考慮した直喩表現生成
* 常識的知識グラフ及び単語埋め込みを用いた重畳型駄洒落ユーモア認識
* Sentence Transformersに基づく定義文が意味的に類似するITS用語検索システム
* 対話イベント知識グラフに基づくユーザ嗜好を考慮した知識獲得機能を有する雑談音声対話システム
* 汎用言語理解機構における駄洒落認識，生成及び文脈制御に基づく雑談対話システム

### 2021年度卒業研究テーマ
* 画像キャプション生成に基づく描画内容に即した駄洒落文の選択手法
* 重畳型駄洒落ユーモアにおける常識的知識グラフを用いた潜在表現抽出
* 意外性，新規性および具体性を考慮したユーモアを含む直喩表現生成
* PRINTEPSに基づくマルチモーダル対話システム開発支援環境の構築
* 汎用的言語理解フレームワークへのボケ検出機構の統合
* 知識グラフに基づく質問応答におけるエンティティと関係リンキング精度の検証
* DBpediaを対象とした日本語エンティティリンキング
* 大規模知識グラフに基づく知識獲得機能を有する雑談対話システム
* タスク指向型対話システムにおける知識グラフを用いたスロットフィリング支援
* マルチモーダル情報に基づく話者の感情推定とソーシャルロボットの表情選択
* DBpediaに基づく知識グラフの埋め込みを用いたウィキリンクに対応するプロパティ予測

### 2020年度卒業研究テーマ
* 知識グラフ埋め込みを用いたオントロジー構築
* PRINTEPSワークフローからのROS2サービスクライアントコード生成
* 自然言語による知識グラフへの問い合わせにおけるプロパティ同定
* 知識グラフと用例に基づく雑談対話システム
* コンポーネントオントロジーに基づくPRINTEPSワークフロー構築におけるコンポーネント選択支援
* プロセスオントロジーに基づくPRINTEPSワークフロー再利用支援
* マルチモーダル情報に基づくソーシャルロボットの表情生成
* PRINTEPSのためのFurhatモジュール開発
* 統合型対話システムにおける知識グラフを用いたタスク指向性判定