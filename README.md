# 毎日Azure

## 29日目

Azure Stream Analytics はリアルタイムな分析サービスです。
1秒未満の遅延で何百万ものイベントを分析できる弾力性と
カスタムコードの利用で高度なユースケースにも対応できる拡張性があります。
99.9% の可用性があり、厳しいワークロードにも耐えられる特徴があります。

## 28日目

Azure Time Series Insights(TSI)はIoTのデータ分析と視覚化に特化したサービスです。
データの蓄積やクエリの実行、データの視覚化を実行できます。
セットアップ方法はTSIのリソースを作成後、既存のIoT HubかEvent Hubs をイベントソースとするように設定するだけです。

## 27日目

Azure Service Health は現在利用中のサービスの状況が確認できます。
リージョン内で稼働しているサービスの正常性や次のメンテナンス予定日をダッシュボードを通して確認できます。

## 26日目

Azure Advisor はAzureの環境および存在するリソースをスキャンし、アドバイスを提供する機能です。
Azureを使用する上でのコンサルタントとして機能します。
スキャンした結果からマイクロソフトからの推奨事項を返します。

## 25日目

〜Azure IoT Hub(IoT Hub)とデバイス間の通信プロトコル〜

IoT HubはIoTでMQTTやAMQP、HTTPSといった複数の通信プロトコルに対応しています。
また、通信方向としてDevice To CloudとCloud To Device にそれぞれ対応しています。

## 24日目

Azure IoT Hub(IoT Hub)は物理世界にあるデバイスと各種Azureサービスとの間でデータの中継(Broker)を担うサービスです。
IoT Hubは数百万のデバイスから送信される数十億のデータを処理できるように設計されています。

## 23日目

Azure Cognitive Servicesはすぐに利用できる汎用的なAIサービスです。
Cognitive Servicesには複数のAPIが存在し、主に5つのカテゴリに分類されます。
APIを利用する場合はCognitive Services SDKから呼び出して利用します。

## 22日目

Azure DatabricksはApache Spark ベースのデータ分析プラットフォームです。
Azure Data Lake Storage にあるデータを元に分析を実行します。PaaS環境で手軽にデータ分析を実行できる上に必要に応じてスケーリングを実行します。

## 21日目

Azure Table Storage はNoSQL型のデータストアです。
Azure Table Storage はCosmos DBより構造が単純な為、比較的容易に利用できます。
また、NoSQLのサービスであるゆえにスキーマの定義を必要としません。

## 20日目

Azure Bot Service は人間のようにコンピューターが振る舞うことで質問応答などをチャットボットに任せることができるサービスです。
既に構築済みのAIを利用することで高度な受け答えやQAサイトの構成をノーコードで実現できます。

## 19日目

Azure DDoS Protection は DDoS攻撃からシステムを保護する監視サービスです。
利用プランにはBasicとStandard があり、DDoS Protection Standard には、DDoS 迅応サポートが含まれています。

## 18日目

Azure Virtual Desktop (旧称 Windows Virtual Desktop)、AVDはAzure上で仮想デスクトップ(VDI)環境を利用できるサービスです。
通常、VDI環境を構築するためには専用のインフラを構築する必要があります。

AVDはインフラ環境を管理してくれるという大きな特徴があります。

## 17日目

Azure Alertはあらかじめ設定したしきい値を超えた場合に指定したアクションを実行できるサービスです。
Azure Alertではスコープ、条件、アクショングループ、詳細の4つの内容から警告を発生させるルールを作ります。

## 16日目

Azure Container Instances(ACI) はDocker コンテナ技術をAzure上に実装したサービスです。
コンテナイメージはAzure Container Registry(ACR)に保存します。
ACIを利用するとAzure上で仮想マシンを管理せずにコンテナーを簡単に実行できます。

## 15日目

Azure Static Web Appsはサーバレスな開発環境高速に構築してすぐにWebアプリをデプロイできるフルスタックなサービスです。
様々なフロントエンドフレームワークに対応しています。

## 14日目

