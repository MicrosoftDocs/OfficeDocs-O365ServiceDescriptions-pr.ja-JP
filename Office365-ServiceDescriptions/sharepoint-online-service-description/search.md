---
title: 検索
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- sharepoint-online-search-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cb36484c-0e8f-480e-be88-5daa8bf2d47d
description: SharePoint Online は、組織がデジタル情報を格納、共有、および管理するのに役立つ web ベースのツールとテクノロジの集合です。 このホスト型サービスは Microsoft SharePoint Server 2013 上に構築されており、プロジェクトの作業、データとドキュメントの一元的な保存、および他のユーザーとの情報の共有を行うのに適しています。 次の検索機能は、ユーザーが業務の遂行に必要な情報を検索するために役立ちます。 検索は、関連性、絞り込み条件、ユーザーの組み合わせです。
ms.openlocfilehash: 39fdeaac67d1c7261e93dd45c4181613910d5ed0
ms.sourcegitcommit: 05458701350d269dce45c9a0812d67d653c52621
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "37726203"
---
# <a name="search"></a>検索

SharePoint Online は、組織がデジタル情報を格納、共有、および管理するのに役立つ web ベースのツールとテクノロジの集合です。 このホスト型サービスは Microsoft SharePoint Server 2013 上に構築されており、プロジェクトの作業、データとドキュメントの一元的な保存、および他のユーザーとの情報の共有を行うのに適しています。 次の検索機能は、ユーザーが業務の遂行に必要な情報を検索するために役立ちます。 検索は、関連性、絞り込み条件、ユーザーの組み合わせです。
  
## <a name="continuous-crawls"></a>継続的クロール

