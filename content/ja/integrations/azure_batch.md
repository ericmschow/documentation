---
categories:
  - cloud
  - configuration & deployment
  - azure
ddtype: クローラー
dependencies: []
description: Azure Batch Services のキーメトリクスを追跡
doc_link: 'https://docs.datadoghq.com/integrations/azure_batch/'
git_integration_title: azure_batch
has_logo: true
integration_title: Microsoft Azure Batch
is_public: true
kind: インテグレーション
manifest_version: '1.0'
name: azure_batch
public_title: Datadog-Microsoft Azure Batch インテグレーション
short_description: Azure Batch Services のキーメトリクスを追跡
version: '1.0'
---
## 概要
Azure Batch Service は、Azure アプリケーション用のマネージド型のタスクスケジューラーおよびプロセッサーです。

Azure Batch Service からメトリクスを取得すると、以下のことができます。

* Batch アカウントのパフォーマンスを視覚化できます。
* Batch アカウントのパフォーマンスをアプリケーションと関連付けることができます。

## セットアップ
### インストール

[Microsoft Azure インテグレーション][1]をまだセットアップしていない場合は、最初にセットアップします。これ以外に必要なインストール手順はありません。

## 収集データ
### メトリクス
{{< get-metrics-from-git "azure_batch" >}}


### イベント
Azure Batch Service インテグレーションには、イベントは含まれません。

### サービスのチェック
Azure Batch Service インテグレーションには、サービスのチェック機能は含まれません。

## トラブルシューティング
ご不明な点は、[Datadog のサポートチーム][2]までお問合せください。



{{< get-dependencies >}}
[1]: https://docs.datadoghq.com/ja/integrations/azure
[2]: https://docs.datadoghq.com/ja/help
