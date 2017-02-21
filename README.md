# UISearchBar
## 概要
UISearchBarは、検索したい時などに使用するクラスです。

## 関連クラス
UIView、UIResponder

## 主要プロパティ

| プロパティ名名 | 説明 | サンプル |
|:-----------:|:------------:|:------------|
| delegate | delegateを設定する<BR>UISearchBarDelegateのメソッドを利用するため | searchBar.delegate = self |
| showsCancelButton | キャンセルボタンを付加する | searchBar.showsCancelButton = true |
| prompt | タイトルを付加する | searchBar.prompt = "タイトル" |
| placeholder | プレースホルダーを付加する | searchBar.placeholder = "入力してください" |
| keyboardType | キーボードを付加する | searchBar.keyboardType = .default |


## 主要メソッド
### UISearchBarDelegateのメソッド

| メソッド名 | 説明 | 必須 |
|:-----------:|:------------:|:------------|
| searchBarSearchButtonClicked | 検索をクリックしたときに呼ばれる | - |
| textDidChange | サーチバーの中身が更新されるときに呼ばれる | - |

## 開発環境
| Category | Version |
|:-----------:|:------------:|
| Swift | 3.0.2 |
| Xcode | 8.2.1 |
| iOS | 10.0~ |

## 参考
https://developer.apple.com/reference/uikit/uisearchbar
