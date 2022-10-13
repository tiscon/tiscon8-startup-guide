# Gitのインストール(Mac)

## [brew](http://brew.sh/index_ja.html)のインストール
macOS 用パッケージマネージャーを先にインストールします。<br>
[Terminalを起動](tipsForMac.md#terminalの起動方法)してインストールされているか確認します。
```sh
brew
```
上記のコマンドを実行して、
```sh
Example usage:
  brew search [TEXT|/REGEX/]
  brew info [FORMULA...]
  brew install FORMULA...
  brew update
  brew upgrade [FORMULA...]
  brew uninstall FORMULA...
  brew list [FORMULA...]

Troubleshooting:
  brew config
  brew doctor
  brew install --verbose --debug FORMULA

Contributing:
  brew create [URL [--no-fetch]]
  brew edit [FORMULA...]

Further help:
  brew commands
  brew help [COMMAND]
  man brew
  https://docs.brew.sh
```
上記のようなコマンド一覧が表示された場合はインストールが完了しています。

```sh
-bash: brew: command not found
```
と表示された場合はインストールが必要なので、以下のコマンドを実行してください。
```sh
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
終了したら再度、
```sh
brew
```
を実行してコマンド一覧が表示されればインストール完了です。

処理が終了した時に明らかにエラーと分かるような赤い文字などが出ていたら、エラー内容と共にインターンシップ実施担当者まで問い合わせてください。


## Gitのインストール
brewを使用してGitをインストールします。<br>
[Terminalを起動](tipsForMac.md#terminalの起動方法)して

```sh
brew install git
```
してください。処理が終了した時に :beer: のアイコンが出ていたらOKです。

## インストールできたら
[Terminalを起動](tipsForMac.md#terminalの起動方法)して

```sh
git --version
git version 2.33.0
```
というように `git` コマンドが動くことが確認できればOKです。
