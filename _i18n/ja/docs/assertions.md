# 利用できるアサーション

## ページを対象としたアサーション

| キーワード名                | 概要                                        | 引数        |
| --------------------------- | ------------------------------------------- | ----------- |
| Page Should Contain Element | ページに要素が存在することを確認する        | HTML 要素   |
| Title Should Be             | ページタイトルが一致することを確認する      | 文字列      |
| Location Should Be          | 現在の URL が文字列と一致することを確認する | 文字列(URL) |
| Location Should Contain     | 現在の URL が文字列を含むことを確認する     | 文字列(URL) |

## 要素を対象としたアサーション

| キーワード名                        | 概要                                                                 | 対象となる要素の種類 | 引数                                                                      |
| ----------------------------------- | -------------------------------------------------------------------- | -------------------- | ------------------------------------------------------------------------- |
| Element Should Be Visible           | 要素が目視できることを確認する                                       | なし                 | 全て                                                                      |
| Element Should Not Be Visible       | 要素が見えないことを確認する                                         | なし                 | 全て                                                                      |
| Element Text Should Be              | 要素のテキストが文字列と一致することを確認する                       | 文字列               | 全て                                                                      |
| Element Should Contain              | 要素が文字列を含むことを確認する                                     | 文字列               | 全て                                                                      |
| Element Should Not Contain          | 要素が文字列を含まないことを確認する                                 | 文字列               | 全て                                                                      |
| Element Should Be Enabled           | 要素が有効であることを確認する                                       | なし                 | `button`, `input`, `select`, `textarea`, `optgroup`, `option`, `fieldset` |
| Element Should Be Disabled          | 要素が無効であることを確認する                                       | なし                 | `button`, `input`, `select`, `textarea`, `optgroup`, `option`, `fieldset` |
| Textarea Should Contain             | テキストエリアが文字列を含むことを確認する                           | 文字列               | `textarea`                                                                |
| Textarea Value Should Be            | テキストエリアの内容が文字列と一致することを確認する                 | 文字列               | `textarea`                                                                |
| Textfield Should Contain            | テキストフィールドが文字列を含むことを確認する                       | 文字列               | `input`                                                                   |
| Textfield Value Should Be           | テキストフィールドの内容が文字列と一致することを確認する             | 文字列               | `input`                                                                   |
| Checkbox Should Be Selected         | チェックボックスが選択されていることを確認する                       | なし                 | `input[type="checkbox"]`                                                  |
| Checkbox Should Not Be Selected     | チェックボックスが選択されていないことを確認する                     | なし                 | `input[type="checkbox"]`                                                  |
| Radio Button Should Not Be Selected | ラジオボタンが選択されていないことを確認する                         | なし                 | `input[type="radio"]`                                                     |
| List Selection Should Be            | ドロップダウンから文字列と一致する選択肢が選ばれていることを確認する | 文字列               | `select`                                                                  |
| List Should Have No Selections      | ドロップダウンで何も選択されていないことを確認する                   | なし                 | `select`                                                                  |
