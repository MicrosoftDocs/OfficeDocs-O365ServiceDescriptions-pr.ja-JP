---
title: Exchange Online Archiving のクライアント機能
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- clients-and-devices-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c8d5f97a-607f-4949-a4f7-0b9e3b246851
description: Microsoft Exchange Online アーカイブを使用すると、ユーザーはさまざまなデバイスやプラットフォームから自分のアーカイブメールボックスに接続することができます。 ユーザーのアーカイブへのすべてのネットワーク接続がインターネット経由で行われるため、仮想プライベート ネットワーク (VPN) 接続は必要ありません。 組織は、社内のクライアント アクセス サーバーを公開して、VPN 接続がなくてもユーザーが Outlook Anywhere を使用してプライマリ メールボックスにアクセスできるようにできます。 社内サーバーに配置されたユーザーのプライマリ メールボックスにアクセスするのに VPN アクセスが必要な場合も、この要件に変わりはありません。
ms.openlocfilehash: b4f35a2bdc4e0c9f4ae54ec7be4997c9d946e0d4
ms.sourcegitcommit: af6f6ee0a74831a5af784612c7a4316658a53e28
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/18/2019
ms.locfileid: "35018299"
---
# <a name="client-features-in-exchange-online-archiving"></a>Exchange Online Archiving のクライアント機能

Microsoft Exchange Online アーカイブを使用すると、ユーザーはさまざまなデバイスやプラットフォームから自分のアーカイブメールボックスに接続することができます。 ユーザーのアーカイブへのすべてのネットワーク接続がインターネット経由で行われるため、仮想プライベート ネットワーク (VPN) 接続は必要ありません。 組織は、社内のクライアント アクセス サーバーを公開して、VPN 接続がなくてもユーザーが Outlook Anywhere を使用してプライマリ メールボックスにアクセスできるようにできます。 社内サーバーに配置されたユーザーのプライマリ メールボックスにアクセスするのに VPN アクセスが必要な場合も、この要件に変わりはありません。
  
> [!IMPORTANT]
> Microsoft は、Exchange Online Archiving サービスの正常性に悪影響を及ぼすクライアント ソフトウェアからの接続をブロックまたは制限する権利を有します。 
  
## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook は、予定表作成、連絡先、タスクのサポートを含む多機能の電子メール プログラムです。Exchange Online Archiving は、Outlook 2013、Outlook 2010、Outlook 2007 をサポートします。主な機能には以下のものがあります。
  
- **Outlook Anywhere** Outlook Anywhere を使用すれば、Outlook ユーザーは、VPN 接続がなくても、インターネット経由で Exchange Server や Exchange Online Archiving に接続できます。Outlook と Exchange Online Archiving 間の通信は、RPC-over-HTTP Windows ネットワーク コンポーネントを使用し、SSL で保護されたトンネルを介して行われます。    
- **自動検出** Exchange 自動検出サービスは、Exchange Online Archiving と連動するように Outlook を自動的に構成します。Outlook ユーザーは、電子メール アドレスとパスワードを使って初めてサインインしたときに (および、その後は一定間隔で)、自動検出によって直接 Exchange から必要なプロファイルを受け取ることができます。 
    
Outlook 2010 以降と Outlook Web App では、アーカイブのすべての機能に加えて、保持ポリシーやアーカイブ ポリシーなどの関連機能もユーザーに提供されます。
  
Outlook 2007 はアーカイブの基本的なサポートを提供しますが、一部のアーカイブ機能とコンプライアンス機能が Outlook 2007 では使用できません。たとえば、Outlook 2007 では、ユーザーは、保持ポリシーやアーカイブ ポリシーをメールボックス内のアイテムに適用できません。代わりに、管理者によってプロビジョニングされるポリシーを使用する必要があります。Outlook 2007 ユーザーがアーカイブにアクセスするためには、2011 年 2 月の Office 2007 累積更新プログラムが必要です。
  
