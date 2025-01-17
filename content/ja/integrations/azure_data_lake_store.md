---
aliases:
  - /ja/integrations/azure_datalakestore
categories:
  - クラウド
  - azure
ddtype: クローラー
dependencies: []
description: Azure Data Lake Store のキーメトリクスを追跡
doc_link: 'https://docs.datadoghq.com/integrations/azure_data_lake_store/'
git_integration_title: azure_data_lake_store
has_logo: true
integration_title: Microsoft Azure Data Lake Store
is_public: true
kind: インテグレーション
manifest_version: 1
name: azure_data_lake_store
public_title: Datadog-Microsoft Azure Data Lake Store インテグレーション
short_description: Azure Data Lake Store のキーメトリクスを追跡
version: 1
---
## 概要

Azure Data Lake Store は、ビッグデータ分析を可能にする無制限のデータレイクです。

Datadog Azure インテグレーションを使用して、Data Lake Store からメトリクスを収集できます。

## セットアップ
### インストール

[Microsoft Azure インテグレーション][1]をまだセットアップしていない場合は、最初にセットアップします。これ以外のインストール手順はありません。

## 収集データ
### メトリクス
{{< get-metrics-from-git "azure_data_lake_store" >}}


### イベント
Azure Data Lake Store インテグレーションには、イベントは含まれません。

### サービスのチェック
Azure Data Lake Store インテグレーションには、サービスのチェック機能は含まれません。

## トラブルシューティング
ご不明な点は、[Datadog のサポートチーム][3]までお問合せください。

[1]: https://docs.datadoghq.com/ja/integrations/azure/
[2]: https://github.com/DataDog/dogweb/blob/prod/integration/azure_data_lake_store/azure_data_lake_store_metadata.csv
[3]: https://docs.datadoghq.com/ja/help/


{{< get-dependencies >}}