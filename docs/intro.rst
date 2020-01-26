Microsoft Azure & F5 BIG-IPの簡単ガイド - ようこそ
==============================================

本ガイドでは、Microsoft Azure上にF5 BIG-IPをデプロイする方法について説明します。 

<https://github.com/F5Networks>のAzureテンプレートを使用して、クラウドまたはBIG-IP VEの専門家でなくても、BIG-IP VE構成を迅速かつ確実に作成できます。これらのテンプレートは、ARM（Azure Resource Manager）テンプレートまたはソリューションテンプレートとも呼ばれます。既存Azure環境もしくは、新規環境での展開は可能です。

各テンプレートは事前に構成されたソリューションを作成し、手動構成に伴う時間と労力を節約します。

テンプレートの構成例：
- F5 BIG-IP VEの２台冗長構成
- F5 BIG-IP VE WAFのオートスケール構成
- F5 BIG-IP VE 3-NIC(internal, external, management VLAN)
- その他

購入オプション
-------------------
- ユーティリティ (従量課金制・PAYG) を用いた時間/日/月単位の課金モデルにより、開発、試験といった一時的な展開のほか、OpEx (運用コスト) モデルを希望するお客様にも対応します。

- ライセンス持ち込み (BYOL) はポータブルソフトウェアライセンスで、すべての F5 Ready クラウドに既存の BIG-IP 仮想アプライアンス投資を簡単に拡張できます。

Azureの要件
-------------------
- 有効なサブスクリプションを持つAzureアカウント

References:
  - F5 CloudDocs: <https://clouddocs.f5.com/cloud/public/v1/azure/Azure_solutions101.html>

コンテンツの修正
-------------------
このガイドのコンテンツは、完全なDevOps CI / CDパイプラインを活用しており、以下のGitHubリポジトリから取得可能です。

<https://github.com/tkam8/f5_azure_jp>

コンテンツの不備がありましたら、以下の２つ修正方法で実施可能です。

- GitHubのリポジトリをフォーク（Fork）して、　プルリクエスト（Pull Request）で修正を送信
  
  - <https://backlog.com/ja/git-tutorial/>

- GitHubのリポジトリ上で `Issue <https://github.com/tkam8/f5_azure_jp/issues>`_ を開く