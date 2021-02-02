---
title: SharePoint Syntex の機能
ms.author: office365servicedesc
author: pamelaar
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
description: 対象となる Microsoft 365、Office 365、および SharePoint Online のプランで利用できる主要な SharePoint Syntex 機能について説明します。
ms.openlocfilehash: 998443a635b7816705553374d8a029f37a669fe0
ms.sourcegitcommit: 68b900488bafad6be4b7216f5a8c5899f159707f
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/02/2021
ms.locfileid: "50072442"
---
# <a name="sharepoint-syntex-features"></a>SharePoint Syntex の機能 

次のセクションでは、対象となる Microsoft 365、Office 365、および SharePoint Online の各プランで利用できる主要な SharePoint [Syntex](sharepoint-syntex-service-description.md) 機能について説明します。 利用可能な機能は、予告なしに変更されることがあります。 機能の最新の完全な一覧については [、SharePoint Syntex](https://www.microsoft.com/microsoft-365/enterprise/sharepoint-syntex)のプランと価格ページをご覧ください。

## <a name="syntex-content-center"></a>Syntex コンテンツ センター

Syntex は、大規模なコンテンツ管理、メタデータとワークフローの統合、コンプライアンス自動化の提供のためのコンテンツ センターと呼ばれるサイト &mdash;  &mdash; テンプレートを提供します。 コンテンツ センターは、ドキュメントの読み取り方法と処理方法を手動で行うのと同じ方法でクラウドに教える機能を提供します。 Syntex は、これらの分析情報を使用して、コンテンツを自動的に認識し、重要な情報を抽出し、メタデータ タグを適用します。 また、統合されたビジュアル分析を使用して、モデルの有効性を追跡できます。

コンテンツ センターの詳細と作成方法については [、「SharePoint Syntex](/microsoft-365/contentunderstanding/create-a-content-center)でコンテンツ センターを作成する」を参照してください。

## <a name="object-recognition"></a>オブジェクト認識

Syntex では、一般的に認識される何千ものオブジェクトを持つ新しいビジュアル ディクショナリを使用して、画像に自動的にタグを付けできます。 さらに、Syntex は手書きのテキストを認識してタグに変換し、検索やさらに処理を行います。

Syntex でのオブジェクト認識とイメージ のタグ付けを構成する方法の詳細については [、「SharePoint Syntex](/microsoft-365/contentunderstanding/image-tagging)でのイメージ のタグ付け」を参照してください。

## <a name="document-understanding"></a>ドキュメントの理解

コードを使用して人工知能 (AI) モデルを構築する場合と同じ方法でコンテンツを読み取る方法を Syntex に教えます。 Syntex では、メタデータの提案または作成、カスタム Power Automate ワークフローの呼び出し、コンプライアンス ラベルの添付を自動的に行い、保持ポリシーまたはレコード管理ポリシーを適用できます。

ドキュメント理解モデルは、Azure Cognitive Services の言語理解モデルに基づいて作成されます。 これらのモデルは Syntex コンテンツ センターで作成および管理され、Syntex 全体で任意のコンテンツ センター内の任意のライブラリにモデルを発行および更新できます。

ドキュメントの理解の詳細については、「ドキュメント理解の概要 [」を参照してください](/microsoft-365/contentunderstanding/document-understanding-overview)。

## <a name="form-processing"></a>フォーム処理

Syntex には、AI ビルダーに基づく強力なフォーム処理エンジンが含まれています。これにより、日付、数値、名前、住所など、半構造化または構造化されたドキュメントから共通の値を自動的に認識して抽出できます。 これらのモデルはコードなしで構築され、信頼性の高い結果を得るドキュメントはわずかです。

フォーム処理の詳細については、「フォーム処理の概要 [」を参照してください](/microsoft-365/contentunderstanding/form-processing-overview)。

## <a name="microsoft-graph-content-connectors"></a>Microsoft Graph コンテンツ コネクタ

Syntex は、Microsoft Graph コネクタを使用して、ファイル共有、Azure SQL などのリモート ソース、または Box や IBM FileNet などのサード パーティソースを Microsoft Graph に統合し &mdash; 、Microsoft 365 全体で検索および使用できます。 &mdash;

Microsoft Graph コネクタを使用すると、お客様は外部リポジトリ内のアイテムにインデックスを付け、Microsoft Search の結果に含めることができます。 Microsoft 365 E5 および Office 365 E5 には、Microsoft Search 用の Microsoft Graph コネクタ (A5 には含まれていない) を使用して、最大 500 アイテムのインデックスを作成する機能が含まれています。 SharePoint または OneDrive プランを含むスイート ライセンスまたはスタンドアロン ライセンスを持つすべてのユーザーは、Microsoft Search の Microsoft Graph コネクタからの検索結果を表示できます。

現在、130 を超えるソースへのコネクタは、Microsoft またはパートナーの 1 つから利用できます。 詳細については、「Microsoft Graph コネクタの [概要」を参照してください](https://aka.ms/iwantconnectors)。

## <a name="advanced-taxonomy-services"></a>高度な分類サービス

Syntex には、Microsoft 365 全体で用語の作成と使用状況を監視および分析できる機能が含まれています。 これらのレポートは、SharePoint 管理センターで配信されます。

共有コンテンツ タイプは、SharePoint ハブ サイトを使用して SharePoint と Microsoft Teams [に発行できます](/sharepoint/dev/features/hub-site/hub-site-overview)。 中央ギャラリーからハブ サイトにコンテンツ タイプを発行すると、一般的に使用されるコンテンツ タイプ (コンテンツの理解を強化) を必要に応じてアーキテクチャの広範なセクション間で迅速に展開およびアップグレードできます。 ハブに接続されたサイトは、発行済みおよび更新されたコンテンツ タイプを自動的に受信します。
