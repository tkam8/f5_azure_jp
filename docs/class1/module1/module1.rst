Module 1: BIG-IP VE in Azure - Single NIC
===========================

PAYG:
- <https://github.com/F5Networks/f5-azure-arm-templates/tree/master/supported/standalone/1nic/new-stack/payg>

BYOL:
- <https://github.com/F5Networks/f5-azure-arm-templates/tree/master/supported/standalone/1nic/new-stack/byol>

このソリューションでは、ARMテンプレートを使用して、Microsoft AzureでBIG-IP VEの1-NICインスタンスを展開します。トラフィックは、BIG-IP VEからアプリケーションサーバーに流れます。これは、BIG-IP VEインスタンスが単一のインターフェイスで実行され、管理トラフィックとデータプレーントラフィックの両方が処理される構成です。このデプロイ方法はワンアーム構成であり、パブリッククラウドでよく使用されるパターンです。


手順:
----------------
#. PAYGもしくはBYOLのリンクにアクセスし、デプロイ用ボタンをクリックします。

   |mod-1-1|

#. 各パラメータを入力しデプロイします。

   .. NOTE::
   パラメータ名の隣にあるアイコンをマウスオーバーまたはクリックすると、パラメータの説明が表示されます。


#. デプロイが正常に完了すると、テンプレート通りにF5 BIG-IPの仮想マシンがAzureのGUI上で表示されます。


以上が、リソースマネージャーのテンプレートを使ったF5 BIG-IPの仮想マシンのデプロイ手順となります。



.. |mod-1-1| image:: images/mod-1-1.png
