---
title: Exchange Online アーカイブのクライアント機能
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
description: Microsoft Exchange Online アーカイブを使用すると、ユーザーはさまざまなデバイスやプラットフォームから自分のアーカイブメールボックスに接続することができます。 ユーザーのアーカイブへのすべてのネットワーク接続はインターネット経由で行われるため、仮想プライベートネットワーク (VPN) 接続は必要ありません。 組織は、社内のクライアント アクセス サーバーを公開して、VPN 接続がなくてもユーザーが Outlook Anywhere を使用してプライマリ メールボックスにアクセスできるようにできます。 社内サーバーに配置されたユーザーのプライマリ メールボックスにアクセスするのに VPN アクセスが必要な場合も、この要件に変わりはありません。
ms.openlocfilehash: 6f29f434f5b6515460ee526450fba4a50bb6c191
ms.sourcegitcommit: e2ebd2f3e4b6e2ec76a29498dc276fa0f05f18a3
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/26/2020
ms.locfileid: "47255904"
---
# <a name="client-features-in-exchange-online-archiving"></a>Exchange Online アーカイブのクライアント機能

Microsoft Exchange Online アーカイブを使用すると、ユーザーはさまざまなデバイスやプラットフォームから自分のアーカイブメールボックスに接続することができます。 ユーザーのアーカイブへのすべてのネットワーク接続はインターネット経由で行われるため、仮想プライベートネットワーク (VPN) 接続は必要ありません。 組織は、社内のクライアント アクセス サーバーを公開して、VPN 接続がなくてもユーザーが Outlook Anywhere を使用してプライマリ メールボックスにアクセスできるようにできます。 社内サーバーに配置されたユーザーのプライマリ メールボックスにアクセスするのに VPN アクセスが必要な場合も、この要件に変わりはありません。
  
> [!IMPORTANT]
> Microsoft は、Exchange Online Archiving サービスの正常性に悪影響を及ぼすクライアント ソフトウェアからの接続をブロックまたは制限する権利を有します。
  
## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook は、予定表作成、連絡先、タスクのサポートを含む多機能の電子メール プログラムです。Exchange Online Archiving は、Outlook 2013、Outlook 2010、Outlook 2007 をサポートします。主な機能には以下のものがあります。
  
- **Outlook Anywhere** Outlook Anywhere を使用すると、Outlook ユーザーは、VPN 接続を必要とせずに、インターネット経由で Exchange Server に接続し、Exchange Online アーカイブを使用することができます。 Outlook と Exchange Online Archiving 間の通信は、RPC-over-HTTP Windows ネットワーク コンポーネントを使用し、SSL で保護されたトンネルを介して行われます。    
- **自動検出** Exchange 自動検出サービスは、Exchange Online Archiving と連動するように Outlook を自動的に構成します。 自動検出を使用すると、Outlook ユーザーは、必要なプロファイル設定を Exchange から直接 (かつ固定した間隔で) 自分のメールアドレスとパスワードで受信することができます。 

Outlook 2010 以降および web 上の Outlook では、アーカイブのすべての機能に加えて、保持ポリシーやアーカイブポリシーなどの関連機能をユーザーに提供します。
  
Outlook 2007 はアーカイブの基本的なサポートを提供しますが、一部のアーカイブ機能とコンプライアンス機能が Outlook 2007 では使用できません。たとえば、Outlook 2007 では、ユーザーは、保持ポリシーやアーカイブ ポリシーをメールボックス内のアイテムに適用できません。代わりに、管理者によってプロビジョニングされるポリシーを使用する必要があります。Outlook 2007 ユーザーがアーカイブにアクセスするためには、2011 年 2 月の Office 2007 累積更新プログラムが必要です。
  
> [!NOTE]
> Outlook は Exchange Online Archiving に付属していません。 Microsoft 365 for enterprise (Microsoft Outlook を含む) は、一部のプランに含まれており、個別のサブスクリプションとして購入できます。 詳細については、「 [Microsoft 365 プランのオプション](../office-365-platform-service-description/office-365-plan-options.md)」を参照してください。 Microsoft 365 enterprise 用アプリの詳細については、「 [Office アプリケーションサービスの説明](../office-applications-service-description/office-applications-service-description.md)」を参照してください。 
  
### <a name="clients-supported-by-exchange-online-archiving"></a>Exchange Online Archiving でサポートされているクライアント

下の表に、Exchange Online Archiving でサポートされているクライアントを列挙します。
  
|**クライアント**|**EOA サポート**|
|:-----|:-----|
|Outlook 2013 以降  <br/> |Exchange Online Archiving の最新機能をサポートします。<sup>1</sup> <br/> |
|Outlook 2010  <br/> |は、2020年10月13日まで Exchange Online アーカイブの最新機能をサポートします。|
|Outlook 2007  <br/> |非サポート |
|Outlook 2003  <br/> |サポート対象外  <br/> |
|Outlook for Mac 2011  <br/> |サポート対象外  <br/> |
|Outlook for Mac  <br/> |サポート対象外 Exchange Online Archiving<sup>3</sup> <br/> |
|Microsoft Office Entourage 2008 Web Services Edition  <br/> |サポート対象外  <br/> |
|IMAP と POP  <br/> |サポート対象外  <br/> |
|Exchange ActiveSync (モバイルデバイス)  <br/> |サポート対象外  <br/> |
   
> [!NOTE]
> <sup>1</sup> Microsoft Office Standard に含まれている Outlook はサポートされていません。 詳細については、「 [個人用アーカイブおよびアイテム保持ポリシーのライセンス要件](https://support.office.com/article/Outlook-license-requirements-for-Exchange-features-46B6B7C5-C3CA-43E5-8424-1E2807917C99)」を参照してください。 <br/> 
<sup>2</sup> アーカイブサポートを有効にするには更新が必要です。 Outlook 2007 ユーザーは、アーカイブメールボックス内のアイテムの保持ポリシーまたはアーカイブポリシーを表示したり、適用したりすることはできません。管理者によってプロビジョニングされたポリシーに頼る必要があります。 また、Outlook 2007 ユーザーはオンプレミスのメールボックスとアーカイブを同時に検索することはできません。 <br/> 
<sup>3</sup> outlook 2016 for mac または Outlook for mac を使用して、フォルダー、予定表アイテム、連絡先、タスク、またはメモをアーカイブに移動またはコピーすることはできません。または、以前に他のバージョンの Outlook (outlook 2016 for Windows) を使用してアイテムが移動されていた場合は、アーカイブメールボックスに表示すること 詳細については、「 [Outlook 2016 For Mac でオンラインアーカイブを使用する](https://support.office.com/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238)」を参照してください。 

## <a name="outlook-on-the-web"></a>Web 上の Outlook

Outlook on the web は、Exchange Online と連携する Web ベースの Outlook 電子メール プログラムです。 自宅、オフィス、または外出先でインターネットに接続しているユーザーは、 &mdash; &mdash; Outlook on the web を使用して自分のメールにアクセスできます。
  
ユーザーはオンプレミスの web 上の Outlook にサインインして、自分のアーカイブにアクセスできます (同じ URL を使用)。 アーカイブは、Outlook on the web のプライマリメールボックスと共に表示されます。 Web 上の Outlook から直接アーカイブにアクセスする明示的な方法はありません。
  
## <a name="feature-availability"></a>機能の可用性

プラン、スタンドアロンのオプション、オンプレミスソリューション全体の機能の可用性を表示するには、「 [Exchange Online アーカイブサービスの説明](exchange-online-archiving-service-description.md)」を参照してください。