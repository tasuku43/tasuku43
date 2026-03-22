# 職務経歴書

## 基本情報

- 氏名: 山下 祐
- SNS:
  - [GitHub](https://github.com/tasuku43)（継続的にメンテしている OSS / 公開成果物）
  - [X](https://x.com/task2021)
  - [Zenn](https://zenn.dev/tasteck)（OSS・開発改善に関する技術記事執筆）

## スキルサマリー

#### プログラミング言語
- PHP（5年）
    - バージョンアップ対応をはじめ、コード品質向上のために静的解析ツールの導入、テスト基盤の構築、CI整備などの施策を主導
    - 独自フレームワークの拡張を通じて、PSR準拠化や Controller 単位でのテスト基盤を整備
    - 個人開発として複数の OSS ライブラリを公開
- TypeScript（2年）
    - Vue.js／React／Next.jsを用いたSPA開発
- Go / Scala（主に業務外）
    - Goで開発支援CLIやワークスペース管理ツールを継続的に開発
    - 低レイヤ実装の学習・検証を通じて、コンテナ・ネットワーク・OSまわりの理解を補強

#### クラウド・インフラ
- AWS（Lambda, DynamoDB, CloudFront, S3, ECR など）
- Kubernetes（GitOps: Helmfile＋Argo CD運用経験）
- Terraform（既存リソースのコード化・Atlantis運用）

#### CI/CD・自動化ツール
- GitHub Actions
    - マルチアーキテクチャ対応のDockerイメージビルド整備
    - CI/CDパイプラインの効率化・改善を主導

#### Agentic Coding
- Claude Code / Roo Code / GitHub Copilot

#### 監視
- DataDog（メトリクス・ログ監視、ダッシュボード構築）

## 職務要約

2019年にソフトウェアエンジニアとしてキャリアをスタートし、PHPを用いたバックエンド開発から、TypeScript／React／Next.js を用いたフロントエンド開発、AWS や Datadog を用いた運用まで、担当領域を広げてきました。PHPでは静的解析ツールの導入を主導し、11年目の大規模コードベースの品質向上に貢献しました。

その後は職能横断型チームで、要件定義から設計、実装、運用までを一貫して担当し、開発プロセス改善、Kubernetes 上の構成見直し、テスト基盤整備などを推進してきました。

現在はSREグループに所属し、Helmfile・Helm・ArgoCDを活用したEKS基盤の運用、CI/CDおよびIaCワークフロー改善に従事しています。

強みは、開発や運用の流れの中にある詰まりを見つけ、基盤整備や運用改善として具体化し、継続的な改善につなげることです。今後は、個別改善にとどまらず、改善の効果が継続して効き続ける仕組みづくりにより強く関わっていきたいと考えています。

## 主な実績ハイライト

- EKSクラスターバージョンアップと約40アプリケーションの移行統括
- GitHub Actions の改善でDockerイメージのビルド時間を約50%削減
- Aurora RDSのWriter負荷改善を主導し、CPU負荷とコミットレイテンシを改善
- ArgoCDを基盤としたGitOpsライクなメンテナンスIn/Out自動化の仕組みを設計
- バリューストリームマッピングを活用した開発プロセス改善
- Kubernetesデプロイメントの再設計による可用性向上
- PHPアプリケーションへの静的解析導入・品質改善
- PHPの独自Webフレームワークを拡張し、PSR準拠化とテスト基盤の整備

## 職務経歴

### 株式会社kubell(旧Chatwork株式会社): 2019年12月 ~ 現在

#### SREグループ(2025年4月 ~ 現在)
- 役割
	- Helmfile・Helm・ArgoCDを活用したEKS基盤の運用
	- GitHub Actions・Atlantis等を用いたCI/CDおよびIaCワークフローの改善
	- 重要案件の進行状況、依存関係、リスクの把握と、必要に応じた調整・進行支援
	- AI活用基盤やスキル共有の仕組みづくりを通じた開発支援
- 主な実績
    - EKSバージョンアップに伴い新規クラスターを構築し、約40アプリケーションの移行スケジュール調整・統括をリード
    - GitHub Actions のマルチアーキテクチャビルドを刷新し、QEMU エミュレーションを廃止して アーキテクチャ別ランナーによる並列ビルド＋ manifest 統合 を導入。これによりコンテナイメージのビルド時間を 約 50 % 削減
    - Aurora RDSのWriter負荷の調査と改善効果検証を主導し、開発チームと連携して CPU負荷およびコミットレイテンシを改善
    - ArgoCDを基盤とした、GitOpsライクなメンテナンスIn/Out実施を自動化する仕組みを設計

#### 認証チーム (2023年6月 ~ 2025年3月)

- 役割
    - 認証ドメインに特化した職能横断型チームに所属し、PdM、デザイナー、エンジニアと協働。要件定義から設計、実装、運用まで一貫して担当。
    - バックエンド、フロントエンド、インフラ領域を跨いで開発・保守に対応。
- 主な実績
	- 開発プロセス改善を目的にバリューストリームマッピングを作成し、チケット分類を再定義。プロセス可視化と時間トラッキングの容易化を実現
    - システム可用性向上のためKubernetesのデプロイメントを分割し、認証専用のService・Deploymentを導入。ALBトラフィックの最適化を実施
    - マニフェストリポジトリをリファクタリングし、他チームが簡単に同様の設定変更を可能とする基盤を整備

#### モバイル管理画面チーム (2022年10月 ~ 2023年5月)

- 役割
	- 管理機能に特化した職能横断型チームで、要件定義から設計、実装、運用まで一貫して対応
	- バックエンド・フロントエンド・インフラ領域の開発と保守
- 主な実績
	- 社内独自フレームワーク上にミニフレームワークを構築し、開発効率とコードの可読性を向上
	- ヘキサゴナルアーキテクチャを導入して依存関係を明確化し、保守性・テスト容易性を改善
	- OSSを参考にエンドポイント単位での自動テスト基盤を整備し、リファクタリング耐性を強化
	- OpenAPIスキーマからControllerの雛形コードを自動生成するツールを開発し、コード品質の均一化と開発速度を向上

#### PHP部 (2019年12月 ~ 2022年9月)

- 役割
    - プロジェクト単位でアサインされ、複数の開発案件に従事
- 主な実績
	- PHP7.3からPHP8.0へのバージョンアップに対応。Dockerイメージ作成・ECRリポジトリ構築、CircleCIの並行テスト設定によるCIパイプライン改善を実施
	- PHPStan導入を主導し、リリース11年目のPHPアプリケーションのコード品質を向上

### NECフィールディング株式会社: 2016年4月 ~ 2019年11月

カスタマーエンジニアとして、サーバやPCなどのハードウェア修理作業を担当

## 公開成果物

> [!TIP]  
> 詳細については [portfolio.md](./portfolio.md) にてご紹介しています。  

### 登壇資料
- [既存の開発資産を活かしながら、 《新規開発コスト抑制》と《開発体験向上》 を両立する拡張アーキテクチャ事例 - Speaker Deck](https://speakerdeck.com/kubell_hr/250508-yamashita)
- [Xdebug ProfileによるCIパフォーマンス改善のためのボトルネック分析 - Speaker Deck](https://speakerdeck.com/tasuku43/php-conference-japan-2024)
- [リリースして11年経過したPHPアプリケーションにPHPStanを導入した - Speaker Deck](https://speakerdeck.com/tasuku43/php-conference-japan-2022)
### 会社公式ブログ
- [スポットインスタンスの可用性をSpot Placement Scoreで事前評価する - kubell Creator's Note](https://creators-note.chatwork.com/entry/2026/01/07/080000)
- [Claude Code のためのコンテキスト設計で実現した Helmfile README の大量生成 - kubell Creator's Note](https://creators-note.chatwork.com/entry/2025/12/22/000000_1)
- [SREグループにおけるJiraタスク可視化の取り組み - kubell Creator's Note](https://creators-note.chatwork.com/entry/2025/09/09/115740)
- [リリースして11年経過したPHPアプリケーションにPHPStanを導入した - kubell Creator's Note](https://creators-note.chatwork.com/entry/2022/05/24/084828)
- [Datadog Workflow Automationを使って「当日」と「翌日」のオンコール当番をチャットツールに通知する - kubell Creator's Note](https://creators-note.chatwork.com/entry/2025/06/26/180650)
### 個人発信
- [チケット／作業場／cmuxを1:1対応させて、並行タスクを迷わない状態にするCLI「kra」](https://zenn.dev/tasteck/articles/59f56f67aa5584)
- [Git worktreeを宣言的に管理するCLI「gion」を作りました](https://zenn.dev/tasteck/articles/50ecb1926a26a9)
- [[PHP]PlantUMLで定義されたクラス図からコードを自動生成するツールを作成しました](https://zenn.dev/tasteck/articles/e81cd61339dc69)
- [[PHP]コードからmermaidjsのクラス図を自動生成するツールを作りました](https://zenn.dev/tasteck/articles/41e0fbd5f6888f)
- [HARファイルをシーケンス図に変換するツールを作成しました](https://zenn.dev/tasteck/articles/cf8ee8a532ebaa)
