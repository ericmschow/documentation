---
title: イベントのポスト
type: apicontent
order: 12.1
external_redirect: '/api/#post-an-event'
---
## イベントのポスト
このエンドポイントを使用して、イベントをストリームにポストできます。イベントにタグ付けし、優先度を設定し、他のイベントと統合します。

##### 引数
* **`title`** [必須]:
    イベントのタイトル。上限は 100 文字です。
    [Datadog Ruby ライブラリ][1]では、`msg_title` を使用してください。
* **`text`** [必須]:
    イベントの本文。上限は 4000 文字です。
    テキストは[マークダウン][2]をサポートしています。
    [Datadog Ruby ライブラリ][1]では、`msg_text` を使用してください。
* **`date_happened`** [オプション、default = **現在**]:
    イベントの POSIX タイムスタンプ 整数として (引用符なしで) 送信する必要があります。1 年と 24 日 (389 日) 以内のイベントに制限されます。
* **`priority`** [オプション、デフォルト = **normal**]:
    イベントの優先度。**normal** か **low** のいずれか。
* **`host`** [オプション、デフォルト = **None**]:
    イベントに関連付けるホスト名。ホストに関連付けられているタグがあれば、それらもこのイベントに適用されます。
* **`tags`** [オプション、デフォルト = **None**]:
    イベントに適用するタグのリスト。
* **`alert_type`** [オプション、デフォルト = **info**]:
    アラートイベントの場合は、**error**、**warning**、**info**、**success** のいずれかのタイプを設定します。
* **`aggregation_key`** [オプション、デフォルト = **None**]:
    集約に使用する任意の文字列。上限は 100 文字です。
    キーを指定した場合は、そのキーを使用するすべてのイベントがイベントストリーム内でグループ化されます。
* **`source_type_name`** [オプション、デフォルト = **None**]:
    ポストされるイベントのタイプ。
    オプションには、**nagios**、**hudson**、**jenkins**、**my_apps**、**chef**、**puppet**、**git**、**bitbucket** などがあります。
    [ソース属性値のリストはこちら][3]を参照してください。
* **`related_event_id`** [オプション、デフォルト = **None**]:
    親イベントの ID。整数として (引用符なしで) 送信する必要があります。
* **`device_name`** [オプション、デフォルト = **None**]:
    イベントのポストに使用するデバイス名のリスト。

[1]: https://github.com/DataDog/dogapi-rb
[2]: /ja/graphing/event_stream/#markdown-events
[3]: /ja/integrations/faq/list-of-api-source-attribute-value