# 職務経歴書

## 基本情報

|key|value|
|---|-----|
| Name | 高橋 一騎 (Takahashi Ikki)|
| Blog | [お？意外といけるやん！](https://www.ikkitang1211.site/) |
| Github | [TakahashiIkki](https://github.com/TakahashiIkki) |
| SpeakerDeck | [TakahashiIkki](https://speakerdeck.com/TakahashiIkki) |
| Twitter | [@ikkitang](https://twitter.com/ikkitang) |
| Qiita | [ikkitang](https://qiita.com/ikkitang) |
| Zenn | [ikkitang](https://zenn.dev/ikkitang) |

## スキル

### 言語やフレームワーク

- PHP
  - 実務経験 5年
    - 5.3 ~ 7.3
    - CakePHP2.x および 3.x (3.xは2.xからリファクタリングした)
    - CodeIgniter 2.x および 3.x (3.xは2.xからリファクタリングした)
- Python
  - 実務経験 3年
    - 3.6
    - Django Rest Framework
- JavaScript
  - 実務経験 5年
  - Webpackを使うなどの今風ではなくて、管理画面から実行するJSを書いたり、既にあるものに対して修正する程度
  - jQuery 実務経験 2年
  - Vue.js 2.x 実務経験 1年
  - AngularJS(1.0) 実務経験 1年
    - MonacaというソフトウェアでiOS・Androidのクロスプラットフォーム開発をやっていた
  - React 実務経験 ほぼ無し
    - Reactを使ったSPAサイトの構築の際にテックリードとして在籍
    - フロントのAPIを改修する程度は行った
- VB.net (VB6, VB Access)
  - 実務経験 2年
    - 新卒で採用された会社でやっていた

### OSS

- PostgreSQL
  - 実務経験 3年
    - 10.x ~ 11.x
  - [日本PostgreSQLユーザー会](https://www.postgresql.jp/) の理事として勉強会を開催しています
  - データベースリファクタリング経験有り
    - [PostgreSQL Conference Japan 2018 に参加&異種DB移行プロジェクトについて登壇させて頂いた。](https://www.ikkitang1211.site/entry/pgconf18j)
- MySQL
  - 実務経験 5年
    - 5.5 ~ 5.7
    - Amazon Aurora 1.x 
- Terraformm
  - 実務経験 半年
    - PHP Webアプリケーションのサーバー構築
      - CloudFront - ALB - TargetGroup - ECS on Fargate
      - AutoScalingの設定
    - WebSocketアプリケーションのサーバー構築
      - ALB - TargetGroup - ECS on Fargate
      - AutoScalingの設定
- MemCached / Redis
  - 実務経験 2年
  - キャッシュ・セッション用 ストレージとしてぐらい

### サービス

- Github
  - [プロジェクトボード](https://docs.github.com/ja/free-pro-team@latest/github/managing-your-work-on-github/about-project-boards) を用いた開発経験がある
    - 上記で `レビュー待ち` 中のPRをSlackに連携するツールをGithubAPIを用いて開発した
    - [オミカレを支えるチーム開発 ~プロダクトを支える文化~/phpconference-sendai2019-omicale?slide=58](https://speakerdeck.com/takahashiikki/phpconference-sendai2019-omicale?slide=58)
- Backlog
- CircleCI
  - ビルドをして AWS ECR に配置する経験あり

### その他

- Git
- Docker

## 強み

- テックリードとして10名以下のチームに在籍していた経験もあり、メンバーと月1で1on1をやっていたなどのリーダーシップを持ってるのは強み
- DBリファクタリングやアプリケーションのリファクタリングやリアーキテクトの経験があるので、リファクタリングなどのシステム立て直しなどには強みがある
  - オミカレ社での経験
    - [技術的負債を徹底的に解消した話 - オミカレのシステムフル刷新のためにやったことを全部教える](https://employment.en-japan.com/engineerhub/entry/2020/04/09/103000)
  - エクシードシステム株式会社での経験
    - Windowsデスクトップで動いていたツールをWebアプリケーション化
    - CakePHP2系で動いてたのを3系にリファクタリング
- 既にある有りものをより良く改善する `マイナスをゼロにする` とか `10を50にする` とかの領域に強みをもっている

## やったことはないが興味があるもの

- コンパイラ言語をプライベート以外でやった事無いので、やりたい

## 職務経歴

### 2018/05 - 現在 : 株式会社オミカレ

婚活パーティーのポータルサイトをやっている会社です。

#### 主な社内での業務、その変遷

軸はバックエンド領域でしたが、スタートアップという性質上、業務としては幅広く データベースリファクタリングの為にDBに手を加えたり
AWSのインフラの設計や実際に作っていったり色々なことをやりました。

入社当初に居たCTOが退職後、テックリードというポジションを用意してもらってチームマネジメントもやっていました。
技術領域は自分の方でリードしつつ、手も動かすというプレイングマネージャー的な形でした。

#### この職場の振り返り

- ちゃんと仕事のやり方を学べた職場だった
  - 前職は遅れは残業でハードワークでカバーするという感じだったけど、そうならないように見積もりをちゃんとする事だったり効率的にコーディングが出来るような自分の中での感覚を磨けていった感覚があります。
- 何となく独学で知っていた事をよりちゃんと実践出来た気がした。 
  - AWSも雰囲気で触ってたけど、初めてコードで管理をする中で「こうなっているのか」という学びがあった。
  - PostgreSQLも何となくしってたけど、MySQLからPostgreSQLに移行していく中でより具体的に各DBの違いも理解出来た。
- よりメンテナブルでテスタブルなコードが書けた。
  - 前職(エクシードシステム株式会社)は営業の力が極端に強い会社だったので、こういう要望は来るよな、という想定できる経験が多くあった。
  - コーディングをしていく中で予め変更に強くなるように切り出すなどを実践出来た

#### 具体的なプロジェクト

##### AWS DMSを用いたDBのリファクタリングプロジェクト

- 期間： 2018/05 ~ (現在)
- やった事の詳細はブログやカンファレンスでの登壇を行いました
  - [PostgreSQL Conference Japan 2018 に参加&異種DB移行プロジェクトについて登壇させて頂いた](https://www.ikkitang1211.site/entry/pgconf18j)
  - [MySQLからPostgreSQLへの移行とDBリファクタリング](https://speakerdeck.com/takahashiikki/postgresqljapan2018)
- 主な業務内容
  - リファクタリング後のDB設計
  - リファクタリング処理の開発
  - リファクタリングを進める為のAPI開発・設計
- 使用言語
  - Python (Django)
- 使用ツール
  - RDS (PostgreSQL,MySQL)
  - pl/v8 (PostgreSQLのトリガーをJSで書く事が出来るようになる)
  - AWS DMS(Database Migration Service)

##### アプリのリリースマネジメント

- 期間： 2018/05 ~ (現在)
- 自社発のアプリ開発について、外部リソースのマネジメント含めて保守を行っていきました。
  - [日本最大級の婚活パーティー情報サイトのオミカレ！スマートフォン向けアプリをリリース！](https://prtimes.jp/main/html/rd/p/000000016.000020019.html)
- 主な業務内容
  - アプリから実行されるAPIの開発・設計
  - アプリを開発する委託会社への要件調整
- 使用言語
  - Python (Django)
- 使用ツール
  - RDS (PostgreSQL,MySQL)
  - pl/v8 (PostgreSQLのトリガーをJSで書く事が出来るようになる)
  - AWS DMS(Database Migration Service)

##### サイトフルリニューアル

- 期間： 2019/03 ~ 2019/06
- 当時やっていた事はエンジニアHubに寄稿という形でアウトプットしております。
  - [技術的負債を徹底的に解消した話 - オミカレのシステムフル刷新のためにやったことを全部教える](https://employment.en-japan.com/engineerhub/entry/2020/04/09/103000)
- 主な業務内容
  - フルリニューアル後の開発基盤の開発
  - バックエンド側のアプリケーションの開発・設計
- 使用言語
  - PHP (CodeIgniter)
- 使用ツール
  - Docker (開発環境で採用、ECS Fargateで本番環境で導入)

##### オミカレ新規プロジェクト(ビデオチャット)の立ち上げ

- 期間： 2020/05 ~ 2020/11
- 主な業務内容
  - インフラの設計・開発
  - データベースの設計・保守
  - バックエンド側のアプリケーションの開発・設計
  - バックエンドから実行されるAPIの開発・設計
  - インフラの保守
- 使用言語
  - PHP (CodeIgniter)
  - Python (Django)
- 使用ツール
  - Terraform (AWSのリソース管理)
  - Ansible (APIのリリース作業)

##### オミカレ本体サイトの開発保守

- 期間： 2018/05 ~ (現在)
- 主な業務内容
  - バックエンド側のアプリケーションの開発・設計
  - バックエンドから実行されるAPIの開発・設計
  - データベースの設計・保守
  - インフラの保守
- 使用言語
  - PHP (CodeIgniter)
  - Python (Django)
- 使用ツール
  - Terraform (AWSのリソース管理)
  - Ansible (APIのリリース作業)

### 2013/04 - 2018/04 : エクシードシステム株式会社

理美容、エステ業を行っている会社へ顧客管理+集計分析システムとしてのSalonMagicというサービスを開発している会社。

元々はWindowsデスクトップアプリケーションを開発して提供していましたが、2015年下旬頃を境に社内初のスマートフォンアプリの展開を開始。
また、2018年に元々あったデスクトップアプリケーションをフルクラウド化する、というサービス展開をしました。

#### 主な社内での業務、その変遷

私はエンジニアという立場から、Windows環境で動作するデスクトップアプリケーションの制作を歴て、
上記と連携するスマートフォンアプリの立ち上げプロジェクトやコーディング業務を一人で担ってローンチを行いました。

その後、開発主任という立場でスマートフォンアプリのグロースを行いつつ、
社内のデスクトップアプリケーションのクラウド化にリードエンジニアとして携わりました。

#### この職場の振り返り

- 未経験で新卒エンジニアとして雇って頂きましたが、最終的に 開発主任のPOSTとして開発基盤の整備とかまでやらせてもらいました。
- バグを出して怒られることもしばしばありましたが、まずやってみよう、という精神を評価してもらえたな、と思っています。
- 自分よりも社内で経験豊富なエンジニアの方が居るにも関わらず、初めての会社の存続を掛けたような一大プロジェクトについて「高橋に任せてみよう」と会議で上司が提案してくれたらしく、そこは誇りに思える事だと思っています。

#### 具体的なプロジェクト

##### Posレジ社内アプリケーションの制作

- 期間： 2013/04 〜 2016/01 
- [Windows デスクトップアプリケーション](https://www.exceed-system.co.jp/salonmagic/) の開発業務
  - 使用言語
    - VB.net
    - VB6
    - MS Access

##### 予約管理、スマートフォンアプリケーションの制作

- 期間: 2016/01 〜 2018/04
- 以下、2つのスマートフォンアプリの設計・開発業務を行いました
  - [PocketSalon - GooglePlay](https://play.google.com/store/apps/details?id=jp.co.exceedsystem.pocketsalon&hl=ja)
  - [PocketSalon - AppStore](https://apps.apple.com/jp/app/pocket-salon/id1063227076)
- 主な業務内容
  - APIの開発・設計
  - スマートフォンアプリの開発・設計
  - ローンチ後の開発保守
  - ５名以下のチームのタスクマネジメント
  - オンプレサーバーの運用保守
- 使用言語
  - スマートフォンアプリ側
    - JavaScript(AngularJS)
  - API側
    - PHP (CakePHP)
  - 管理画面
    - PHP (CakePHP)
    - JavaScript (jQuery/Vue.js)
- 使用ツール
  - [Monaca](https://ja.monaca.io/)

##### 顧客管理・分析システムのWebアプリケーションリプレース業務

- 期間: 2017/04 〜 2018/04
- 以下のプロダクトの開発を行いました
  - [SalonAnswer](https://ex.salonanswer.com/)
- 主な業務内容
  - Webアプリケーションについてコーディング基盤の開発・設計
  - Webアプリケーションの開発・設計
  - 多種社内サービスとのデータ連携基盤の開発・設計
- 使用言語
  - バックエンド
    - PHP (CakePHP)
  - フロントエンド
    - JavaScript (jQuery/Vue.js)
- 使用ツール
  - AWS

## 登壇歴

- 2015~2019
  - [オープンセミナー岡山2015](https://oso-web.doorkeeper.jp/events/42344)
  - [中国地方DB勉強会](https://dbstudychugoku.connpass.com/) 
    - [設計をする上で役にたった制約について](https://speakerdeck.com/takahashiikki/she-ji-wosurushang-teyi-nitatutazhi-yue-nituite)
    - [7年振りの大型アップデート_PostgreSQL10とは](https://speakerdeck.com/takahashiikki/7nian-zhen-rifalseda-xing-atuhuteto-postgresql10toha)
  - [岡山モバイルアプリ開発勉強会](https://okmoku.connpass.com/) 
- 2020
  - [2020-01-25 第28回 中国地方DB勉強会](https://dbstudychugoku.connpass.com/event/158127/) 
    - [PostgreSQL12 新機能ご紹介](https://speakerdeck.com/takahashiikki/chugokudb28-1)

### 社外プロジェクト

- [日本PostgreSQLユーザー会](https://www.postgresql.jp/))
  - 期間: 2017/06 ~ (現在)
  - NPOのPostgreSQLのユーザー会の理事として、中国地方支部長という役職で活動をしています
  - [中国地方DB勉強会](https://dbstudychugoku.connpass.com/) を年4回とかのスパンで開催しています。

### 執筆歴

- [技術的負債を徹底的に解消した話 - オミカレのシステムフル刷新のためにやったことを全部教える](https://employment.en-japan.com/engineerhub/entry/2020/04/09/103000)
