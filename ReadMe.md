Name
====

Overview
Unity上で動作するプラグイン「Jokerスクリプト」専用のコードをサクラエディタで編集したいという奇特な方向けの入力補完・強調表示ファイルです。

## Description
現在、Unity付属のVisualStudioではJokerスクリプトの入力補完やシンタックスハイライトは困難な事、VisualStudio自体が非力なマシンではやや不安という個人的需要から作成しました。
サクラエディタとUnityをインストール後、Unity上でEdit->Preference->ExternalツールでUnityから立ち上げるエディタをVisualStudioからサクラエディタに切り替えた後、このファイルを下記Usageの通りサクラエディタに読み込ませてあげてください。

## Usage
\サクラエディタインストール済みディレクトリ\sakura\keyword ディレクトリ内にkwdファイルを設置、その他のファイルは任意のディレクトリに設置

## Install
設定->タイプ別設定->カラー->共通設定->セット追加
ここから任意のセット名でそれぞれシンタックスハイライトをインポート

設定->タイプ別設定->正規表現キーワード
ここからjoker.rkwをインポート

設定->タイプ別設定->支援->単語ファイル
ここでjoker.txtを指定

## Licence

[MIT]http://choosealicense.com/licenses/mit/

## Author

[storchP](https://github.com/storchP)

