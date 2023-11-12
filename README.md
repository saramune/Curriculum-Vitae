# 職務経歴書
## 基本情報
|key|value|
|---|-----|
|Name|古屋啓介(Keisuke FURUYA)|
|Twitter|[@saramune](https://twitter.com/saramune)|

## 所属
AWS Community Builder: container (2023 ~)

JAWS-UG SRE支部運営 (2022 ~)

## スキル
元・開発エンジニア、現・インフラエンジニア（クラウドonly）なのである程度どちらも見れますが、ここ数年はインフラ寄りなので（趣味でちょこちょこやってるとは言え）開発力は落ちています。
### 使い方を知っていて、最小限の調査で済むもの/本番で運用したことがあるもの
- AWS(EC2, Lambda, RDS, CloudFront, Opensearch, ECS, CodeXXX etc)
- GCP(Cloud Run, GCE, Cloud SQL, Network系)
- Kubernetes(EKS, Argo CD, helmfile)
- IaC(Terraform)
- 英語(reading)
### 大まかな仕組み、使い方、なぜ使うかを知っているもの/個人の趣味で使用したことがあるもの
- Kafka
- HBase
- GCP(GKE, Anthos, Firebase)
- Python
- Go

## 登壇・執筆
- 登壇
  - ACKを活用して使い捨てAWS検証環境を構築している話: https://speakerdeck.com/saramune/ackwohuo-yong-site-shi-ishe-teawsjian-zheng-huan-jing-wogou-zhu-siteiruhua
  - KubernetesとTerraformのセキュリティ/ガバナンス向上委員会 with OPA: https://speakerdeck.com/saramune/gabanansuxiang-shang-wei-yuan-hui-with-opa
  - 夏のAWS Kubernetes祭り！: https://pages.awscloud.com/JAPAN-event-OE-EIB22-WWSO-Compute-Container-20220804-reg-event.html?trk=aws_event_page
  - しくじり先生 on AWS: https://www.youtube.com/watch?v=IQvduOpgF5E
- ブログ
  - Creating Network Load Balancer (SG supported) with AWS Load Balancer Controller: https://dev.to/aws-builders/creating-network-load-balancer-sg-supported-with-aws-load-balancer-controller-168p
  - Managing AWS Resources with ACK and helmfile: https://dev.to/aws-builders/managing-aws-resources-with-ack-and-helmfile-2mo6
  - Google Cloud Batchを使ってバッチの処理待ち時間を1/30以下にしたので紹介させて欲しい: https://tech.delm0.jp/entry/2023/04/11/110000
  - Amazon EventBridgeを使ってChatworkにメッセージを送ってみた: https://creators-note.chatwork.com/entry/2022/09/20/111123

## 資格（だいたい失効）
- AWS認定
  - ソリューションアーキテクト – アソシエイト
  - デベロッパー – アソシエイト
  - システムオペレーション (SysOps) アドミニストレーター – アソシエイト
  - ソリューションアーキテクト - プロフェッショナル
  - DevOpsエンジニア - プロフェッショナル
  - セキュリティ – 専門知識
  - ネットワーク - 専門知識
  - データベース - 専門知識
  - データ・アナリティクス - 専門知識
  - 機械学習 -　専門知識
  - Alexa スキルビルダー – 専門知識
- Google Cloud Certified
  - Associate Cloud Engineer
  - Professional Cloud Architect
  - Professional Cloud DevOps Engineer
  - Professional Cloud Network Engineer

## できること

ここ数年の自分の働き方を振り返ってみて、ひとことでいうと「事業や組織のためになることをなんでもやる」ことをやってきたな、と思います。
- 技術的な側面
  - クラウドインフラ、Kubernetesを中心に扱いつつ開発者の体験をよくするプラットフォームの提供
  - サービスの保守性・可用性を向上させる取り組み
  - チーム横断的なプロジェクトのファシリテート
- ブランド的な側面
  - 各種カンファレンスでの登壇・自社の技術アピール
  - エンジニアサマーインターンシップの運営を行い学生へのアトラクト
- コミュニティ活性化（かつちょっとブランド）的な側面
  - JAWS-UGのオーガナイズ・Community Builderとしての発信
  - 他社のSREさんとコラボしての勉強会開催
そこまで技術力があるわけではないので、技術x楽しいことの仕掛け人の掛け算が強みなのかなと思っています。

## やりたいこと
0→1より1→10が好き。
mogamingさんのことばをかります。

> 自分は特定の技術領域を極めていくスペシャリストになれると思っていません。自分で起業して自分のサービスを立ち上げたいという気持ちもほとんどありません。仕事で成し遂げたいこと、夢みたいなものを強く持っているわけではないと思います。ただ、そういうものを持っている人はかっこいいと思うし、叶えてほしいと思っています。だからこそ、そういった人たちを支えられる人になりたいなと最近思うようになりました。

## 最近気になっていること/ことば

o11y, edge, wasm

## 職務経歴
### 2022/11 - : 副業
 インフラエンジニアとしてクラウド環境の構築、運用、改善を実施しています。
##### 担当業務
- WebアプリケーションのGAEからCloud Runへの移行とterraform化
- バッチ処理のGCEからCloud Runへの移行とterraform化
- Batchを使った画像処理のインフラ基盤構築とCD周りの整備
- BatchとGPUを使った機械学習のインフラ基盤構築
### 2022/02 - : SaaS企業
 インフラエンジニアとしてクラウド環境の構築、運用、監視、改善を実施しています。
##### 担当業務
- 検証環境の改善とPR環境の構築
- ElasticSearchからOpensearchへの移行
- アプリチームを巻き込んでAuroraのバージョンアップ推進
- helmfile、Argo CDを用いたEKSの管理（クラスタ更新や諸改善）
### 2018/07 - 2022/01: クラウドインテグレーター
 インフラエンジニアとしてクラウド環境の構築、およびクラウド環境を用いたシステムの開発を行っています。〜20台ほどの小規模な案件を多数担当し、内訳はEC2+RDSのWebシステムが大多数ですが、ECSによるアプリケーション開発のコンサルティング、W-Aに則った構築支援も実施しました。
##### 担当業務
- 要件定義・インフラ設計・インフラ構築・障害対応
- 要件定義・基本設計・実装・テスト
### 2016/01 - 2018/06: 塾検索メディア運営企業
　Webアプリケーションエンジニアとして、自社メディアのフロントエンド/サーバーサイド開発に従事しました。
#### 社内Data Management Platform開発担当(2017/04-10)
 自社メディアで使用するレコメンドシステムのため、Data Management Platform開発を行いました。レコメンドのデータベースとしてElasticsearchを社内で初めて使用し、その技術調査、設計、APIの開発を担当しました。開発言語はNode.js(Express)で、インフラはすべてAWS上で運用(EC2, Api Gateway, Lambda)しました。
##### 担当業務
- 要件定義・基本設計・詳細設計
- 実装・テスト・リリース・障害対応
#### 自社メディア開発担当(2016/1-)
　Webアプリケーションエンジニアとして、主に要件定義、設計、開発、リリースまで担当しています。開発言語はPHP (CakePHP 2.X)です。開発環境としてはSubversion、Jenkins、Vagrant、MySQLを利用しています。開発環境はクラウドサービスで、本番環境はオンプレミス環境でサービスを運用しています。  
##### 担当業務
- 要件定義・基本設計・詳細設計
- 実装・テスト・リリース・障害対応
- 開発環境改善（selenium環境高速化）
### 2011/04 - 2015/12: 関西大手SIer
　プログラマとして業務系システムの開発、お客様との折衝を行いました。
#### 客先常駐でのプリンタ制御ソフトウェア開発 (2013/10 - 2015/12)
　大手プリンタ開発企業様にて常駐で開発、メンバ管理を行っていました。開発はあまりなく、後輩やパートナーさんの取りまとめ、お客様・オフショアとの調整など管理的な役割が多かったです。
#### 担当業務
- メンバのスケジュール管理
- お客様/オフショアとの折衝
