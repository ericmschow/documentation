---
title: モニターの詳細の取得
type: apicontent
order: 26.02
external_redirect: /api/#get-a-monitor-s-details
---

## モニターの詳細の取得
##### 引数
* **`group_states`** [オプション、デフォルト = **None**]:
    この引数を設定すると、指定したグループ状態に関する追加情報があれば、それを含むデータが返されます。たとえば、最後の通知タイムスタンプ、最後の解決タイムスタンプ、モニターがトリガーした最後の時間などです。この引数は、どのグループ状態を追加するかを含む文字列リストを指定します。**all**、**alert**、**warn**、**no data** から 1 つ以上を選択します。例: 'alert,warn'"
