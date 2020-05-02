---
title: User account management
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-user-account-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: e7616079-5b13-4f1c-99ed-b20174e0808d
description: Microsoft は、ユーザーを作成、管理、および認証するための以下の方法をサポートしています。
ms.openlocfilehash: 7711a57247c20d7185e613d042791b089b01b483
ms.sourcegitcommit: f1322138cca22e4e1c640a31117f3b7999732b7a
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/01/2020
ms.locfileid: "44002314"
---
# <a name="user-account-management"></a>User account management

Microsoft は、ユーザーを作成、管理、および認証するための以下の方法をサポートしています。 
  
> [!NOTE]
> このトピックには、個別の Microsoft リソースへのアクセスを許可または禁止するセキュリティ機能 (Microsoft Exchange Online のロールベースのアクセス制御、Microsoft SharePoint Online でのセキュリティの構成など) に関する情報は含まれていません。 これらの機能の詳細については、「 [Exchange online サービスの説明](../exchange-online-service-description/exchange-online-service-description.md)」および「 [SharePoint online サービスの説明](../sharepoint-online-service-description/sharepoint-online-service-description.md)」を参照してください。 
  
管理タスクの実行に役立つツールについての情報が必要な場合は、「ツールを使用して[Microsoft アカウントを管理する](https://docs.microsoft.com/office365/enterprise/manage-office-365-accounts)」を参照してください。 日常の管理タスクを実行する方法については、「[一般的な管理タスク](https://docs.microsoft.com/office365/admin/manage/manage)」を参照してください。
  
## <a name="need-help-signing-in-installing-or-uninstalling-or-canceling-your-subscription"></a>サインイン、インストール、アンインストール、またはサブスクリプションのキャンセルについてヘルプが必要ですか?

Office | を[インストールまたはアンインストールする](https://support.office.com/article/download-and-install-or-reinstall-office-365-or-office-2019-on-a-pc-or-mac-4414eaaf-0478-48be-9c42-23adc4716658)際[のサインインに](https://support.office.com/article/where-to-sign-in-to-office-365-for-business-e9eb7d51-5430-4929-91ab-6157c5a050b4) | 関するヘルプを取得する ([office をキャンセル](https://support.office.com/article/Cancel-Office-365-for-business-b1bc0bef-4608-4601-813a-cdd9f746709a)する) 365
  
その他の問題については、 [Microsoft サポートセンター](https://support.microsoft.com/contactus/)を参照してください。 中国の 21Vianet が運用している Office 365 に対するサポートを受けるには、[21Vianet サポート チーム](https://support.office.com/article/Get-technical-billing-and-subscription-support-for-Office-365-operated-by-21Vianet-671FB12E-F5D8-4CDF-B3E9-E8068A9AA496)にお問い合わせください。 Office 365 Germany の場合、[Office 365 Germany サポート チーム](https://support.office.com/article/Get-technical-and-billing-support-for-Office-365-Germany-83ef2266-2543-48d7-a41a-1b56b403a8e9?ui=en-US&amp;rs=en-US&amp;ad=US&amp;fromAR=1)にお問い合わせください。 
  
## <a name="sign-in-options"></a>サインイン オプション

Microsoft には、ユーザー id として使用できる2つのシステムがあります。
  
- **職場または学校のアカウント (クラウド id)** ユーザーは、Microsoft クラウドサービスにサインインするために、他のデスクトップや企業の資格情報とは別に、Azure Active Directory クラウドの資格情報を受け取ります。 これは既定の ID で、展開の複雑さを最小にするためにこの ID を使用することをお勧めします。 職場または学校のアカウント用のパスワードは、Azure Active Directory [ パスワード ポリシー ](https://docs.microsoft.com/previous-versions/azure/jj943764(v=azure.100)) を使用します。
    
- **フェデレーションアカウント (フェデレーション id)** シングルサインオン (SSO) を使用するオンプレミスの Active Directory を持つ組織内のすべてのサブスクリプションについて、ユーザーは Active Directory 資格情報を使用して Microsoft サービスにサインインできます。 会社の Active Directory は、パスワード ポリシーを格納し制御します。 SSO の詳細については、「 [シングル サインオンのロードマップ](https://docs.microsoft.com/previous-versions/azure/azure-services/hh967643(v=azure.100))」を参照してください。
    
ID の種類は、ユーザー エクスペリエンスおよびユーザー アカウントの管理オプションに加えて、ハードウェアとソフトウェアの要件や、展開に関する他の検討事項にも影響します。
  
### <a name="custom-domains-and-identity-options"></a>カスタム ドメインと ID オプション

新しいユーザーを作成すると、ユーザーのサインイン名と電子メールアドレスが、Microsoft 365 管理センターで設定されている既定のドメインに割り当てられます。 詳細については、「[ユーザーとドメインを追加](https://support.office.com/article/Add-your-users-and-domain-to-Office-365-6383f56d-3d09-4dcb-9b41-b5f5a5efd611)する」を参照してください。 
  
既定では、サブスクリプションは、 \<アカウントを使用して作成された\> **onmicrosoft.com**ドメインを使用し_ます。_\* Onmicrosoft.com ドメインを保持するのではなく、1つ以上のカスタムドメインを Microsoft に追加し、検証済みのドメインのいずれかでサインインするようにユーザーを割り当てることができます。 Each user's assigned domain is the email address that will appear on sent and received email messages. 
  
最大900の登録済みインターネットドメインをホストでき、それぞれ異なる名前空間で表されます。 
  
シングルサインオンを使用する組織では、ドメイン上のすべてのユーザーが同じ id システムを使用する必要があります。これは、クラウド id とフェデレーション id のどちらかです。 たとえば、クラウド id のみを必要とするユーザーグループを1つ持つことができます。これは、オンプレミスのシステムにアクセスせず、Microsoft とオンプレミスのシステムを使用しているユーザーの別のグループです。 Contractors.contoso.com や staff.contoso.com などの2つのドメインを Office 365 に追加し、そのうち1つの SSO のみを設定します。 ドメイン全体を、クラウド id からフェデレーション id に変換するか、フェデレーション id からクラウド id に変換することができます。
  
Office 365 におけるドメインの詳細については、「[ドメイン](domains.md)」のサービスの説明を参照してください。 
  
\* 中国で 21Vianet が運用している Office 365 を使用している場合、既定のドメインは、\<companyname\> **.onmsChina.cn** です。Office 365 Germany を使用している場合の既定ドメインは、\<companyname\> **.onmicrosoft.de** です。
  
## <a name="authentication"></a>認証

SharePoint Online で作成された匿名アクセスのインターネットサイトは例外として、Microsoft サービスへのアクセス時にユーザーを認証する必要があります。 
  
- **先進認証**: 先進認証によって、各種プラットフォームにおける Office クライアント アプリへの Active Directory 認証ライブラリ (ADAL) ベースのサインインを行えます。 これにより、多要素認証 (MFA) によるサインイン、SAML ベースのサードパーティ製 ID プロバイダーから Office クライアント アプリケーションへのサインイン、スマート カードや証明書をベースとする認証機能を使用したサインインなどが可能になります。 また、Microsoft Outlook を使用していなくても基本認証プロトコルを使用できるようになります。 Office アプリケーション間での先進認証の可用性を含む詳細については、「 [office 2013 および office 2016 クライアントアプリでの先進認証のしくみ](https://docs.microsoft.com/office365/enterprise/modern-auth-for-office-2013-and-2016)」を参照してください。
    
    モダン認証は、Exchange Online では既定でオンになっています。 この機能をオンまたはオフにする方法については、「 [Exchange Online で先進認証を有効](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/enable-or-disable-modern-authentication-in-exchange-online)にする」を参照してください。
    
- **クラウド id 認証**クラウド id を持つユーザーは、従来のチャレンジ/レスポンスを使用して認証されます。 Web ブラウザーが Microsoft サインインサービスにリダイレクトされ、職場または学校のアカウントのユーザー名とパスワードを入力します。 サインインサービスは、資格情報を認証し、サービストークンを生成します。これにより、要求されたサービスに web ブラウザーがポストし、ログインします。 
    
- **フェデレーション id 認証**フェデレーション id を持つユーザーは、Active Directory フェデレーションサービス (AD FS) 2.0 またはその他のセキュリティトークンサービスを使用して認証されます。 Web ブラウザーは Microsoft サインインサービスにリダイレクトされ、ユーザープリンシパル名 (UPN) の形式で会社 ID を入力します (たとえば、isabel@contoso.com)。 サインインサービスは、フェデレーションドメインの一部であることを確認し、認証のためにオンプレミスのフェデレーションサーバーにリダイレクトすることを提供します。 デスクトップ (ドメインに参加) にログオンしている場合は、(Kerberos または NTLMv2 を使用して) 認証され、オンプレミスのセキュリティトークンサービスによって、web ブラウザーが Microsoft サインインサービスにポストするログオントークンが生成されます。 サインインサービスは、ログオントークンを使用して、web ブラウザーが要求されたサービスにポストしてログインするサービストークンを生成します。 利用可能なセキュリティトークンサービスの一覧については、「[シングルサインオンのロードマップ](https://docs.microsoft.com/previous-versions/azure/azure-services/hh967643(v=azure.100))」を参照してください。
    
Microsoft では、フォームベース認証を使用しており、ネットワーク経由の認証トラフィックは、ポート443を使用して常に TLS/SSL で暗号化されています。 認証トラフィックは、Microsoft サービスの帯域幅の無視率を無視します。 
  
### <a name="multi-factor-authentication"></a>多要素認証

多要素認証を使用する場合、ユーザーは、パスワードを正確に入力した後に、スマートフォンで電話、テキストメッセージ、またはアプリの通知に同意する必要があります。 Only after this second authentication can the user sign in. Microsoft 管理者は、Microsoft 365 管理センターで多要素認証のためにユーザーを登録することができます。 [多要素認証](https://docs.microsoft.com/office365/admin/security-and-compliance/set-up-multi-factor-authentication)の詳細について説明します。
  
### <a name="rich-client-authentication"></a>リッチ クライアント認証

Microsoft Office デスクトップ アプリケーションなどのリッチ クライアントの場合、2 つの方法で認証を実行できます。
  
- **Microsoft Online Services サインインアシスタント**デスクトップセットアップによってインストールされるサインインアシスタントには、サインインサービスからサービストークンを取得してリッチクライアントに返すクライアントサービスが含まれています。 
    
  - クラウド id がある場合は、資格情報の入力を求めるプロンプトが表示されます。これは、認証のためにクライアントサービスがサインインサービスに送信します (WS-TRUST を使用)。
    
  - フェデレーション id がある場合、クライアントサービスは最初に AD FS 2.0 サーバーに接続して資格情報を認証し (Kerberos または NTLMv2 を使用)、サインインサービスに送信されるログオントークンを取得します (WS-FEDERATION および WS-TRUST を使用)。
    
- **SSL による基本/プロキシ認証** Outlook クライアントは、基本認証の資格情報を SSL で Exchange Online に送ります。 Exchange Online は、認証要求を id プラットフォームに、次にオンプレミスの Active Directory フェデレーションサーバー (SSO の場合) にプロキシします。 
    
Microsoft サービスを適切に検出して認証するために、管理者は、リッチクライアント (Microsoft Office 2010 など) を使用する各ワークステーションに一連のコンポーネントと更新プログラムを適用し、Office 365 に接続する必要があります。 デスクトップのセットアップは、必要な更新プログラムを備えたワークステーションを構成するための自動ツールです。 詳細については、「[現在の Office デスクトップアプリを使用する](https://support.office.com/article/set-up-office-2010-desktop-programs-to-work-with-office-365-for-business-3324b8b8-dceb-45e2-ac24-c642720108f7?ocmsassetID=HA102817827&CorrelationId=8eb1b198-827a-4999-a584-05a05a92d224&ui=en-US&rs=en-US&ad=US)」を参照してください。
  
### <a name="sign-in-experience"></a>サインイン方法

サインイン時の動作は、使用中の id の種類に応じて変わります。
  
||**クラウド ID**|**フェデレーション ID**|
|:-----|:-----|:-----|
|Outlook 2016  <br/> |セッションごとにサインイン <sup>1</sup> <br/> |セッションごとにサインイン <sup>2</sup> <br/> |
|Outlook 2013  <br/> |セッションごとにサインイン <sup>1</sup> <br/> |セッションごとにサインイン <sup>2</sup> <br/> |
|Windows 7 で Outlook 2010 または Office 2007 を使用  <br/> |セッションごとにサインイン <sup>1</sup> <br/> |セッションごとにサインイン <sup>2</sup> <br/> |
|Windows Vista で Outlook 2010 または Office Outlook 2007 を使用  <br/> |セッションごとにサインイン <sup>1</sup> <br/> |セッションごとにサインイン <sup>2</sup> <br/> |
|Microsoft Exchange ActiveSync  <br/> |セッションごとにサインイン <sup>1</sup> <br/> |セッションごとにサインイン <sup>2</sup> <br/> |
|POP、IMAP、Outlook for Mac  <br/> |セッションごとにサインイン <sup>1</sup> <br/> |セッションごとにサインイン <sup>2</sup> <br/> |
|Web エクスペリエンス: Microsoft 365 管理センター/Outlook on the web/SharePoint Online/Office for web  <br/> |ブラウザー セッションごとにサインイン <sup>4</sup> <br/> |セッションごとにサインイン <sup>3</sup> <br/> |
|SharePoint Online で Office 2010 または Office 2007 を使用  <br/> |SharePoint Online セッションごとにサインイン <sup>4</sup> <br/> |SharePoint Online セッションごとにサインイン <sup>3</sup> <br/> |
|Skype for Business Online  <br/> |セッションごとにサインイン <sup>1</sup> <br/> |プロンプトなし  <br/> |
|Outlook for Mac  <br/> |セッションごとにサインイン <sup>1</sup> <br/> |セッションごとにサインイン <sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup>最初にメッセージが表示されたら、パスワードを保存して後で使用できます。 パスワードを変更するまで、別のプロンプトを受け取ることはありません。 <br/> 
<sup>2</sup>会社の資格情報を入力します。 パスワードを保存することはできますが、パスワードが変更されるまで、再度メッセージは表示されません。 <br/> 
<sup>3</sup>すべてのアプリで、サインインするユーザー名を入力または選択する必要があります。 コンピューターがドメインに参加している場合は、パスワードの入力は要求されません。 [サインアウトし**ない] を選択すると、** サインアウトするまで、再度メッセージは表示されません。 <br/> 
<sup>4</sup> [サインインを**維持**する] を選択すると、サインアウトするまで、再度メッセージは表示されません。 
  
## <a name="creating-user-accounts"></a>ユーザー アカウントの作成

ユーザーを追加する方法は複数あります。 詳細については、「ユーザーを個別に追加する」、[または](https://docs.microsoft.com/office365/admin/add-users/add-users)「 [Microsoft 365 管理センタープレビューでユーザーを追加、削除、管理](https://support.office.com/article/add-remove-and-manage-users-in-the-new-office-365-admin-center-6e80db58-c36b-4add-b1c8-cc5135f111f3?amp%3Bclcid=0x409&ui=en-US&rs=en-US&ad=US)する」を参照してください。 中国で運用している Office 365 を使用している場合は、「[21Vianet が運用している Office 365 でユーザー アカウントを作成または編集する - 管理者向けヘルプ](https://docs.microsoft.com/office365/admin/add-users/add-users)」を参照してください。
  
## <a name="deleting-accounts"></a>アカウントの削除

アカウントを削除する方法は、ディレクトリ同期を使用しているかどうかによって異なります。 
  
- ディレクトリ同期を使用していない場合は、管理ページまたは Windows PowerShell を使用してアカウントを削除できます。
    
- ディレクトリ同期を使用している場合は、Office 365 ではなく、ローカルの Active Directory からユーザーを削除する必要があります。
    
アカウントは、削除されると非アクティブになります。 削除後約 30 日間は、アカウントを復元することができます。 アカウントの削除と復元の詳細については、「[ユーザーを削除](https://docs.microsoft.com/office365/admin/add-users/delete-a-user)して[ユーザーを復元](https://docs.microsoft.com/office365/admin/add-users/restore-user)する」または「中国で21Vianet が運営する office 365 を使用している場合は、「 [Create Or edit user accounts in Office 365](https://docs.microsoft.com/office365/admin/add-users/add-users)」を参照してください。
  
## <a name="password-management"></a>パスワードの管理

パスワード管理のポリシーと手順は、ID システムによって異なります。
  
 **クラウド ID パスワードの管理:**
  
クラウド ID を使用する場合、パスワードは、アカウントが作成されたときに自動的に生成されます。
  
- クラウド ID パスワードの強度要件の詳細については、「[パスワード ポリシー](https://docs.microsoft.com/previous-versions/azure/jj943764(v=azure.100))」を参照してください。
    
- セキュリティを強化するには、ユーザーが最初に Microsoft サービスにアクセスするときにパスワードを変更する必要があります。 そのため、ユーザーが Microsoft サービスにアクセスできるようにするには、Microsoft 365 管理センターにサインインし、パスワードを変更するように求めるメッセージが表示される必要があります。
    
- 管理者は、パスワード有効期限ポリシーを設定できます。詳しくは、「[組織のパスワード有効期限ポリシーを設定します。](https://docs.microsoft.com/office365/admin/manage/set-password-expiration-policy)」を参照してください。
    
クラウド ID を持つユーザーのパスワードを再設定するには、いくつか方法があります。
  
- **管理者**によるパスワードのリセットユーザーが自分のパスワードを紛失または忘れた場合、管理者は管理センターで、または Windows PowerShell を使用してユーザーのパスワードをリセットすることができます。 ユーザーは、自分の現在のパスワードを知っている場合に、自分のパスワードだけを変更できます。 
    
    エンタープライズプランでは、管理者がパスワードを紛失または忘れた場合、グローバル管理者の役割を持つ別の管理者が、Microsoft 365 管理センターまたは Windows PowerShell を使用して、管理者のパスワードを再設定することができます。 詳細については、「[Office 365 の管理者パスワードを再設定する](https://docs.microsoft.com/office365/admin/add-users/reset-passwords)」を参照してください。 中国で 21Vianet が運用している Office 365 で作業している場合は、「[21Vianet が運用している Office 365 でパスワードを変更または再設定する](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b)」を参照してください。
    
- **ユーザーが Outlook on the web を使用してパスワードを変更する**Outlook on the web オプションページには、[パスワードの変更] ハイパーリンクが含まれています。これにより、ユーザーは [**パスワードの変更**] ページにリダイレクトされます。 ユーザーは、以前のパスワードを知っている必要があります。 詳細については、「 [Outlook Web アプリでパスワードを変更する](https://support.office.com/article/change-password-in-outlook-web-app-50bb1309-6f53-4c24-8bfd-ed24ca9e872c)」を参照してください。 中国で 21Vianet が運用している Office 365 を使用している場合は、「[21Vianet が運用している Office 365 でパスワードを変更または再設定する](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b)」を参照してください。
    
- **ロールベースのパスワードのリセット権限**エンタープライズプランでは、ヘルプデスクスタッフなどの承認されたユーザーに、[**パスワードのリセット**] ユーザー権限と、完全なサービス管理者ではなく、定義済みまたはカスタムの役割を使用してパスワードを変更する権限を割り当てることができます。 既定では、Enterprise プランの場合、全体管理者、パスワード管理者、またはユーザー管理の管理者の役割が割り当てられた管理者がパスワードを変更できます。 詳細については、「 [一般法人向け Office 365 で管理者ロールを割り当てる](https://docs.microsoft.com/office365/admin/add-users/assign-admin-roles)」を参照してください。
    
- **Windows PowerShell を使用してパスワードを再設定する** サービス管理者は、Windows PowerShell を使用してパスワードを再設定することができます。 
    
 **フェデレーション ID パスワードの管理:**
  
フェデレーション ID を使用する場合、パスワードは Active Directory で管理されます。 社内セキュリティトークンサービスは、ユーザーのローカル Active Directory パスワードをインターネット経由で Office 365 に渡しずに、フェデレーションゲートウェイとの認証をネゴシエートします。 ローカル パスワード ポリシーを使用するか、Web クライアントの場合には 2 要素認証を使用します。 Outlook on the web には、パスワードの変更ハイパーリンクは含まれていません。 ユーザーは、標準の社内ツールを使用して、またはデスクトップ PC のログオン オプションでパスワードを変更します。
  
組織環境で[シングルサインオン (SSO)](https://docs.microsoft.com/previous-versions/azure/azure-services/dn441213(v=azure.100))が有効になっていて、フェデレーション id プロバイダーに影響する停止が発生している場合、フェデレーションサインインのパスワード同期バックアップでは、ドメインを手動でパスワード同期に切り替えるオプションが提供されます。パスワード同期を使用すると、停止が修正されている間、ユーザーがアクセスできるようになります。 パスワード同期を使用すると、ユーザーは停止の修復作業中でも Office 365 にアクセスできます。[シングル サインオンからパスワード同期に切り替える方法](https://go.microsoft.com/fwlink/p/?LinkId=509832)をご確認ください。
  
## <a name="license-management"></a>ライセンス管理

ライセンスは、Microsoft サービスのセットへのユーザーアクセスを提供します。 管理者は、必要なサービスにアクセスするためのライセンスを各ユーザーに割り当てます。 たとえば、Skype for Business Online へのアクセス権は割り当て、SharePoint Online へのアクセス権は割り当てないということができます。
  
Microsoft billing 管理者は、ユーザーライセンス数や会社が使用する追加サービス数などのサブスクリプションの詳細を変更できます。 [[ライセンスの割り当てまたは削除を](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users)確認します。 中国で 21Vianet が運用している Office 365 を使用している場合は、「[21Vianet が運用している Office 365 でライセンスの割り当てまたは削除を行う](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users)」を参照してください。
  
## <a name="group-management"></a>グループの管理

SharePoint Online では、セキュリティ グループを使用してサイトへのアクセスを制御します。 セキュリティグループは、Microsoft 365 管理センターで作成できます。 セキュリティ グループの詳細については、「[セキュリティ グループを作成、編集、削除する](https://docs.microsoft.com/office365/admin/email/create-edit-or-delete-a-security-group)」を参照してください。
  
## <a name="administrator-roles"></a>管理者の役割

Office 365 Enterprise は、ロールベースのアクセス制御 (RBAC) モデルを採用しています。そのため、アクセス許可や機能は、管理の役割によって定義されます。自分の組織の Office 365 にサインアップしたユーザーが、自動的に全体管理者または最上位管理者になります。管理者の役割には、全体管理者、課金管理者、パスワード管理者、サービス管理者、およびユーザー管理の管理者の 5 つがあります。管理者の役割を Exchange Online、SharePoint Online、および Skype for Business Online の管理に適用する方法など、Office 365 Enterprise の管理者役割の詳細については、「[一般法人向け Office 365 で管理者ロールを割り当てる](https://docs.microsoft.com/previous-versions/windows/it-pro/windows-server-2012-R2-and-2012/jj878348(v=ws.11))」を参照してください。中国で 21Vianet が運用している Office 365 を使用している場合は、「[一般法人向け Office 365 で管理者ロールを割り当てる](https://docs.microsoft.com/office365/admin/add-users/assign-admin-roles)」を参照してください。
  
## <a name="delegated-administration-and-support-for-partners"></a>代理管理とパートナーのサポート

顧客に代わってアカウントを管理する権限をパートナーに付与することができます。 お客様はパートナーが使用するユーザーアカウントを必要とせず、委任された管理権限を付与する際にライセンスを消費することはありません。 パートナーは、無制限のアクセスまたは制限付きのアクセスを組織内のユーザーに割り当てることができます。 制限付きのアクセスには、パスワードの再設定、サービス リクエストの管理、およびサービス正常性の監視などの権限が含まれます。 
  
> [!NOTE]
> 代理管理者としてパートナーを使用および指定できるかどうかは、地域によって異なります。 
  
## <a name="azure-active-directory-services"></a>Azure Active Directory サービス

Azure Active Directory (AD) は、Office 365 に対して包括的な ID およびアクセス管理の機能を提供します。開発者のために、ディレクトリ サービス、高度な ID ガバナンス、アプリケーション アクセス管理、機能豊富な標準ベースのプラットフォームを組み合わせています。Office 365 における AD 機能について詳しくは、「[サインイン ページのブランド化とクラウド ユーザーのセルフサービスによるパスワードのリセット](https://www.microsoft.com/en-us/microsoft-365/blog/2015/02/17/sign-page-branding-cloud-user-self-service-password-reset-office-365/)」をご覧ください。[Azure Active Directory のエディション](https://msdn.microsoft.com/library/azure/dn532272.aspx)の詳細をご確認ください。 
  
## <a name="feature-availability"></a>機能の可用性

プラン、スタンドアロンのオプション、オンプレミスソリューション全体の機能の可用性を表示するには、「 [Microsoft 365 And Office 365 platform service description](office-365-platform-service-description.md)」を参照してください。
  
