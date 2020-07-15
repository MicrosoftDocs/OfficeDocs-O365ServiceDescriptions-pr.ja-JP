---
title: ドメイン
ms.author: office365servicedesc
author: pamelaar
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
description: ドメインを追加すると、ユーザーを追加したり、電子メールアドレスやその他のサービスをビジネス名に変換したりするためのステップバイステップウィザードを使用できます。 ウィザードを完了すると、現在のメールプロバイダーに移動するのではなく、会社のメールが Microsoft に届くようになります。 詳細については、「ユーザーとドメインを Microsoft に追加する」を参照してください。 21Vianet が運用している Office 365 を使用する場合は、「ドメインを確認する」を参照してください。
ms.openlocfilehash: b6bbd87a1c3f303ceec0de90b42b322ba513d354
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132401"
---
# <a name="domains"></a>ドメイン

ドメインを追加すると、ユーザーを追加したり、電子メールアドレスやその他のサービスをビジネス名に変換したりするためのステップバイステップウィザードを使用できます。 ウィザードを完了すると、現在のメールプロバイダーに移動するのではなく、会社のメールが Microsoft に届くようになります。 詳細については、「[ユーザーとドメインを Microsoft に追加する](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611)」を参照してください。 21Vianet が運用している Office 365 を使用する場合は、「[ドメインを確認する](https://docs.microsoft.com/office365/admin/setup/add-domain)」を参照してください。
  
## <a name="custom-domains"></a>カスタム ドメイン

サブスクリプションには最大900のドメインを追加できます。 ただし、別の Microsoft クラウド サービスで既に使用している Office 365 にドメインを追加することはできません。 これは、同一のドメインを複数のサブスクリプションに追加できないことを意味します。 詳細については、「[ドメインに関する FAQ](https://support.office.com/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a)」を参照してください。
  
### <a name="second-and-third-level-domains"></a>第 2 および第 3 レベル ドメイン

Office 365 Enterprise および Microsoft 365 Apps for business では、marketing.contoso.com などの第3レベルドメインを含む任意のレベルドメインを追加できます。 「[カスタムサブドメインまたは複数のドメインを Microsoft に追加する」を](https://docs.microsoft.com/office365/admin/setup/domains-faq)参照してください。 21Vianet が運用している Office 365 をご使用の方は、「[21Vianet が運用している Office 365 にカスタム サブドメインまたは複数のドメインを追加する](https://docs.microsoft.com/office365/admin/setup/domains-faq)」を参照してください。
  
## <a name="domain-verification-and-managing-dns-records"></a>ドメインの検証および DNS レコードの管理

Microsoft 365 では、dns ホスティングプロバイダーですべての DNS レコードを管理するか、Microsoft にドメインの DNS レコードを設定して管理することを選択できます。 レコードを引き続き管理する場合は、必要に応じて、特定のレコードを Microsoft サービスをポイントするように変更します。 レコードを追加するための手順を順を追って説明しているドメインレジストラーの一覧については、「 [dns レコードを作成](https://docs.microsoft.com/office365/admin/get-help-with-domains/create-dns-records-at-any-dns-hosting-provider)する」を参照してください。または、21vianet が運用している office 365 を使用している場合は、「21vianet が運用する office 365 の dns レコードを作成する」を参照してください。 
  
Microsoft がドメインの DNS レコードを管理している場合は、まず、ドメインのネームサーバーレコードを Microsoft をポイントするように切り替えてから、microsoft がサービスをセットアップした後、ドメインの DNS レコードを Microsoft で管理する必要があります。
  
ドメインが GoDaddy に登録されている場合、Microsoft は GoDaddy で必要なレコードを作成することができます。 
  
DNS レコードがどこにホストされているかに関係なく、Microsoft または別のホスティングプロバイダーでホストされているパブリック web サイトの URL に対してドメインを使用するように DNS レコードを設定できます。 
  
Microsoft は、dns レコードを事前にチェックして、DNS の問題を見つけて修正します。 DNS レコードが予期したとおりに一致しない場合は、Microsoft 365 管理センターで通知を受け取り、特定された可能性のある問題を解決する方法についての情報を提供します。
  
詳細については、「 [Microsoft が dns](https://docs.microsoft.com/office365/admin/setup/domains-faq)レコードを管理する方法」または「21vianet が運用している office 365」を参照してください。 dns レコードを管理するときには、「 [Create Dns records for office 365](https://docs.microsoft.com/office365/admin/services-in-china/create-dns-records-when-you-manage-your-dns-records)」を参照してください。
  
## <a name="sharing-a-domain"></a>ドメインの共有

一部の電子メールアドレスは、Microsoft のドメインに対して、または前のメールプロバイダーで試験的に使用することができます。 これは、追加のセットアップ手順が必要であり、Microsoft サービスにいくつかの制限があるため、パイロットでのみ使用することをお勧めします。 詳細については、以下を参照してください。
  
- [小規模企業向けの Microsoft 365 のパイロット](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [大規模企業向けの Microsoft 365 のパイロット (FastTrack を使用)](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>機能の可用性

Microsoft 365 のビジネスプラン、スタンドアロンのオプション、オンプレミスソリューションで利用できる機能を表示するには、「 [microsoft 365 および Office 365 platform service description](office-365-platform-service-description.md)」を参照してください。
  

