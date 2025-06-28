<samp>
<div align="center">

# version-action-test0

[English](./README.en.md)

</div>

このリポジトリでは、`develop` ブランチなどから `main` ブランチへPRを作成し、マージするとGitHub Actionsが実行されます。

## バージョン管理について

セマンティックバージョニングを採用しています。
PRのタイトルに以下のキーワードが含まれている場合、それに応じたバージョンアップデートが行われます。

* `[major]`：メジャーアップデート
* `[minor]`：マイナーアップデート
* `[patch]`：パッチアップデート
* **キーワードが含まれない場合**：マイナーアップデート

新しいバージョンのタグが作成され、リリースが作成されます。

Install dependencies と build のステップはモックとして実装されています。

</samp>
