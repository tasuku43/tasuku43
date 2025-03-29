# 📁 ポートフォリオ

> [!TIP]  
> 職務経歴やスキルの概要については [resume.md](./resume.md) にてご紹介しています。  

## 🎤 登壇実績
### 🎙 PHP Conference Japan 2024  
#### **タイトル**: Xdebug Profileを使ったCIのボトルネック解析  
#### **概要**:  
多くのテストケースを回すCI環境において、わずかな処理遅延が全体のパフォーマンスに与える影響を可視化するため、Xdebug Profileを用いたメソッド単位のパフォーマンス分析手法を紹介。PHPUnitの実行中に頻出するボトルネックの特定方法を解説しました。

#### 📎 リンク：  
- [イベントページ](https://phpcon.php.gr.jp/2024/)  
- [スライド](https://speakerdeck.com/tasuku43/php-conference-japan-2024)

### 🎙 PHP Conference Japan 2022  
#### **タイトル**: リリースして11年経過したPHPアプリケーションにPHPStanを導入した  
#### **概要**:  
Chatworkの11年もののPHPコードベースにPHPStanを導入し、型エラーの早期検出やCIの品質向上に取り組んだ事例を紹介。導入の背景から障害の乗り越え方、開発チームへの定着を図る工夫、導入によって得られた成果までを実体験として共有しました。

#### 📎 リンク：  
- [イベントページ](https://phpcon.php.gr.jp/2022/)  
- [スライド](https://speakerdeck.com/tasuku43/php-conference-japan-2022)  
- [YouTube](https://www.youtube.com/watch?v=NTw0gxIAYNw)

---

## 👨‍💻 OSS活動

### [tasuku43/php-mermaid-class-diagram](https://github.com/tasuku43/php-mermaid-class-diagram)

> Generate Mermaid-js class diagram from php code.  
> This tool focuses on the relationships between classes and omits the details of class internals at this stage.

PHPコードからMermaid.jsのクラス図を生成するツール。自身の関わらない外部プロジェクトにも活用例あり。  
  
- **使用言語**: PHP  
- **紹介記事**: [[PHP]コードからmermaidjsのクラス図を自動生成するツールを作りました](https://zenn.dev/tasteck/articles/41e0fbd5f6888f)
<br><br>

### [tasuku43/puml-parser-php](https://github.com/tasuku43/puml-parser-php)

> This package builds AST of class definitions from plantuml files. This package works only with php.

PlantUMLからASTを構築するライブラリ。PlantUMLからPHPコードを生成するツールの基盤として開発。  
  
- **使用言語**: PHP  
- **紹介記事**: [[PHP]PlantUMLで定義されたクラス図からコードを自動生成するツールを作成しました](https://zenn.dev/tasteck/articles/e81cd61339dc69)
<br><br>

### [tasuku43/dependency-analyzer](https://github.com/tasuku43/dependency-analyzer)

> Analyze dependencies on specific classes.We hope this will be useful for major version upgrades of dependent libraries. For example, if you know that there is a disruptive change in a particular class, you can immediately see which classes in your project are affected. Combined with a library upgrade tool such as dependebot, it is also possible to comment the affected classes in the generated PR.

特定のクラスや名前空間に依存するクラスを一覧表示するツール。ライブラリのメジャーバージョンアップ時などに影響を受けるクラスを特定する際に役立つ事を想定。
  
- **使用言語**: PHP  
- **紹介記事**: [[PHP]特定のクラスやnamespaceに依存するクラスを一覧表示する静的解析ツールを作成しました](https://zenn.dev/tasteck/articles/28599dcf00b621)
<br><br>

### [tasuku43/har2sequence](https://github.com/tasuku43/har2sequence)

> `har2sequence` is a tool designed to convert HTTP Archive (HAR) files into sequence diagrams. This project aims to help visualize HTTP interactions by generating sequence diagrams based on the information contained in HAR files.

HTTPアーカイブ（HAR）ファイルからMermaid.jsのシーケンス図を生成するツール。OIDCを用いた認証フローの理解を支援する目的で開発。
  
- **使用言語**: Go  
- **紹介記事**: [HARファイルをシーケンス図に変換するツールを作成しました](https://zenn.dev/tasteck/articles/cf8ee8a532ebaa)
<br><br>

---

## 🔎 学習プロジェクト

### Go
- [learn-ds-go](https://github.com/tasuku43/learn-ds-go)
- [build-own-network-stack-go](https://github.com/tasuku43/build-own-network-stack-go)
- [pal (OCI runtime)](https://github.com/tasuku43/pal)
- [go-learn-projects-hub](https://github.com/tasuku43/go-learn-projects-hub)
- [codecrafters-dns-server-go](https://github.com/tasuku43/codecrafters-dns-server-go)
- [codecrafters-docker-go](https://github.com/tasuku43/codecrafters-docker-go)
- [codecrafters-git-go](https://github.com/tasuku43/codecrafters-git-go)

### Scala
- [PumlParserScala](https://github.com/tasuku43/PumlParserScala)

### PHP
- [oil](https://github.com/tasuku43/oil)
- [toy-or-maper](https://github.com/tasuku43/toy-or-maper)
- [toy-container](https://github.com/tasuku43/toy-container)

### その他
- [tasuku43/dns-hierarchy-docker: A complete DNS server hierarchy running in Docker, featuring a root name server, TLD name server, and authoritative DNS using BIND9.](https://github.com/tasuku43/dns-hierarchy-docker)
- [tasuku43/aws-network-server-terraform-handson](https://github.com/tasuku43/aws-network-server-terraform-handson)

## ✍️ 執筆
- TBD
