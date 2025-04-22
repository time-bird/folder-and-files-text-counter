# folder-and-files-text-counter README

VSCodeの拡張機能Folder & Files Text Counterのコード全体です。

## 機能

VSCodeのエクスプローラー内のフォルダ、または複数のテキストファイルを選択し、右クリックしてこの拡張機能を実行するとフォルダ内テキストファイルまたは選択ファイル全体の文字数を合計した数を右下のメッセージボックスに表示します。
テキストファイル以外のファイルは無視します。
文字コードはUTF-8のみに対応しています。
全角文字も半角文字も１文字として計算します。
空白と改行は計算に含めません。

使用イメージは下記のリンクを参照してください。
https://time-bird.github.io/hp/apps/02_fftc01.html

### 使い方

エクスプローラー上でフォルダ、または複数のファイルを選択し、右クリックします。表示されるコンテキストメニュー内の「Folder & Files Text Counter」という項目をクリックしてください。右下の通知メッセージに合計した文字数が表示されます。

### インストール

このファイルをダウンロードし、VSCodeの拡張機能メニューの上部３点メニューより「VSIXからのインストール…」よりファイルを指定してインストールします。


## Release Notes

2024年9月28日に最初のVersionをリリースしました。

### 1.0.0

Initial release of ...

### 1.0.1

Fixed issue #.

### 1.1.0

Added features X, Y, and Z.

---

## Following extension guidelines

Ensure that you've read through the extensions guidelines and follow the best practices for creating your extension.

* [Extension Guidelines](https://code.visualstudio.com/api/references/extension-guidelines)
