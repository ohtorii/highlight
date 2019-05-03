# 秀丸エディタのハイライト設定集

- [秀丸エディタのハイライト設定集](#秀丸エディタのハイライト設定集)
- [Vim scriptの強調表示](#vim-scriptの強調表示)
- [MEL Script(Autodesk MAYA 2019)の強調表示](#mel-scriptautodesk-maya-2019の強調表示)
- [Shell Script(Bash)の強調表示](#shell-scriptbashの強調表示)
- [MaxScript(Autodesk 3D Studio MAX)の強調表示](#maxscriptautodesk-3d-studio-maxの強調表示)
- [ダウンロード](#ダウンロード)
- [連絡先](#連絡先)


# Vim scriptの強調表示

VIMスクリプトのコードリーディングを主目的として以下方針で作成しました。

- 文字列とコメントは正確に強調する
- それ以外は多少の間違いを許容する

スクリーンショット
![スクリーンショット](images/vim.png "スクリーンショット")

## 強調するもの

- 組み込み関数
- コマンド
- 制御構文
- 変数スコープ
- ネームスペース
- 関数

## ファイル

vim.hilight

## 補足

強調表示定義ファイルを読み込むときに「カラー」を選択すると、上のスクリーンショットと同じ配色になります。

# MEL Script(Autodesk MAYA 2019)の強調表示

以下方針で作成しました。
- MAYA 2019のスクリプトエディタのカラー表示にできるだけ近づける。
- proc定義はできるだけ正確に解析する。

スクリーンショット
![スクリーンショット](images/maya_mel.png "スクリーンショット")


## ファイル

maya_mel.hilight

## 補足

- 強調表示定義ファイルを読み込むときに「カラー」を選択すると、上のスクリーンショットと同じ配色になります。
- 「ファイルメニュー→その他→ファイルタイプ別の設定→その他→単語補完→詳細(X)→強調表示の定義」の設定をONにすることでMELコマンド名の補完（約5000個）が効くようになります。


# Shell Script(Bash)の強調表示

## ファイル

shell.hilight

# MaxScript(Autodesk 3D Studio MAX)の強調表示

ここ10年以上メンテしていませんが、とりあえずアップしました😅😅😅

## ファイル
maxscript.hilight

# ダウンロード

[hilightフォルダ](hilight)から必要なファイルをダウンロードしてください。

# 連絡先

http://d.hatena.ne.jp/ohtorii/ <br>
https://twitter.com/ohtorii <br>

