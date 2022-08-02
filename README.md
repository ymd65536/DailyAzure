# 毎日Azure

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

##　6日目

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
