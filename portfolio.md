# 📁 ポートフォリオ

> [!TIP]  
> 職務経歴やスキルの概要については [resume.md](./resume.md) にてご紹介しています。  

## 🎤 登壇実績

### 🎙 [技術的負債への向き合い PHP編｜10年越えプロダクトを提供する3社が語ります！](https://codmon.connpass.com/event/347561/)
#### **タイトル**: 
既存の開発資産を活かしながら、 《新規開発コスト抑制》と《開発体験向上》 を両立する拡張アーキテクチャ事例

#### **概要**:  

既存のPHPベースの独自Webフレームワークを拡張する事で、新規開発コストの削減と開発者体験の向上を両立させたアーキテクチャ拡張事例を紹介。具体的には、PSR準拠化やテスト基盤整備を通じて、保守性と開発効率を改善した取り組みをお伝えしました。

#### 📎 リンク：  
- [イベントページ](https://codmon.connpass.com/event/347561/)  
- [スライド](https://speakerdeck.com/kubell_hr/250508-yamashita) 

### 🎙 [PHP Conference Japan 2024](https://phpcon.php.gr.jp/2024/)  
#### **タイトル**: 
Xdebug Profileを使ったCIのボトルネック解析  
#### **概要**:  
多くのテストケースを回すCI環境において、わずかな処理遅延が全体のパフォーマンスに与える影響を可視化するため、Xdebug Profileを用いたメソッド単位のパフォーマンス分析手法を紹介。PHPUnitの実行中に頻出するボトルネックの特定方法を解説しました。

#### 📎 リンク：  
- [スライド](https://speakerdeck.com/tasuku43/php-conference-japan-2024)

<br>

### 🎙 [PHP Conference Japan 2022](https://phpcon.php.gr.jp/2022/)  
#### **タイトル**: リリースして11年経過したPHPアプリケーションにPHPStanを導入した  
#### **概要**:  
Chatworkの11年もののPHPコードベースにPHPStanを導入し、型エラーの早期検出やCIの品質向上に取り組んだ事例を紹介。導入の背景から障害の乗り越え方、開発チームへの定着を図る工夫、導入によって得られた成果までを実体験として共有しました。

#### 📎 リンク：  
- [スライド](https://speakerdeck.com/tasuku43/php-conference-japan-2022)  
- [YouTube](https://www.youtube.com/watch?v=NTw0gxIAYNw)

---

## 👨‍💻 OSS活動

### 現在継続的にメンテしているOSS

### [tasuku43/kra](https://github.com/tasuku43/kra)

![GitHub stars](https://img.shields.io/github/stars/tasuku43/kra?style=flat-square)
![GitHub forks](https://img.shields.io/github/forks/tasuku43/kra?style=flat-square)

> Ticket-driven local workspaces with per-task Git worktrees and optional cmux workspace mapping.

チケット駆動のローカル開発ワークスペース運用を支援するCLI。タスクごとに分離したワークスペースを作成し、必要なリポジトリだけをGit worktreeで接続しながら作業を進められます。完了時は `archive/` に安全に退避でき、`cmux` と組み合わせることで ticket / workspace / terminal workspace を揃えた運用を実現します。

- **使用言語**: Go
- **主な特徴**: タスク単位のワークスペース管理、Git worktree の選択的な接続、`archive/` を前提にしたライフサイクル運用、`cmux` 連携
- **紹介記事**: [チケット／作業場／cmuxを1:1対応させて、並行タスクを迷わない状態にするCLI「kra」](https://zenn.dev/tasteck/articles/59f56f67aa5584)
<br><br>

### [tasuku43/gion](https://github.com/tasuku43/gion)

![GitHub stars](https://img.shields.io/github/stars/tasuku43/gion?style=flat-square)
![GitHub forks](https://img.shields.io/github/forks/tasuku43/gion?style=flat-square)

> Task workspaces as code, with guardrails. Built on Git worktrees: define a YAML inventory, then plan/apply to reconcile safely.

Git worktree ベースの task workspaces as code ツール。YAML マニフェストを正本にして `plan/apply` で差分を確認しながら、ワークスペースの一括作成・削除を安全に扱えます。PRレビュー、issue調査、再現環境の切り出しなど、複数リポジトリにまたがる作業を宣言的に管理できるようにしています。

- **使用言語**: Go
- **主な特徴**: YAML による宣言的管理、差分確認を前提にした一括作成・削除、削除リスクの可視化、GitHub PR / issue 起点のワークスペース作成
- **紹介記事**: [Git worktreeを宣言的に管理するCLI「gion」を作りました](https://zenn.dev/tasteck/articles/50ecb1926a26a9)
<br><br>

### 過去に公開したOSS

現在は主に `kra` と `gion` のメンテナンスに注力しており、以下はこれまでに公開してきたOSSです。

### [tasuku43/php-mermaid-class-diagram](https://github.com/tasuku43/php-mermaid-class-diagram)

![GitHub stars](https://img.shields.io/github/stars/tasuku43/php-mermaid-class-diagram?style=flat-square)
![GitHub forks](https://img.shields.io/github/forks/tasuku43/php-mermaid-class-diagram?style=flat-square)
![Packagist Downloads](https://img.shields.io/packagist/dt/tasuku43/mermaid-class-diagram?style=flat-square)

> Generate Mermaid-js class diagram from php code.  
> This tool focuses on the relationships between classes and omits the details of class internals at this stage.

PHPコードからMermaid.jsのクラス図を生成するツール。  

- **使用言語**: PHP  
- **紹介記事**: [[PHP]コードからmermaidjsのクラス図を自動生成するツールを作りました](https://zenn.dev/tasteck/articles/41e0fbd5f6888f)
<br>

このツールは、以下の外部プロジェクトのREADMEに掲載されているクラス図の生成に使用された実績があります（※当該プロジェクトの開発には関与していません）：  
> [MyIntervals/PHP-CSS-Parser](https://github.com/MyIntervals/PHP-CSS-Parser)  
> A Parser for CSS Files written in PHP. Allows extraction of CSS files into a data structure, manipulation of said structure and output as (optimized) CSS.

<br>

### [tasuku43/puml-parser-php](https://github.com/tasuku43/puml-parser-php)

![GitHub stars](https://img.shields.io/github/stars/tasuku43/puml-parser-php?style=flat-square)
![GitHub forks](https://img.shields.io/github/forks/tasuku43/puml-parser-php?style=flat-square)
![Packagist Downloads](https://img.shields.io/packagist/dt/puml2php/puml-parser?style=flat-square)

> This package builds AST of class definitions from plantuml files. This package works only with php.

PlantUMLからASTを構築するライブラリ。PlantUMLからPHPコードを生成するツールの基盤として開発。  
  
- **使用言語**: PHP  
- **紹介記事**: [[PHP]PlantUMLで定義されたクラス図からコードを自動生成するツールを作成しました](https://zenn.dev/tasteck/articles/e81cd61339dc69)
<br><br>

### [tasuku43/dependency-analyzer](https://github.com/tasuku43/dependency-analyzer)

![GitHub stars](https://img.shields.io/github/stars/tasuku43/dependency-analyzer?style=flat-square)
![GitHub forks](https://img.shields.io/github/forks/tasuku43/dependency-analyzer?style=flat-square)
![Packagist Downloads](https://img.shields.io/packagist/dt/tasuku43/dependency-analyzer?style=flat-square)

> Analyze dependencies on specific classes.We hope this will be useful for major version upgrades of dependent libraries. For example, if you know that there is a disruptive change in a particular class, you can immediately see which classes in your project are affected. Combined with a library upgrade tool such as dependebot, it is also possible to comment the affected classes in the generated PR.

特定のクラスや名前空間に依存するクラスを一覧表示するツール。ライブラリのメジャーバージョンアップ時などに影響を受けるクラスを特定する際に役立つ事を想定。
  
- **使用言語**: PHP  
- **紹介記事**: [[PHP]特定のクラスやnamespaceに依存するクラスを一覧表示する静的解析ツールを作成しました](https://zenn.dev/tasteck/articles/28599dcf00b621)
<br><br>

### [tasuku43/har2sequence](https://github.com/tasuku43/har2sequence)

![GitHub stars](https://img.shields.io/github/stars/tasuku43/har2sequence?style=flat-square)
![GitHub forks](https://img.shields.io/github/forks/tasuku43/har2sequence?style=flat-square)

> `har2sequence` is a tool designed to convert HTTP Archive (HAR) files into sequence diagrams. This project aims to help visualize HTTP interactions by generating sequence diagrams based on the information contained in HAR files.
HTTPアーカイブ（HAR）ファイルからMermaid.jsのシーケンス図を生成するツール。OIDCを用いた認証フローの理解を支援する目的で開発。
  
- **使用言語**: Go  
- **紹介記事**: [HARファイルをシーケンス図に変換するツールを作成しました](https://zenn.dev/tasteck/articles/cf8ee8a532ebaa)
<br><br>