> [!NOTE]
> Outlook は Exchange Online Archiving に付属していません。Microsoft Office 365 ProPlus (Microsoft Outlook を含む) は、一部の Office 365 プランに含まれているほか、個別のサブスクリプションとして購入することもできます。詳細については、「[Office 365 プランのオプション](../office-365-platform-service-description/office-365-plan-options.md)」を参照してください。Office 365 ProPlus の詳細については、「[Office アプリケーション サービスの説明](../office-applications-service-description/office-applications-service-description.md)」を参照してください。 
  
### <a name="clients-supported-by-exchange-online-archiving"></a>Exchange Online Archiving でサポートされているクライアント

下の表に、Exchange Online Archiving でサポートされているクライアントを列挙します。
  
|**クライアント**|**EOA サポート**|
|:-----|:-----|
|Outlook 2010 以降  <br/> |Exchange Online Archiving の最新機能をサポートします。<sup>1</sup> <br/> |
|Outlook 2007  <br/> |Exchange Online Archiving と一緒に使用するためにサポートされています。<sup>1、2</sup> <br/> |
|Outlook 2003  <br/> |サポートされていません  <br/> |
|Outlook for Mac 2011  <br/> |サポートされていません  <br/> |
|Outlook for Mac  <br/> |サポート対象外 Exchange Online Archiving<sup>3</sup> <br/> |
|Microsoft Office Entourage 2008 Web Services Edition  <br/> |サポートされていません  <br/> |
|IMAP と POP  <br/> |サポートされていません  <br/> |
|Exchange ActiveSync (モバイル デバイス)  <br/> |サポート対象外  <br/> |
   
> [!NOTE]
> <sup>1</sup> Microsoft Office Standard に含まれている Outlook はサポートされていません。 詳細については、「[個人用アーカイブおよびアイテム保持ポリシーのライセンス要件](https://support.office.com/article/Outlook-license-requirements-for-Exchange-features-46B6B7C5-C3CA-43E5-8424-1E2807917C99)」を参照してください。 <br/> 
<sup>2</sup>アーカイブサポートを有効にするには更新が必要です。 Outlook 2007 ユーザーは、アーカイブメールボックス内のアイテムの保持ポリシーまたはアーカイブポリシーを表示したり、適用したりすることはできません。管理者によってプロビジョニングされたポリシーに頼る必要があります。 また、Outlook 2007 ユーザーはオンプレミスのメールボックスとアーカイブを同時に検索することはできません。 <br/> 
<sup>3</sup> outlook 2016 for mac または Outlook for mac を使用して、フォルダー、予定表アイテム、連絡先、タスク、またはメモをアーカイブに移動またはコピーすることはできません。または、アーカイブメールボックスでアイテムが以前に移動されていた場合は、他のバージョンの outlook (Outlook 2016 for Windows)。 詳細については、「 [Outlook 2016 For Mac でオンラインアーカイブを使用する](https://support.office.com/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238)」を参照してください。 

## <a name="outlook-web-app"></a>Outlook Web App

Outlook Web App は、Exchange Online と一緒に使用される Outlook 電子メール プログラムの Web ベース バージョンです。ユーザーは自宅でも、オフィスでも、移動中でも、いつでもインターネットに接続して、Outlook Web App を介して電子メールにアクセスできます。
  
ユーザーは、オンプレミスの Outlook Web App にサインインすることによって (同じ URL を使用して) アーカイブにアクセスすることができます。アーカイブはプライマリ メールボックスと一緒に Outlook Web App に表示されます。Outlook Web App から直接アーカイブにアクセスする明示的な方法はありません。
  
## <a name="feature-availability"></a>機能の可用性

Office 365 のプラン、スタンドアロンのオプション、オンプレミス ソリューション全体の機能の可用性を表示するには、「[Exchange Online Archiving サービスの説明](exchange-online-archiving-service-description.md)」を参照してください。