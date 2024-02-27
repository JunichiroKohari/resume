# 経歴

## 基本情報

|||
|---|---|
|氏名|小針隼一郎（JunichiroKohari）|
|生年月日|1996/03/28|
|居住地|大阪府|
|開発経験|約 5 年|

---

## 保有スキル

- JavaScript + Vue.js / React でのフロントエンド開発
- Laravel(Lumen)、Python での API 開発
- Go、Python でのバッチ開発
- C#での画面、バッチ開発
- ウォーターフォールでの開発経験、アジャイル（スクラム）での開発経験


---

## 実務開発経験

### 言語

![Go](https://img.shields.io/badge/-Go-22272e.svg?logo=go&style=popout-square)
![Python](https://img.shields.io/badge/-Python-22272e.svg?logo=python&style=popout-square)
![PHP](https://img.shields.io/badge/-Php-22272e.svg?logo=php&style=popout-square)
![C#](https://img.shields.io/badge/-c%23-22272e.svg?logo=csharp&style=popout-square)
![JavaScript](https://img.shields.io/badge/-Javascript-22272e.svg?logo=javascript&style=popout-square)
![HTML](https://img.shields.io/badge/-Html5-22272e.svg?logo=html5&style=popout-square)
![CSS](https://img.shields.io/badge/-Css3-22272e.svg?logo=css3&style=popout-square)
![SASS](https://img.shields.io/badge/-SASS-22272e.svg?logo=SASS&style=popout-square)
![LESS](https://img.shields.io/badge/-LESS-22272e.svg?logo=less&style=popout-square)
![pug](https://img.shields.io/badge/-pug-22272e.svg?logo=pug&style=popout-square)

### フレームワーク

![Vue](https://img.shields.io/badge/-Vue.js-22272e.svg?logo=vue.js&style=popout-square)
![Nuxt](https://img.shields.io/badge/-Nuxt.js-22272e.svg?logo=nuxt.js&style=popout-square)
![React](https://img.shields.io/badge/-React-22272e.svg?logo=react&style=popout-square)
![Laravel](https://img.shields.io/badge/-Laravel-22272e.svg?logo=laravel&style=popout-square)
![.NET](https://img.shields.io/badge/-.NET%20Framework-22272e.svg?logo=.NET&style=popout-square)

### インフラ

![AWS](https://img.shields.io/badge/-AWS-22272e.svg?style=popout-square&logo=amazon-aws)
![Docker](https://img.shields.io/badge/-docker-22272e.svg?style=popout-square&logo=docker)
![Linux](https://img.shields.io/badge/-Linux-22272e.svg?logo=linux&style=popout-square)
![Windows Server](https://img.shields.io/badge/-Windows%20Server-22272e.svg?logo=windows&style=popout-square)
![on-premises](https://img.shields.io/badge/-on_premises-22272e.svg?logo=&style=popout-square)

### DB

![PostgresSQL](https://img.shields.io/badge/-PostgreSQL-22272e.svg?logo=postgresql&style=popout-square)
![MySQL](https://img.shields.io/badge/-MySQL-22272e.svg?logo=mysql&style=popout-square)
![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Server-22272e?style=popout-square&logo=microsoft%20sql%20server)
![SQLite](https://img.shields.io/badge/-SQLite-22272e.svg?logo=sqlite&style=popout-square)
![DynamoDB](https://img.shields.io/badge/-DynamoDB-22272e.svg?logo=Amazon%20DynamoDB&style=popout-square)
![ElasticSearch](https://img.shields.io/badge/-ElasticSearch-22272e.svg?logo=elasticsearch&style=popout-square)

### その他

![Git](https://img.shields.io/badge/-Git-22272e.svg?logo=git&style=popout-square)
![GitHub](https://img.shields.io/badge/-GitHub-22272e.svg?logo=github&style=popout-square)
![Bitbucket](https://img.shields.io/badge/-Bitbucket-22272e.svg?logo=bitbucket&style=popout-square)
![AWS CodeCommit](https://img.shields.io/badge/-CodeCommit-22272e.svg?logo=amazon-aws&style=popout-square)
![TFS](https://img.shields.io/badge/-TFS-22272e.svg?logo=tfs&style=popout-square)


---

## 職務経歴詳細

### Y社

- 案件情報

    |||
    |---|---|
    |業種|Web マーケティング|
    |プロダクト|Web 広告成果測定システム|
    |フェーズ|リプレイス|
    |雇用形態|フリーランス|
    |勤務形態|フルリモート|
    |参画期間|2023/03〜2024/03（1 年 1 か月）|
    |規模|全体：40 名程度、チーム：5 名程度|
    |開発手法|ウォーターフォール|
    |担当工程|設計、実装、テスト、保守|

- 担当業務
    - バックエンド
        - バッチ設計、バッチ実装、API 実装、社内ライブラリ改修
        - コードレビュー（バッチ）、テストコード作成
        - バッチ処理ワークフローの AWS アーキテクチャ再設計、再構築（CloudFormation）
            - バッチ処理で利用する ECS のタスク稼働数がクォータ（上限）に達してしまい、その影響でバッチ処理が異常終了する障害が起こっていた。上限に達しないように同時稼働数を抑え、また不要になったタスクはスケールインするようにワークフローを再設計/再構築
            - 仕様上、AWS が提供する ECS のオートスケーリングの仕組みは使えなかったため、自前でオートスケーリングする仕組みを構築
        - 外部 API 連携（Google Ads、Yahoo 検索広告、Yahoo ディスプレイ広告、Facebook、Line、TikTok）
            - 広告閲覧時やコンバージョン（CV)時に取得したデータを各広告媒体に送信するバッチを作成。今季目標月間 100 万 CV×100 アカウント分のデータが遅延なく送信できるよう、流量制限を超えないようにしつつ並行処理によってできるだけ高速で送信できるように実装
    - フロントエンド
        - UI 実装、バグ対応

- 使用技術
    |/|technologies|
    |---|---|
    |言語、FW|![Go](https://img.shields.io/badge/-Go-22272e.svg?logo=go&style=popout-square)![Python](https://img.shields.io/badge/-Python-22272e.svg?logo=python&style=popout-square)![JavaScript](https://img.shields.io/badge/-Javascript-22272e.svg?logo=javascript&style=popout-square)![React](https://img.shields.io/badge/-React-22272e.svg?logo=react&style=popout-square) ...|
    |DB|![PostgresSQL](https://img.shields.io/badge/-PostgreSQL-22272e.svg?logo=postgresql&style=popout-square)![SQLite](https://img.shields.io/badge/-SQLite-22272e.svg?logo=sqlite&style=popout-square) ...|
    |インフラ|![AWS](https://img.shields.io/badge/-AWS-22272e.svg?style=popout-square&logo=amazon-aws)![Docker](https://img.shields.io/badge/-docker-22272e.svg?style=popout-square&logo=docker)![Linux](https://img.shields.io/badge/-Linux-22272e.svg?logo=linux&style=popout-square) ...|
    |その他ツール等|![Git](https://img.shields.io/badge/-Git-22272e.svg?logo=git&style=popout-square)![AdobeXD](https://img.shields.io/badge/-Adobe%20xd-22272e.svg?logo=adobe-xd&style=popout-square)![Figma](https://img.shields.io/badge/-Figma-22272e.svg?logo=figma&style=popout-square)![Slack](https://img.shields.io/badge/-Slack-22272e.svg?logo=slack&style=popout-square)![SonarQube](https://img.shields.io/badge/-SonarQube-22272e.svg?logo=sonarqube&style=popout-square)![Asana](https://img.shields.io/badge/-Asana-22272e.svg?logo=asana&style=popout-square)![GoogleWorkspace](https://img.shields.io/badge/-Google%20Workspace-22272e.svg?logo=google&style=popout-square)![AmazonWorkspaces](https://img.shields.io/badge/-Amazon%20Workspaces-22272e.svg?logo=amazon-aws&style=popout-square) ...|

### N社

- 案件情報

    |||
    |---|---|
    |業種|建設|
    |プロダクト|住宅施工品質マネジメントシステム|
    |フェーズ|新規開発|
    |雇用形態|フリーランス|
    |勤務形態|フルリモート|
    |参画期間|2021/06〜2023/02（1 年 9 か月）|
    |規模|全体：~10 名程度、チーム：5 名程度|
    |開発手法|アジャイル（スクラム）|
    |担当工程|要件擦り合わせ、設計、実装、テスト、保守|

    - 開発チーム発足時に最初期メンバーとして参画し、プロトタイプ開発→RC 版開発→正式版開発→リリース→リリース後の機能追加や運用のところまで参画

- 担当業務

    - バックエンド
        - 技術選定
        - テーブル設計、OpenSearch(ElasticSearch)のマッピング定義、API 設計、バッチ設計、帳票設計
        - API 実装、バッチ実装、性能改善、他システム連携
        - コードレビュー、ユニットテスト（PHPUnit)、結合テスト

    - フロントエンド
        - 技術選定
        - ロジックの設計、UI 実装、API 繋ぎ込み、性能改善、バグ対応
        - オフライン対応
            - 山奥などインターネットが使えない環境でも利用するシーンがあるとのことで、キャッシュを活用して可能な範囲でオフライン環境に対応。PWA 化する用件があったので、Service Worker を利用して PWA をオフラインで動かせるように、Nuxt.js で Workbox を活用して実装
        - コードレビュー、ユニットテスト、結合テスト、E2E テスト（Cypress)

    - その他
        - 新規参画者や若手エンジニアのサポート

- 使用技術
    |/|technologies|
    |---|---|
    |言語、FW|![PHP](https://img.shields.io/badge/-Php-22272e.svg?logo=php&style=popout-square)![Laravel](https://img.shields.io/badge/-Laravel-22272e.svg?logo=laravel&style=popout-square)![Go](https://img.shields.io/badge/-Go-22272e.svg?logo=go&style=popout-square)![Python](https://img.shields.io/badge/-Python-22272e.svg?logo=python&style=popout-square)![JavaScript](https://img.shields.io/badge/-Javascript-22272e.svg?logo=javascript&style=popout-square)![Vue](https://img.shields.io/badge/-Vue.js-22272e.svg?logo=vue.js&style=popout-square)![Nuxt](https://img.shields.io/badge/-Nuxt.js-22272e.svg?logo=nuxt.js&style=popout-square)![Vuetify](https://img.shields.io/badge/-Vuetify-22272e.svg?logo=vuetify&style=popout-square) ...|
    |DB|![PostgresSQL](https://img.shields.io/badge/-PostgreSQL-22272e.svg?logo=postgresql&style=popout-square)![SQLite](https://img.shields.io/badge/-DynamoDB-22272e.svg?logo=Amazon%20DynamoDB&style=popout-square)![ElasticSearch](https://img.shields.io/badge/-ElasticSearch-22272e.svg?logo=elasticsearch&style=popout-square) ...|
    |インフラ|![AWS](https://img.shields.io/badge/-AWS-22272e.svg?style=popout-square&logo=amazon-aws)![Docker](https://img.shields.io/badge/-docker-22272e.svg?style=popout-square&logo=docker)![Linux](https://img.shields.io/badge/-Linux-22272e.svg?logo=linux&style=popout-square) ...|
    |その他ツール等|![Git](https://img.shields.io/badge/-Git-22272e.svg?logo=git&style=popout-square)![Figma](https://img.shields.io/badge/-Figma-22272e.svg?logo=figma&style=popout-square)![Slack](https://img.shields.io/badge/-Slack-22272e.svg?logo=slack&style=popout-square)![GoogleWorkspace](https://img.shields.io/badge/-Google%20Workspace-22272e.svg?logo=google&style=popout-square) ...|

### S社

- 案件情報

    |||
    |---|---|
    |業種|教育|
    |プロダクト|自立学習型能力開発システム（学習塾で利用される、学生向け学習ゲームアプリ）|
    |フェーズ|保守|
    |雇用形態|会社員|
    |勤務形態|出社|
    |参画期間|2021/03〜2021/05（3 か月）|
    |規模|全体：？　名程度、チーム：2 名程度|
    |開発手法|ウォーターフォール|
    |担当工程|詳細設計、実装、テスト、保守|

- 担当業務

    - 学習履歴取得 API、成績ランキング取得 API の設計、実装
    - 成績ランキング（全国、都道府県別、塾別、教室別）取得 SQL チューニング
    - ※他業務（採用活動、新人教育、メールサーバー構築等）と掛け持ち

- 使用技術
    |/|technologies|
    |---|---|
    |言語、FW|![PHP](https://img.shields.io/badge/-Php-22272e.svg?logo=php&style=popout-square)![Laravel](https://img.shields.io/badge/-Laravel-22272e.svg?logo=laravel&style=popout-square) ...|
    |DB|![MySQL](https://img.shields.io/badge/-MySQL-22272e.svg?logo=mysql&style=popout-square) ...|
    |インフラ|![AWS](https://img.shields.io/badge/-AWS-22272e.svg?style=popout-square&logo=amazon-aws)![Linux](https://img.shields.io/badge/-Linux-22272e.svg?logo=linux&style=popout-square) ...|
    |その他ツール等|![Subversion](https://img.shields.io/badge/-subversion-22272e.svg?logo=subversion&style=popout-square)![Eclipse](https://img.shields.io/badge/-Eclipse-22272e.svg?logo=Eclipse&style=popout-square)![GoogleWorkspace](https://img.shields.io/badge/-Google%20Workspace-22272e.svg?logo=google&style=popout-square) ...|

### N社
### 1

- 案件情報

    |||
    |---|---|
    |業種|金融|
    |プロダクト|T 銀行向け銀行口座開設・電子帳票基盤システム|
    |フェーズ|新規開発|
    |雇用形態|会社員|
    |勤務形態|フルリモート|
    |参画期間|2020/05〜2021/02（10 か月）|
    |規模|全体：5 名、チーム：5 名|
    |開発手法|ウォーターフォール|
    |担当工程|設計、実装、テスト、保守|

- 担当業務

    - 画面や帳票生成バッチ、他システム連携バッチの設計、実装、テスト
    - 画面や帳票生成バッチの設計、実装、テスト
    - 他システム連携バッチの設計、実装、テスト

- 使用技術
    |/|technologies|
    |---|---|
    |言語、FW|![C#](https://img.shields.io/badge/-c%23-22272e.svg?logo=csharp&style=popout-square)![.NET](https://img.shields.io/badge/-.NET%20Framework-22272e.svg?logo=.NET&style=popout-square)![JavaScript](https://img.shields.io/badge/-Javascript-22272e.svg?logo=javascript&style=popout-square)![jQuery](https://img.shields.io/badge/-jquery-22272e.svg?logo=jquery&style=popout-square) ...|
    |DB|![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Server-22272e?style=popout-square&logo=microsoft%20sql%20server) ...|
    |インフラ|![Windows Server](https://img.shields.io/badge/-Windows%20Server-22272e.svg?logo=windows&style=popout-square)![vmware](https://img.shields.io/badge/-vmware-22272e.svg?logo=vmware&style=popout-square)![IIS](https://img.shields.io/badge/-IIS-22272e.svg?logo=IIS&style=popout-square) ...|
    |その他ツール等|![TFS](https://img.shields.io/badge/-TFS-22272e.svg?logo=tfs&style=popout-square)![Redmine](https://img.shields.io/badge/-Redmine-22272e.svg?logo=redmine&style=popout-square)![Visual Studio](https://img.shields.io/badge/-VisualStudio-22272e.svg?logo=visual-studio&style=popout-square)![SSMS](https://img.shields.io/badge/-SSMS-22272e.svg?logo=ssms&style=popout-square) ...|

---

### 2

- 案件情報

    |||
    |---|---|
    |業種|金融|
    |プロダクト|E 銀行向け個人ローン申込システム|
    |フェーズ|新規開発|
    |雇用形態|会社員|
    |勤務形態|出社|
    |参画期間|2019/11〜2020/04（6 か月）|
    |規模|全体：5 名、チーム：5 名|
    |開発手法|ウォーターフォール|
    |担当工程|設計、実装、テスト、保守|

- 担当業務

    - 画面や帳票の UI デザイン、設計、実装、テストを担当
    - 銀行員やローン申込者が利用する画面のデザイン、設計、実装、テスト

- 使用技術
    |/|technologies|
    |---|---|
    |言語、FW|![C#](https://img.shields.io/badge/-c%23-22272e.svg?logo=csharp&style=popout-square)![.NET](https://img.shields.io/badge/-.NET%20Framework-22272e.svg?logo=.NET&style=popout-square)![JavaScript](https://img.shields.io/badge/-Javascript-22272e.svg?logo=javascript&style=popout-square)![jQuery](https://img.shields.io/badge/-jquery-22272e.svg?logo=jquery&style=popout-square) ...|
    |DB|![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Server-22272e?style=popout-square&logo=microsoft%20sql%20server) ...|
    |インフラ|![Windows Server](https://img.shields.io/badge/-Windows%20Server-22272e.svg?logo=windows&style=popout-square)![vmware](https://img.shields.io/badge/-vmware-22272e.svg?logo=vmware&style=popout-square)![IIS](https://img.shields.io/badge/-IIS-22272e.svg?logo=IIS&style=popout-square) ...|
    |その他ツール等|![TFS](https://img.shields.io/badge/-TFS-22272e.svg?logo=tfs&style=popout-square)![Redmine](https://img.shields.io/badge/-Redmine-22272e.svg?logo=redmine&style=popout-square)![Visual Studio](https://img.shields.io/badge/-VisualStudio-22272e.svg?logo=visual-studio&style=popout-square)![SSMS](https://img.shields.io/badge/-SSMS-22272e.svg?logo=ssms&style=popout-square) ...|


---

### 3

- 案件情報

    |||
    |---|---|
    |業種|金融|
    |プロダクト|F 銀行向け営業支援システム|
    |フェーズ|保守|
    |雇用形態|会社員|
    |勤務形態|出社|
    |参画期間|2019/04〜2019/10（7 か月）|
    |規模|全体：3 名、チーム：3 名|
    |開発手法|ウォーターフォール|
    |担当工程|保守|

- 担当業務

    - ポータルサイトの改修、CRM の改修を担当
    - ポータルサイト画面改修（SharePoint）、ユニットテスト
    - Microsoft Dynamics CRM と SharePoint によるポータルサイトとの連携バッチ実装、ユニットテスト

- 使用技術
    |/|technologies|
    |---|---|
    |言語、FW|![C#](https://img.shields.io/badge/-c%23-22272e.svg?logo=csharp&style=popout-square)![.NET](https://img.shields.io/badge/-.NET%20Framework-22272e.svg?logo=.NET&style=popout-square)![JavaScript](https://img.shields.io/badge/-Javascript-22272e.svg?logo=javascript&style=popout-square)![jQuery](https://img.shields.io/badge/-jquery-22272e.svg?logo=jquery&style=popout-square) ...|
    |DB|![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Server-22272e?style=popout-square&logo=microsoft%20sql%20server) ...|
    |インフラ|![Windows Server](https://img.shields.io/badge/-Windows%20Server-22272e.svg?logo=windows&style=popout-square)![vmware](https://img.shields.io/badge/-vmware-22272e.svg?logo=vmware&style=popout-square)![IIS](https://img.shields.io/badge/-IIS-22272e.svg?logo=IIS&style=popout-square) ...|
    |その他ツール等|![TFS](https://img.shields.io/badge/-TFS-22272e.svg?logo=tfs&style=popout-square)![Redmine](https://img.shields.io/badge/-Redmine-22272e.svg?logo=redmine&style=popout-square)![Visual Studio](https://img.shields.io/badge/-VisualStudio-22272e.svg?logo=visual-studio&style=popout-square)![SSMS](https://img.shields.io/badge/-SSMS-22272e.svg?logo=ssms&style=popout-square)![Microsoft SharePoint](https://img.shields.io/badge/-Microsoft_Sharepoint-22272e.svg?logo=microsoft-sharepoint&&style=popout-square)![Microsoft DynamicsCRM](https://img.shields.io/badge/-Microsoft_DynamicsCRM-22272e.svg?logo=microsoft-dynamicscrm&&style=popout-square) ...|

### P社 2019/01〜2019/03（3か月）

<details>
  <summary>詳細</summary>

- 案件情報

    |||
    |---|---|
    |業種|電気|
    |プロダクト|太陽光発電ソーラーパネル管理システム|
    |フェーズ|保守|
    |雇用形態|アルバイト|
    |勤務形態|出社|
    |参画期間|2019/01〜2019/03（3 か月）|
    |規模|全体：?名、チーム：3 名|
    |開発手法|ウォーターフォール|
    |担当工程|保守|

- 担当業務

    - フロントエンドの実装、ユニットテストを担当
    - UI 改修、バグ対応

- 使用技術
    |/|technologies|
    |---|---|
    |言語、FW|![Vue](https://img.shields.io/badge/-Vue.js-22272e.svg?logo=vue.js&style=popout-square)![JavaScript](https://img.shields.io/badge/-Javascript-22272e.svg?logo=javascript&style=popout-square) ...|

</details>

### R社 2018/11〜2018/12（2か月）

<details>
  <summary>詳細</summary>

- 案件情報

    |||
    |---|---|
    |業種|不動産|
    |プロダクト|賃貸ガレージ（トランクルーム）管理システム|
    |フェーズ|保守、運用|
    |雇用形態|アルバイト|
    |勤務形態|出社|
    |参画期間|2018/11〜2018/12（2 か月）|
    |規模|全体：?名、チーム：3 名|
    |開発手法|ウォーターフォール|
    |担当工程|運用|

- 担当業務

    - 保守・運用担当
    - 銀行統廃合による、お客様の請求口座更新 SQL 作成
    - 顧客、物件データメンテナンス

- 使用技術
    |/|technologies|
    |---|---|
    |言語、FW|SQL|
    |DB|![PostgresSQL](https://img.shields.io/badge/-PostgreSQL-22272e.svg?logo=postgresql&style=popout-square)|

</details>