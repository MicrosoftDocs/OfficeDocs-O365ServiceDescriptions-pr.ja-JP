---
title: クライアント機能 (Exchange Online Archiving
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- clients-and-devices-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c8d5f97a-607f-4949-a4f7-0b9e3b246851
description: この記事では、アーカイブで使用できるクライアント機能についてMicrosoft Exchange Onlineしてください。
ms.openlocfilehash: 54f066562b08eeeed90b8c9b465c4740bcc3f0df
ms.sourcegitcommit: e342174df76128430dfc8c971716da5c4b2942ac
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/28/2020
ms.locfileid: "48293643"
---
# <a name="client-features-in-exchange-online-archiving"></a>クライアント機能 (Exchange Online Archiving

Microsoft Exchange Onlineアーカイブを使用すると、ユーザーはさまざまなデバイスやプラットフォームからアーカイブ メールボックスに接続できます。 ユーザーのアーカイブへのネットワーク接続はすべてインターネット上で行われるので、仮想プライベート ネットワーク (VPN) 接続は必要ありません。 組織は、社内のクライアント アクセス サーバーを公開して、VPN 接続がなくてもユーザーが Outlook Anywhere を使用してプライマリ メールボックスにアクセスできるようにできます。 社内サーバーに配置されたユーザーのプライマリ メールボックスにアクセスするのに VPN アクセスが必要な場合も、この要件に変わりはありません。
  
> [!IMPORTANT]
> Microsoft は、Exchange Online Archiving サービスの正常性に悪影響を及ぼすクライアント ソフトウェアからの接続をブロックまたは制限する権利を有します。
  
## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook は、予定表作成、連絡先、タスクのサポートを含む多機能の電子メール プログラムです。Exchange Online Archiving は、Outlook 2013、Outlook 2010、Outlook 2007 をサポートします。主な機能には以下のものがあります。
  
- **Outlook Anywhere** - Outlook Anywhere を使用すると、Outlook ユーザーは vpn 接続を必要とExchange ServerしてExchange Online Archivingをインターネット上で接続できます。 Outlook と Exchange Online Archiving 間の通信は、RPC-over-HTTP Windows ネットワーク コンポーネントを使用し、SSL で保護されたトンネルを介して行われます。    
- **自動検出**- 自動検出Exchangeサービスは、自動検出サービスで動作Outlook自動的に構成Exchange Online Archiving。 自動検出では、Outlook ユーザーが電子メール アドレスとパスワードを使用してサインインする最初の Exchange から (その後、一定の間隔で) 必要なプロファイル設定を直接受信できます。 

Outlook 2010 以降および web 上の Outlook は、ユーザーにアーカイブの完全な機能と、保持ポリシーやアーカイブ ポリシーなどの関連機能を提供します。
  
Outlook 2007 はアーカイブの基本的なサポートを提供しますが、一部のアーカイブ機能とコンプライアンス機能が Outlook 2007 では使用できません。たとえば、Outlook 2007 では、ユーザーは、保持ポリシーやアーカイブ ポリシーをメールボックス内のアイテムに適用できません。代わりに、管理者によってプロビジョニングされるポリシーを使用する必要があります。Outlook 2007 ユーザーがアーカイブにアクセスするためには、2011 年 2 月の Office 2007 累積更新プログラムが必要です。
  
> [!NOTE]
> Outlook は Exchange Online Archiving に付属していません。 Microsoft 365 Apps for enterprise (Microsoft Outlook を含む) は一部のプランに含まれており、個別のサブスクリプションとして購入できます。 詳細については、「プラン オプションMicrosoft 365[参照してください](../office-365-platform-service-description/office-365-plan-options.md)。 アプリケーション サービスの詳細についてはMicrosoft 365 Apps for enterpriseアプリケーション サービスOffice[を参照してください](../office-applications-service-description/office-applications-service-description.md)。 
  
### <a name="clients-supported-by-exchange-online-archiving"></a>Exchange Online Archiving でサポートされているクライアント

下の表に、Exchange Online Archiving でサポートされているクライアントを列挙します。<br><br>
  
| クライアント | EOA サポート |
|:-----|:-----|
|Outlook 2013 以降  <br/> |Exchange Online Archiving の最新機能をサポートします。<sup>1</sup> <br/> |
|Outlook 2010  <br/> |2020 年 10 月 13 日までExchange Online Archivingの最新機能をサポート|
|Outlook 2007  <br/> |非サポート |
|Outlook 2003  <br/> |サポート対象外  <br/> |
|Outlook for Mac 2011  <br/> |サポート対象外  <br/> |
|Outlook for Mac  <br/> |サポート対象外 Exchange Online Archiving<sup>3</sup> <br/> |
|Microsoft Office Entourage 2008 Web Services Edition  <br/> |サポート対象外  <br/> |
|IMAP と POP  <br/> |サポート対象外  <br/> |
|Exchange ActiveSync (モバイル デバイス)  <br/> |サポート対象外  <br/> |
   
> [!NOTE]
> <sup>標準Outlook 1</sup>つのMicrosoft Officeはサポートされていません。 詳細については、「個人用アーカイブおよび保持 [ポリシーのライセンス要件」を参照してください](https://support.office.com/article/Outlook-license-requirements-for-Exchange-features-46B6B7C5-C3CA-43E5-8424-1E2807917C99)。 <br/> 
<sup>2 アーカイブ</sup> サポートを有効にするには更新が必要です。 Outlook 2007 ユーザーは、アーカイブ メールボックス内のアイテムにアイテム保持ポリシーまたはアーカイブ ポリシーを表示または適用できません。管理者がプロビジョニングしたポリシーに依存する必要があります。 さらに、Outlook 2007 ユーザーは、オンプレミスのメールボックスとアーカイブを同時に検索できません。 <br/> 
<sup>3</sup> Outlook 2016 for Mac または Outlook for Mac を使用して、フォルダー、予定表アイテム、連絡先、タスク、メモをアーカイブに移動またはコピーしたり、アーカイブ メールボックスで表示したりすることはできません (Windows の Outlook 2016 など)、他のバージョンの Outlook を使用してアイテムを移動した場合。 詳細については、「オンライン アーカイブとオンライン[アーカイブを使用する」を参照Outlook 2016 for Mac。](https://support.office.com/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238) 

## <a name="outlook-on-the-web"></a>Web 上の Outlook

Outlook on the web は、Exchange Online と連携する Web ベースの Outlook 電子メール プログラムです。 ユーザーが自宅、オフィス、または道路でインターネットに接続されている場合は、web 上のユーザーからメールOutlook &mdash; &mdash; アクセスできます。
  
ユーザーは、(同じ URL を使用して) Outlookにサインインして、自分のアーカイブにアクセスできます。 アーカイブは、Web 上のユーザーのプライマリ メールボックスOutlook一緒に表示されます。 Web 上のアーカイブから直接アーカイブにアクセスOutlook方法はありません。
  
## <a name="feature-availability"></a>機能の可用性

プラン、スタンドアロン オプション、オンプレミス ソリューションの機能の可用性を表示するには、「サービスの説明Exchange Online Archiving[参照してください](exchange-online-archiving-service-description.md)。