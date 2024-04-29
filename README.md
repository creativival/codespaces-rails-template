# Codespaces Rails Template

CodespaceでRails開発を簡単に開始できるテンプレートです。

rails newコマンドでRailsプロジェクトを作成した時点から、開発を始められます。

# Usage

このテンプレートレポジトリから新しいレポジトリを作成して開発を始めてください。次の手順を実行します。

1. 本レポジトリの右上ボタン「Use this template > Create a new repository」を選びます。
2. 新しいレポジトリの名前を決めます。公開状態は任意です（Private推奨）。
3. 新しいレポジトリが作成できたら、「Code」ボタンから「Codespace」タブの「Create codespace on main」ボタンをクリックします。
4. Codespaceが開いたら、bundle installコマンドを実行してください。
5. rails sでサーバーが開きます。サーバーが起動できたら、Codespaceの準備は完了です。
6. コードを修正して、Rails開発を開始します。
7. 必要に応じて、VS CodeのExtensionをインストールします。

# Used Command

環境構築で使用したコマンドです。

Rubyバージョンの確認

$ ruby -v

ruby 3.2.3

rails gemのインストール

$ gem install rails

プロジェクトルートにRailsプロジェクトを作成

$ rails new . -f

## License

このプロジェクトは[MITライセンス](LICENSE)の下で公開されています。