継続的クロールは、SharePoint サイト内のコンテンツを頻繁にクロールすることによって、検索結果を最新の状態に保ちます。SharePoint Online では継続的クロールが有効であり、Microsoft によって管理されたクロール頻度に従います。SharePoint Server 2013 では、管理者が継続的クロールを有効にして、継続的クロールの頻度を管理できます。[SharePoint での既定のクロール対象ファイルのファイル名拡張子および解析対象ファイルの種類](https://docs.microsoft.com/sharepoint/technical-reference/default-crawled-file-name-extensions-and-parsed-file-types)の詳細を確認してください。詳細については、「[SharePoint Server 2013 で継続的クロールを管理する](https://docs.microsoft.com/SharePoint/search/manage-continuous-crawls)」を参照してください。
  
## <a name="deep-links"></a>ディープ リンク

検索システムは、頻繁にアクセスするメイン ページのサブセクションへの直接リンクを自動的に作成します。これらのリンクは、"ディープ リンク"と呼ばれます。詳細については、「[検索のヒント](https://docs.microsoft.com/sharepoint/dev/general-development/search-in-sharepoint)」を参照してください。
  
## <a name="event-based-relevancy"></a>イベント ベースの関連性

検索システムは、コンテンツの接続方法、検索結果でのアイテムの表示頻度、およびユーザーが選択した検索結果に応じて、検索結果の関連性を判断します。 分析コンポーネントがこの情報を追跡および分析し、それを使用して継続的に関連性を改善します。 詳細については、「[SharePoint Server 2013 の分析処理の概要](https://docs.microsoft.com/SharePoint/search/overview-of-analytics-processing)」を参照してください。
  
## <a name="expertise-search"></a>専門知識の検索

SharePoint では、[人の検索] 機能により、特定のスキルまたは経験を備えた人物を簡単に検索できます。検索結果は、ユーザーがそれぞれの個人サイトで自身について入力したメタデータやユーザーが作成したコンテンツからの情報などの情報に基づいています。詳細については、「[検索ナビゲーション Web パーツの設定を変更する](https://docs.microsoft.com/sharepoint/search/configure-properties-of-the-search-navigation-web-part)」を参照してください。
  
## <a name="graphical-refiners"></a>グラフィカルな絞り込み条件

新しいグラフィカルな絞り込み条件は、検索結果をフィルター処理するより視覚的な方法を提供します。 詳細については、「[絞り込み Web パーツの設定を変更する](https://support.office.com/article/About-configuring-the-Refinement-Web-Part-7cef67e8-b992-4659-b21a-ba534eea102e)」を参照してください。
  
## <a name="hybrid-search"></a>ハイブリッド検索

SharePoint のハイブリッド展開では、検索結果のコンテンツは、SharePoint Online サイトと SharePoint Server 2013 社内サイトの両方から取得できます。SharePoint のハイブリッド環境の詳細については、「[SharePoint Server 2013 のハイブリッド](https://docs.microsoft.com/SharePoint/hybrid/hybrid)」を参照してください。
  
## <a name="manage-search-schema"></a>検索スキーマを管理する

SharePoint サイト上でコンテンツを検索すると、検索インデックスに含まれているものが検索されます。検索インデックスは、SharePoint サイト上のコンテンツをクロールすることによって構築され、サイト上のすべてのドキュメントとページからの情報が含まれています。検索スキーマは、クローラーが収集すべきコンテンツとメタデータと、それらにインデックスを付ける方法を決定するのに役立ちます。検索スキーマを変更することによって、カスタマイズした検索エクスペリエンスをユーザーに提供できます。詳細については、「[SharePoint Online で検索スキーマを管理する](https://docs.microsoft.com/sharepoint/manage-search-schema)」を参照してください。
  
## <a name="on-hover-preview"></a>ホバープレビュー

ユーザーはポインターを検索結果の上に合わせ、結果の右側にあるホバー パネルで、ドキュメントやサイトのコンテンツのプレビューや操作ができます。プレビューには、豊富なメタデータが示され、ドキュメントまたはサイトのメイン セクションへのディープ リンクがあります。詳細については、「[検索のヒント](https://support.office.com/article/Not-getting-the-search-results-you-re-looking-for-in-SharePoint-D80687F7-1010-4E6D-ADD9-584B423289D9)」を参照してください。
  
## <a name="phonetic-name-matching"></a>フリガナ マッチング

改善されたフリガナ マッチングが、読み方が類似の名前 (John か Jon か) の検索結果を見つけます。 詳細については、「[検索先を管理する](https://docs.microsoft.com/sharepoint/manage-result-sources)」を参照してください。
  
## <a name="query-rulesadd-promoted-results"></a>クエリ ルール — 昇格対象結果の追加

クエリ ルールでは、条件と相関するアクションを指定します。クエリがクエリ ルールの条件を満たす場合、検索システムはルールに指定されたアクションを実行します。"昇格対象結果の追加" アクションを使うと、検索結果の上位に表示されるように個々の結果を昇格できます。詳細については、「[クエリ ルールを管理する](https://docs.microsoft.com/SharePoint/search/manage-query-rules)」を参照してください。
  
## <a name="query-rulesadvanced-actions"></a>クエリ ルール — 高度なアクション

クエリ ルールでは、条件および相関するアクションを指定することができます。"結果ブロックの追加" アクションを使うと、検索結果のサブセットをグループとして表示することができます。"クエリの変更によるランク付けされた結果の変更" アクションでは、返される検索結果のランク付けを変更することができます。詳細については、「[クエリ ルールを管理する](https://docs.microsoft.com/SharePoint/search/manage-query-rules)」を参照してください。
  
## <a name="query-spelling-correction"></a>クエリのスペル修正

除外一覧と内包一覧を編集して、どのクエリのときに検索結果ページで代替のクエリ スペルを表示するかを決定します。この機能は通常、"検索語句の候補"と呼ばれています。詳細については、「[検索辞書を管理する](https://docs.microsoft.com/sharepoint/search/manage-query-spelling-correction)」を参照してください。
  
## <a name="query-suggestions"></a>クエリ候補

クエリ候補は、ユーザーがすでに検索済みの提案されたフレーズです。候補は、ユーザーがクエリを入力すると検索ボックスの下の一覧に表示されます。クエリ候補は自動的に生成され、"常に" 表示する場合はフレーズをシステムに追加できます。また、候補の表示を "オフ" にすることもできます。詳細については、「[クエリ候補の設定を管理する](https://docs.microsoft.com/sharepoint/search/manage-query-suggestions)」を参照してください。
  
## <a name="ranking-models"></a>ランク付けモデル

SharePoint では、最も関連性の高い項目が最初に表示されるように、ランク付けモデルを使用して検索結果に値が割り当てられます。ランク付けモデルは、特定の項目のランク スコアを計算するランク付け係数のセットです。SharePoint Online と SharePoint Server 2013 の両方に、カスタマイズせずに有効なランク付けを提供するいくつかのランク付けモデルが付属しています。ただし、検索結果をエンド ユーザーにとってより関連性の高いものにする必要がある場合は、ランク付けモデルをカスタマイズすることができます。ランク付けモデル チューニング アプリを使用すれば、SharePoint Online のお客様はカスタム ランク付けモデルを作成できます。このアプリは、既存のランク付けモデルをコピーして、一連のクエリ結果を評価し、ランク機能を追加または削除することでその重みを調整することによってランク付けモデルを "チューニング" するユーザー インターフェイスを提供します。検索結果のランク付けの詳細については、「[SharePoint Online 検索管理の概要](https://docs.microsoft.com/sharepoint/search/overview-of-search-result-ranking)」を参照してください。
  
## <a name="refiners"></a>Refiners

絞り込み条件は、SharePoint Server 検索結果の上位のドキュメントをユーザーが検索結果をフィルター処理できるグループに分類します。詳細については、「[絞り込み Web パーツの設定を変更する](https://support.office.com/article/About-configuring-the-Refinement-Web-Part-7cef67e8-b992-4659-b21a-ba534eea102e)」を参照してください。
  
## <a name="restful-query-apiquery-om"></a>REST 対応のクエリ API/クエリ OM

開発者は、パブリック検索オブジェクト モデルにアクセスする .NET コードを作成できます。 これには、検索クエリの送信に加えて、検索管理操作も含まれます。 サービス側のオブジェクト モデルと対話するには, .NET コードをファーム内の Web サーバーで実行する必要があります。 オブジェクトモデルのサブセットには、クライアント側オブジェクトモデル (CSOM) を使用してリモートコンピューターからアクセスできます。 クライアント側オブジェクトモデル (CSOM) の機能には、REST ベースの web サービスまたは oData を使用してアクセスできます。 これにより、開発者は一般の Web 開発ツールを使用して、クエリを SharePoint Server 2013 ファームに送信できます。

## <a name="search-results-sorting"></a>検索結果の並べ替え

ユーザーは、関連性、鮮度、社会的距離 (&mdash;人の名前) など、さまざまな条件で検索結果を並べ替えることができます。 詳細については、「[検索結果 Web パーツの設定を変更する](https://support.office.com/article/change-settings-for-the-search-results-web-part-40ff85b3-bc5e-4230-b1dd-f088188e487e)」を参照してください。
  
## <a name="this-list-searches"></a>"このリスト" 検索

SharePoint Online と SharePoint Server 2013 では、検索対象を制限して、リストまたはライブラリだけで検索を行うことができます。SharePoint Foundation 2013 では、検索が実行されたサイト以下に存在するすべてのリストとライブラリから検索結果が返されます。
  
## <a name="feature-availability"></a>機能の可用性

Office 365 プラン、スタンドアロンのオプション、オンプレミスソリューション全体の機能の可用性を表示するには、「 [SharePoint Online サービスの説明](sharepoint-online-service-description.md)」を参照してください。
  

