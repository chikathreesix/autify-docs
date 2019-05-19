# APIドキュメント

## パーソナルアクセストークンの使い方

API を認可するには Authorization ヘッダーにパーソナルアクセストークンを含めて使用します：

```
curl -H "Authorization: Bearer PERSONAL-ACCESS-TOKEN" https://app.autify.com/api/v1
```

## スケジュール API

スケジュールを実行開始します。

```
POST /schedules/:id
```

### パラメータ：

- `id` （必須）- 認可されたユーザーが所有するスケジュールの ID。この ID は URL から見つけることができます。 `https://app.autify.com/projects/<:project_id>/schedules/<:id>`

![](https://paper-attachments.dropbox.com/s_4D4D0D734A035220AE5A2053120BC0FB57F2BB2E117D5B16B3FAB4EB5D6E22D2_1557720980763_Screen+Shot+2019-05-13+at+13.16.01.png)
