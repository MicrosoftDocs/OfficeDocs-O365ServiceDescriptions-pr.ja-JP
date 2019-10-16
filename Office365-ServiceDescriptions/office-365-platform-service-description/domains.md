---
title: ドメイン
ms.author: sharik
author: skjerland
manager: mnirkhe
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
description: ドメインを追加する時にステップ バイ ステップのウィザードを使用すれば、ユーザーを追加したり、Office 365 のメール アドレスやその他のサービスを会社名に変換したりする作業を簡単に行えます。 ウィザードを完了すると、ビジネス用の電子メールは、現在のメール プロバイダーではなく Office 365 に届くようになります。 詳細については、「Office 365 にユーザーとドメインを追加する」を参照してください。 21Vianet が運用している Office 365 を使用する場合は、「ドメインを確認する」を参照してください。
ms.openlocfilehash: d4d2e0316960f6c3d91cbdb088bd154d6739c2f2
ms.sourcegitcommit: 4d1cc432b4ce292abeb926f88108937695ce619b
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/15/2019
ms.locfileid: "37523405"
---
# <a name="domains"></a>ドメイン

ドメインを追加する時にステップ バイ ステップのウィザードを使用すれば、ユーザーを追加したり、Office 365 のメール アドレスやその他のサービスを会社名に変換したりする作業を簡単に行えます。 ウィザードを完了すると、ビジネス用の電子メールは、現在のメール プロバイダーではなく Office 365 に届くようになります。 詳細については、「[Office 365 にユーザーとドメインを追加する](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611)」を参照してください。 21Vianet が運用している Office 365 を使用する場合は、「[ドメインを確認する](https://docs.microsoft.com/office365/admin/setup/add-domain)」を参照してください。
  
## <a name="custom-domains"></a>カスタム ドメイン
<a name="BKMK_CustomDomains"> </a>

最大 900 のドメインを Office 365 サブスクリプションに追加できます。ただし、別の Microsoft クラウド サービスで既に使用している Office 365 にドメインを追加することはできません。つまり、複数の Office 365 サブスクリプションに同一ドメインを追加することはできません。詳細については、「[ドメインに関する FAQ](https://support.office.com/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a)」を参照してください。
  
### <a name="second-and-third-level-domains"></a>第 2 および第 3 レベル ドメイン
<a name="BKMK_SecondAndThirdLevelDomains"> </a>

Office 365 Enterprise と Office 365 Business を使用すれば、marketing.contoso.com などの第 3 レベル ドメインを含む任意のレベル ドメインを追加できます。詳細は、「[カスタム サブドメインまたは複数のドメインを Office 365 に追加する](https://docs.microsoft.com/office365/admin/setup/domains-faq)」を参照してください。21Vianet が運用している Office 365 をご使用の方は、「[21Vianet が運用している Office 365 にカスタム サブドメインまたは複数のドメインを追加する](https://docs.microsoft.com/office365/admin/setup/domains-faq)」を参照してください。
  
## <a name="domain-verification-and-managing-dns-records"></a>ドメインの検証および DNS レコードの管理
<a name="BKMK_ManagingDNSRecords"> </a>

Office 365 では、DNS ホスティング プロバイダーですべての DNS レコードを管理することも、Office 365 がドメインの DNS レコードを設定して管理するよう選択することもできます。レコードを引き続き自分で管理する場合は、必要に応じて特定のレコードが Office 365 サービスを指すよう変更します。各レコードに使用する特定の値など、レコードの追加に関する詳しい手順を提供しているドメイン登録業者の一覧については、「[任意の DNS ホスティング プロバイダーで Office 365 用の DNS レコードを作成する](https://docs.microsoft.com/office365/admin/get-help-with-domains/create-dns-records-at-any-dns-hosting-provider)」を参照してください。21Vianet が運用している Office 365 を使用している場合は、「21Vianet が運用している Office 365 用に任意のプロバイダーで DNS レコードを作成する」を参照してください。 
  
Office 365 がドメインの DNS レコードを管理する場合は、最初にドメインのネームサーバー レコードが Office 365 を指すよう切り替えてから、Office 365 が Office 365 のサービスを設定し、その後ドメインの DNS レコードが Office 365 で管理されるようにする必要があります。
  
ドメインが GoDaddy に登録されている場合は、 Office 365 が GoDaddy で必要なレコードを作成することができます。 
  
DNS レコードがどこでホストされているかに関係なく、Office 365 上でホストされたパブリック Web サイトまたは別のホスティング プロバイダーを使用したパブリック Web サイトの URL のドメインを使用するように DNS レコードを設定できます。 
  
Office 365 は、DNS レコードを積極的にチェックし、DNS の問題を検索して解決します。 DNS レコードが予期したとおりに一致しない場合は、Microsoft 365 管理センターで通知を受け取り、特定された可能性のある問題を解決する方法についての情報を提供します。
  
詳細については、「[ドメインに関する FAQ](https://docs.microsoft.com/office365/admin/setup/domains-faq)」を参照してください。21Vianet が運用している Office 365 については、「[DNS レコードの管理時に Office 365 の DNS レコードを作成する](https://docs.microsoft.com/office365/admin/services-in-china/create-dns-records-when-you-manage-your-dns-records)」を参照してください。
  
## <a name="sharing-a-domain"></a>ドメインの共有
<a name="BKMK_ManagingDNSRecords"> </a>

Office 365 は、Office 365 上のドメインのいくつかの電子メール アドレスと以前の電子メール プロバイダー上のいくつかの電子メール アドレスを使用して試運転することができます。この方法は、追加の設定ステップを必要とし、Office 365 サービスの一部が制限されるため、Office 365 の試運転期間にだけ使用することをお勧めします。詳細については、次のトピックをご覧ください。
  
- [小規模企業向けに Office 365 を試験運用する](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [大企業向けに Office 365 を試験運用する (FastTrack を使用)](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>機能の可用性
<a name="BKMK_ManagingDNSRecords"> </a>

Office 365 プラン、スタンドアロンのオプション、オンプレミスソリューション全体の機能の可用性を表示するには、「 [office 365 Platform Service Description](office-365-platform-service-description.md)」を参照してください。
  

