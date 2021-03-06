---
title: SharePoint Syntex の機能
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
description: 対象となるオンライン プラン、SharePoint、およびオンライン プランで利用できる主要な Syntex Microsoft 365、Office 365についてSharePointします。
ms.openlocfilehash: 2ffc3ccb52d074434c89424a151e63c7698b62c2
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/09/2021
ms.locfileid: "51651032"
---
# <a name="sharepoint-syntex-features"></a>SharePoint Syntex の機能 

以下のセクションでは、対象となるオンライン プラン、SharePoint、およびオンライン プランで利用できる主要な[syntex](sharepoint-syntex-service-description.md) Microsoft 365、Office 365についてSharePoint説明します。 利用可能な機能は予告なしに変更される場合があります。 最新の機能の完全な一覧については、「Syntex プランと価格SharePoint[ページ」を参照してください](https://www.microsoft.com/microsoft-365/enterprise/sharepoint-syntex)。

## <a name="syntex-content-center"></a>Syntex コンテンツ センター

Syntex は、コンテンツを大規模に管理し、メタデータとワークフローを統合し、コンプライアンスの自動化を実現するためのコンテンツ センターと呼ばれるサイト &mdash;  &mdash; テンプレートを提供します。 コンテンツ センターは、ドキュメントを手動で読み取って処理する方法をクラウドに教える機能を提供します。 Syntex は、これらの分析情報を使用してコンテンツを自動的に認識し、重要な情報を抽出し、メタデータ タグを適用します。 さらに、統合されたビジュアル分析を使用してモデルの有効性を追跡できます。

コンテンツ センターとコンテンツ センターを作成する方法の詳細については、「Create a content [center in SharePoint Syntex 」を参照してください](/microsoft-365/contentunderstanding/create-a-content-center)。

## <a name="object-recognition"></a>オブジェクト認識

Syntex は、何千もの一般的に認識されるオブジェクトを持つ新しいビジュアル ディクショナリを使用して、画像に自動的にタグを付けできます。 さらに、Syntex は手書きのテキストを認識してタグに変換して、検索やさらなる処理で使用できます。

Syntex でのオブジェクト認識の詳細と画像のタグ付けを構成する方法については、「画像タグ付け」を参照SharePoint[してください](/microsoft-365/contentunderstanding/image-tagging)。

## <a name="document-understanding"></a>ドキュメント理解

コードを使用して人工知能 (AI) モデルを構築するために機械学習を使用する方法でコンテンツを読み取る方法を Syntex に教えます。 Syntex では、メタデータの提案または作成、カスタム ワークフローの呼びPower Automate、コンプライアンス ラベルを添付して保持またはレコード管理ポリシーを適用できます。

ドキュメント理解モデルは、Azure Cognitive Services の言語理解モデルに基づいて作成されます。 これらのモデルは Syntex コンテンツ センターで作成および管理され、Syntex 全体の任意のコンテンツ センター内の任意のライブラリにモデルを発行および更新できます。

ドキュメントの理解の詳細については、「ドキュメントの概要 [」を参照してください](/microsoft-365/contentunderstanding/document-understanding-overview)。

## <a name="form-processing"></a>フォーム処理

Syntex には、AI ビルダーに基づく強力なフォーム処理エンジンが含まれています。これにより、日付、図形、名前、住所など、半構造化または構造化されたドキュメントから共通の値を自動的に認識して抽出できます。 これらのモデルはコードなしで構築され、信頼性の高い結果を得るドキュメントはわずかです。

フォーム処理の詳細については、「フォーム処理の [概要」を参照してください](/microsoft-365/contentunderstanding/form-processing-overview)。

## <a name="microsoft-graph-content-connectors"></a>Microsoft Graph コンテンツ コネクタ

Syntex は、Microsoft Graph コネクタを使用して、ファイル共有、Azure SQL、または Box や IBM FileNet などのサード パーティソースなどのリモート ソースを Microsoft Graph に統合し、Microsoft 365 全体で検索および使用できます。 &mdash; &mdash;

Microsoft Graphコネクタを使用すると、Microsoft 検索結果に含める外部リポジトリ内のアイテムにインデックスを作成できます。 Microsoft 365 E5および Office 365 E5 には、Microsoft 検索用 Microsoft Graph コネクタ (A5 には含まれていない) を使用して、最大 500 アイテムのインデックスを作成する機能が含まれます。 スイート ライセンスまたはスタンドアロン ライセンスを持つすべてのユーザーが、SharePoint または OneDrive プランを含む場合は、Microsoft Search の Microsoft Graph コネクタからの検索結果を確認できます。

現在、130 を超えるソースへのコネクタは、Microsoft またはパートナーの 1 つから利用できます。 詳細については[、「Microsoft Graphコネクタの概要」を参照してください](/MicrosoftSearch/connectors-overview)。

## <a name="advanced-taxonomy-services"></a>高度な分類サービス

Syntex には、用語の作成と使用状況を監視および分析できる機能が含Microsoft 365。 これらのレポートは、管理センター SharePoint配信されます。

共有コンテンツ タイプは、ハブ サイトをSharePointしてMicrosoft Teams共有SharePoint[発行できます](/sharepoint/dev/features/hub-site/hub-site-overview)。 中央ギャラリーからハブ サイトにコンテンツ タイプを発行すると、一般的に使用されるコンテンツ タイプ (コンテンツの理解が強化された) を、必要に応じてアーキテクチャの広範なセクション間で迅速に展開およびアップグレードできます。 ハブに接続されているサイトは、発行および更新されたコンテンツ タイプを自動的に受信します。