Editor For Jokerscript
====

## Overview
Unity上で動作するプラグイン「Jokerスクリプト」専用のコードをサクラエディタで編集したいという奇特な方向けの入力補完・強調表示ファイルです。
知識のある方であれば、その他のテキストエディタやIDE用の設定ファイルにも流用出来るでしょう。
## Description
現在、Unity付属のVisualStudioではJokerスクリプトの入力補完やシンタックスハイライトは困難な事、VisualStudio自体が非力なマシンではやや不安という個人的需要から作成しました。
サクラエディタとUnityをインストール後、Unity上でEdit->Preference->ExternalツールでUnityから立ち上げるエディタをVisualStudioからサクラエディタに切り替えた後、このファイルを下記Usageの通りサクラエディタに読み込ませてあげてください。

## Usage
\サクラエディタインストール済みディレクトリ\sakura\keyword ディレクトリ内にkwdファイルを設置、その他のファイルは任意のディレクトリに設置

## Install
設定->タイプ別設定->カラー->共通設定->セット追加
ここから任意のセット名でそれぞれシンタックスハイライトの設定ファイル .kwd をインポート

### Install Supplemental
joker_tag.kwdはjokerスクリプト用タグになりますので、インポートする際はセット名をJOKER_TAGに
joker_param.kwdはjokerスクリプト用タグのパラメーターになりますので、セット名をJOKER_PARAM等にしておくと後でわかりやすいでしょう。

設定->タイプ別設定->正規表現キーワード

ここからjoker.rkwをインポート

設定->タイプ別設定->支援->単語ファイル

ここでjoker.txtを指定

設定->タイプ別設定->カラー->強調キーワード1->セット追加で設定したJokerスクリプト用タグのセット名を選択

ex.JOKER_TAG

設定->タイプ別設定->カラー->強調キーワード2->セット追加で設定したJokerスクリプト用パラメーターのセット名を選択

ex.JOKER_PARAM

設定->タイプ別設定->カラー->正規表現キーワード1->チェックを入れる

## Licence

[MIT]http://choosealicense.com/licenses/mit/

## Author

[storchP](https://github.com/storchP)

