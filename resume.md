# 職務経歴書

## 基本情報

- 氏名: 山下 祐
- SNS:
  - [GitHub](https://github.com/tasuku43)（OSS / 学習用プロジェクト）
  - [X](https://x.com/task2021)
  - [Zenn](https://zenn.dev/tasteck)（技術記事執筆）

## スキルサマリー

#### プログラミング言語
- PHP（5年）
    - バージョンアップ対応をはじめ、コード品質向上のために静的解析ツールの導入、テスト基盤の構築、CI整備などの施策を主導
    - 独自フレームワークの拡張を通じて、PSR準拠化や Controller 単位でのテスト基盤を整備
    - 個人開発として複数の OSS ライブラリを公開
- TypeScript（2年）
    - Vue.js／React／Next.jsを用いたSPA開発
- Go / Scala（非業務）
    - ネットワークスタックなどの低レイヤ実装を中心に学習・検証

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

2019年にソフトウェアエンジニアとしてキャリアをスタートし、PHPを用いたバックエンド開発から始め、フロントエンド開発（TypeScript／React／Next.js）、インフラ運用（AWS、Datadog）、そして現在のSRE業務へと技術領域を広げてきました。PHPでは静的解析ツールの導入を主導し、11年目の大規模コードベースの品質向上に貢献しました。

その後はフルサイクル開発チームの一員として、TypeScript／React／Next.jsを用いたフロントエンド開発を経験。AWS（CloudFront、API Gateway など）を活用したインフラ運用とDatadogによる監視体制の構築も担当しました。

現在はSREグループに所属し、Helmfile・Helm・ArgoCDを駆使したEKS基盤の運用とCI/CDパイプライン改善に従事しています。

今後はクラウドネイティブ技術の専門性を深め、Platform SREとして技術・プロセス両面から組織の継続的な改善に貢献していきたいと考えています。

## 主な実績ハイライト

- EKSクラスターバージョンアップと約40アプリケーションの移行統括
- GitHub Actions の改善でDockerイメージのビルド時間を約50%削減
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
- 主な実績
    - EKSバージョンアップに伴い新規クラスターを構築し、約40アプリケーションの移行スケジュール調整・統括をリード
    - GitHub Actions のマルチアーキテクチャビルドを刷新し、QEMU エミュレーションを廃止して アーキテクチャ別ランナーによる並列ビルド＋ manifest 統合 を導入。これによりコンテナイメージのビルド時間を 約 50 % 削減
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
- [リリースして11年経過したPHPアプリケーションにPHPStanを導入した - kubell Creator's Note](https://creators-note.chatwork.com/entry/2022/05/24/084828)
- [Datadog Workflow Automationを使って「当日」と「翌日」のオンコール当番をチャットツールに通知する - kubell Creator's Note](https://creators-note.chatwork.com/entry/2025/06/26/180650)
### 個人発信
- [[PHP]PlantUMLで定義されたクラス図からコードを自動生成するツールを作成しました](https://zenn.dev/tasteck/articles/e81cd61339dc69)
- [[PHP]コードからmermaidjsのクラス図を自動生成するツールを作りました](https://zenn.dev/tasteck/articles/41e0fbd5f6888f)
- [HARファイルをシーケンス図に変換するツールを作成しました](https://zenn.dev/tasteck/articles/cf8ee8a532ebaa)