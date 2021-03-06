---

copyright:

  years: 2015, 2017
lastupdated: "2017-08-01"

---

{:new_window: target="_blank"}  
{:shortdesc: .shortdesc}


# 新しいサービス資格情報の追加
{: #service_credentials}

外部利用者を Bluemix サービスに手動で接続させたい場合、サービス資格情報の新しいセットを生成することができます。例えば、AWS アプリを Watson サービスにバインドしようとしている場合、これらの 2 つのサービスを一緒にバインドするために使用できる新しいサービス資格情報の生成が必要になります。

Cloud Foundry サービスは、サービス・キー (サービス資格情報とも呼ばれる) を生成できます。サービス資格情報は、サービスに固有であり、各サービスが、生成する必要がある資格情報をどのように定義しているかによって異なります。サービス資格情報には、ユーザー名、パスワード、ホスト名、ポート、および URL が含まれている可能性があります。ただし、各サービス資格情報の内容は、それを生成するサービスに固有です。サービスの中には、パラメーターを渡す必要がある追加データを生成するものもあります。例えば、あるサービスでは、生成されるサービス・キーで返されるデフォルト言語を設定するための言語パラメーターの入力が要求される場合があります。 

新しいサービス資格情報を追加するには、以下の手順を実行してください。

1. 「サービス詳細」ページから「サービス資格情報」タブを選択し、**「新規資格情報 +」**をクリックします。
2. 「新規資格情報の追加」ダイアログから、**「名前」**を指定します。
3. オプションで、インラインまたはファイルのいずれかで提供されるサービス固有の構成パラメーターを含む有効な JSON オブジェクトとして、追加のパラメーターを指定できます。

  **注**: 多くのサービスでは追加のパラメーターは必要なく、追加パラメーターを必要とするサービスでは、各サービスが独自の固有パラメーター・リストを定義しています。サポートされている構成パラメーターのリストについては、特定のサービス・オファリング用の資料を参照してください。
4. **「追加」**をクリックして、新しいサービス資格情報を生成します。
