---
title: ドメイン
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-domains
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 5c374309-8016-4f18-8f2a-bceeb863ca67
description: ドメインを追加する場合、ユーザーを追加し、電子メール アドレスや他のサービスをビジネス名に変換する手順を実行します。 ウィザードを完了すると、現在のメール プロバイダーにアクセスする代わりに、ビジネス 用メールが Microsoft に送信されます。 詳細については、「Add your users and domains to Microsoft」を参照してください。 21Vianet が運用している Office 365 を使用する場合は、「ドメインを確認する」を参照してください。
ms.openlocfilehash: 72ea4e88d659d7a6004888c45bb233832978fd34
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652571"
---
# <a name="domains"></a>ドメイン

ドメインを追加する場合、ユーザーを追加し、電子メール アドレスや他のサービスをビジネス名に変換する手順を実行します。 ウィザードを完了すると、現在のメール プロバイダーにアクセスする代わりに、ビジネス 用メールが Microsoft に送信されます。 詳細については、「Microsoft [にユーザーとドメインを追加する」を参照してください](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611)。 21Vianet が運用している Office 365 を使用する場合は、「[ドメインを確認する](/office365/admin/setup/add-domain)」を参照してください。
  
## <a name="custom-domains"></a>カスタム ドメイン

サブスクリプションに最大 900 のドメインを追加できます (サブドメインを含む)。 別の Microsoft クラウド サービスMicrosoft 365しているドメインをドメインに追加できない。 つまり、同じドメインを複数のサブスクリプションに追加できないという意味です。 詳細については、「[ドメインに関する FAQ](https://support.office.com/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a)」を参照してください。
  
### <a name="second-and-third-level-domains"></a>第 2 および第 3 レベル ドメイン

[Office 365 EnterpriseとMicrosoft 365 Apps for businessを使用すると、レベルドメイン (ドメインなどの第 3 レベルドメインを含む) を marketing.contoso.com。 「 [カスタム サブドメインまたは複数のドメインを Microsoft に追加する」を参照してください](/office365/admin/setup/domains-faq)。 21Vianet が運用している Office 365 をご使用の方は、「[21Vianet が運用している Office 365 にカスタム サブドメインまたは複数のドメインを追加する](/office365/admin/setup/domains-faq)」を参照してください。
  
## <a name="domain-verification-and-managing-dns-records"></a>ドメインの検証および DNS レコードの管理

このMicrosoft 365、DNS ホスティング プロバイダーですべての DNS レコードを管理するか、Microsoft がドメインの DNS レコードをセットアップして管理することを選択できます。 レコードを引き続き管理する場合は、必要に応じて特定のレコードをポイントMicrosoft サービス変更します。 各レコードに使用する特定の値を含む、レコードを追加する手順を示すドメイン レジストラーの一覧については、「Create [DNS](/office365/admin/get-help-with-domains/create-dns-records-at-any-dns-hosting-provider) records or if using Office 365 operate by 21Vianet」を参照してください。21Vianet が運用する Office 365 プロバイダーで DNS レコードを作成するを参照してください。 
  
Microsoft がドメインの DNS レコードを管理する場合は、まずドメインのネームサーバー レコードを Microsoft をポイントに切り替え、次に Microsoft がサービスをセットアップしてから、ドメインの DNS レコードを Microsoft で管理する必要があります。
  
ドメインが GoDaddy に登録されている場合、Microsoft は GoDaddy で必要なレコードを作成できます。 
  
DNS レコードがホストされている場所に関係なく、Microsoft でホストされているパブリック Web サイトまたは別のホスティング プロバイダーの URL にドメインを使用する DNS レコードを設定できます。 
  
Microsoft は DNS レコードを積極的にチェックして、DNS の問題を見つけて修正します。 DNS レコードが予想される DNS レコードと一致しない場合は、Microsoft 365 管理センターで通知と、特定された可能性のある問題を修正する方法を示す情報が表示されます。
  
詳細については[、「Microsoft](/office365/admin/setup/domains-faq)が DNS レコードを管理する方法」または「21Vianet が運用する Office 365 については、「DNS レコードを管理するときに Office 365 の DNS レコードを作成する」を[参照](/office365/admin/services-in-china/create-dns-records-when-you-manage-your-dns-records)してください。
  
## <a name="sharing-a-domain"></a>ドメインの共有

Microsoft 上のドメインの一部の電子メール アドレスと、以前のメール プロバイダーの一部をパイロットできます。 これは、追加のセットアップ手順が必要であり、テストの制限が必要なので、パイロットの間にのみ使用Microsoft サービス。 詳細については、以下を参照してください。
  
- [小規模Microsoft 365のパイロット テスト](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [大規模Microsoft 365のパイロット テスト (FastTrack を使用)](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>機能の可用性

ビジネス プラン、スタンドアロン Microsoft 365、オンプレミス ソリューションの機能の可用性を表示するには、「Microsoft 365および[Office 365」を参照してください](office-365-platform-service-description.md)。
