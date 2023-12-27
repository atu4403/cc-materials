# cc-materials Cookiecutter Template

## 概要
`cc-materials` は、メディアプロジェクト用の素材管理ディレクトリ構造を生成するためのCookiecutterテンプレートです。このテンプレートを使用して、Audio、Image、Other、Videoの各カテゴリに分かれた素材管理ディレクトリを素早くセットアップできます。

## 前提条件
このテンプレートを使用するには、Cookiecutterがインストールされている必要があります。まだインストールしていない場合は、以下のコマンドでインストールできます：

```bash
pip install cookiecutter
```

その他にもHomeBrew,pipx,XBPSなどを使ってインストールすることも可能です。詳しくは公式ドキュメントを参照してください。

[Cookiecutter Installation Guide](https://cookiecutter.readthedocs.io/en/stable/installation.html)

## 使用方法
1. **テンプレートの生成**:
   以下のコマンドを実行し、`cc-materials` テンプレートから新しいプロジェクトを生成します。

   ```bash
   cookiecutter gh:atu4403/cc-materials
   ```

   必要に応じて、`directory_name` などのプロンプトに回答します。

2. **ディレクトリ構造のカスタマイズ**:
   生成されたプロジェクトディレクトリ内で、必要に応じてフォルダやファイルを追加、編集、削除します。

3. **プロジェクトの使用開始**:
   生成されたディレクトリ構造を使用して、素材管理を開始します。

## ディレクトリ構造
生成されるディレクトリ構造は以下の通りです：

```
{{cookiecutter.directory_name}}/
├── Audio/
│   ├── Favorites/
│   ├── Music/
│   └── SoundEffects/
├── Image/
│   ├── BackgroundImages/
│   ├── Favorites/
│   ├── Illustrations/
│   └── Photographs/
├── Other/
│   ├── Documents/
│   ├── Favorites/
│   ├── Notes/
│   └── Templates/
└── Video/
    ├── Favorites/
    ├── FreeStockVideos/
    └── PaidStockVideos/
```

## サポート
このテンプレートに関する質問やフィードバックは、GitHubのIssuesまたはPull Requestsを通じてお寄せください。