Azure WAF(Web Application Firewall)はWebアプリケーションの脆弱性への攻撃に対するセキュリティソリューションです。
Azure WAFは、SQLインジェクション攻撃やXSS攻撃などの攻撃からアプリケーションを保護します。

## 13日目

Azure Bastion(バスティオン)とはブラウザとAzurePortalを経由して仮想マシンに接続できるようにするサービスです。
Bastionを経由して仮想マシンに対するRDP接続やSSH接続が利用できます。

https://docs.microsoft.com/ja-jp/azure/bastion/bastion-overview

## 12日目

Azure Resource Manager(ARM) はAzure内にあるリソースの作成・更新・削除の役割を果たすマネージドサービスです。
Azureは様々な管理インターフェイスでリソースを管理できますが、各インターフェイスからの実行はこのARMを経由して実行されます。

## 11日目

AzureFunctions はサーバの準備やミドルウェアの実行環境の管理が不要なサーバレス環境です。FaaSの一つでもあります。
関数名、ランタイム、地域、ベースとなるOS、料金プランを選択したらあとはソースコードをアップするだけで実行できます。

## 10日目

ExpressRouteは特定の通信回線事業者が提供する閉域網を利用してオンプレミスネットワークとAzure上のネットワークをつなぐサービスです。
高速で遅延の小さい安全な通信を最大で100Gbpsの帯域幅で利用できます。
利用には別途、ネットワークサービスプロバイダとの契約が必要です。

## 9日目

〜テナントとサブスクリプション〜

テナントは組織単位で作成するアカウントのことであり
Azure ADで管理されます。
サブスクリプションを契約するにはテナントが必要です。サブスクリプションはAzureの契約を行う単位で請求はサブスクリプションを通して管理します。

## 8日目

AzureはGUIだけでなくコマンドラインベースでコマンドを実行することもできます。
具体的にはAzure PowerShellやAzure CLIがあります。
Azureを操作できるAzureポータルにはAzure Cloud Shell というWebベースのターミナルもあり、BashまたはPowerShellでリソースを操作できます。

## 7日目

Azure Cosmos DBは半構造化データを扱うことができるNoSQLデータベースサービスです。
マルチマスター構成の為、複数のリージョンに同時にデータを書き込むことが可能です。
Azure Cosmos DBの特徴は次のとおりです。(図)

## 6日目

Azure Storageには複数の冗長オプションがあります。
冗長オプションはストレージサービスによって利用できるオプションが異なります。
例えば、Azure Disk StorageではLRSとZRSに対応しています。

https://azure.microsoft.com/ja-jp/updates/zone-redundant-storage-zrs-for-azure-disk-storage-now-generally-available/
https://azure.microsoft.com/en-us/blog/improve-availability-with-zoneredundant-storage-for-azure-disk-storage/
https://docs.microsoft.com/ja-jp/azure/virtual-machines/disks-redundancy#zone-redundant-storage-for-managed-disks

## 5日目

Azure StorageはAzureのストレージサービスで、以下の種類のデータサービスがあります。
(図)
Azure Storageには複数の冗長オプションがあり、高い耐久性を実現することができます。

## 4日目

Azure Virtual Machinesは仮想化技術によって物理サーバ上に構築された仮想マシンを提供するサービスです。
ハイパーバイザーを利用して複数のOSを稼働させます。
Azure Virtual Machinesの特徴は次のとおりです。(図)

## 3日目

Azure SQL DatabaseはSQL Serverをベースとしたフルマネージドなデータベースサービスです。
99.9%の可用性があり、同じデータセンターで異なる3台の物理サーバー上で稼働します。
また、Geoレプリケーションにより可用性を担保できます。

## 2日目

Azure Firewall は、Azure 上で実行されるステートフルなファイアウォールです。
Azure FirewallにはStandard とPremium 2つのSKUがあります。

## 1日目

Azure Virtual Network(VNet)はAzure内に作成する仮想プライベートネットワークです。
VNetにより仮想マシンや他のリソースと接続が可能となります。
また、VNet内のトラフィックを制御する方法としてNSGとASGがあります。
