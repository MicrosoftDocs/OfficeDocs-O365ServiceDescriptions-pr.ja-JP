---
title: User account management
ms.author: office365servicedesc
author: pamelaar
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
description: Microsoft では、ユーザーの作成、管理、および認証を行う次の方法がサポートされています。
ms.openlocfilehash: 31fe2a1df472b6fc22df5cb7ff29b8658519cbc7
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/24/2021
ms.locfileid: "51172782"
---
# <a name="user-account-management"></a>User account management

Microsoft では、ユーザーの作成、管理、および認証を行う次の方法がサポートされています。 
  
> [!NOTE]
> このトピックには、個々の Microsoft リソースへのアクセスを許可または禁止するセキュリティ機能 (Microsoft Exchange Online での役割ベースのアクセス制御、Microsoft SharePoint Online でのセキュリティの構成など) については説明します。 これらの機能の詳細については [、「Exchange Online](../exchange-online-service-description/exchange-online-service-description.md) サービスの説明」および [「SharePoint Online サービスの説明」を参照してください](../sharepoint-online-service-description/sharepoint-online-service-description.md)。 
  
管理タスクの実行に役立つツールに関する情報が必要な場合は、「Microsoft アカウントを管理するための [ツール」を参照してください](/office365/enterprise/manage-office-365-accounts)。 毎日の管理タスクを実行する方法については、「一般的な管理タスク [」を参照してください](/office365/admin/manage/manage)。
  
## <a name="need-help-with-signing-in-installing-or-uninstalling-or-canceling-your-subscription"></a>サブスクリプションへのサインイン、インストールまたはアンインストール、またはキャンセルに関するヘルプが必要ですか?

ヘルプを表示する[](https://support.office.com/article/where-to-sign-in-to-office-365-for-business-e9eb7d51-5430-4929-91ab-6157c5a050b4):  |  [](https://support.office.com/article/download-and-install-or-reinstall-office-365-or-office-2019-on-a-pc-or-mac-4414eaaf-0478-48be-9c42-23adc4716658)[365 のインストールとアンインストールOffice  |  [キャンセルOfficeサインイン](https://support.office.com/article/Cancel-Office-365-for-business-b1bc0bef-4608-4601-813a-cdd9f746709a)する
  
その他の問題については、Microsoft サポート [センターをご覧ください](https://support.microsoft.com/contactus/)。 中国の 21Vianet が運用している Office 365 に対するサポートを受けるには、[21Vianet サポート チーム](https://support.office.com/article/Get-technical-billing-and-subscription-support-for-Office-365-operated-by-21Vianet-671FB12E-F5D8-4CDF-B3E9-E8068A9AA496)にお問い合わせください。 Office 365 Germany の場合、[Office 365 Germany サポート チーム](https://support.office.com/article/83ef2266-2543-48d7-a41a-1b56b403a8e9)にお問い合わせください。 
  
## <a name="sign-in-options"></a>サインイン オプション

Microsoft には、ユーザー ID に使用できる 2 つのシステムがあります。
  
- **仕事または学校のアカウント (クラウド ID)** - ユーザーは、Microsoft クラウド サービスにサインインするための Azure Active Directory クラウド資格情報 (他のデスクトップまたは企業の資格情報とは別) を受け取る。 これは既定の ID で、展開の複雑さを最小にするためにこの ID を使用することをお勧めします。 職場または学校のアカウント用のパスワードは、Azure Active Directory [ パスワード ポリシー ](/previous-versions/azure/jj943764(v=azure.100)) を使用します。
    
- フェデレーション アカウント (フェデレーション ID) - シングル サインオン **(SSO)** を使用するオンプレミスの Active Directory を持つ組織のすべてのサブスクリプションについて、ユーザーは Active Directory 資格情報を使用して Microsoft サービスにサインインできます。 会社の Active Directory は、パスワード ポリシーを格納し制御します。 SSO の詳細については、「 [シングル サインオンのロードマップ](/previous-versions/azure/azure-services/hh967643(v=azure.100))」を参照してください。
    
ID の種類は、ユーザー エクスペリエンスおよびユーザー アカウントの管理オプションに加えて、ハードウェアとソフトウェアの要件や、展開に関する他の検討事項にも影響します。
  
### <a name="custom-domains-and-identity-options"></a>カスタム ドメインと ID オプション

新しいユーザーを作成すると、Microsoft 365 管理センターで設定されている既定のドメインにユーザーのサインイン名と電子メール アドレスが割り当てられます。 詳細については、「Add [your users and domain」を参照してください](https://support.office.com/article/Add-your-users-and-domain-to-Office-365-6383f56d-3d09-4dcb-9b41-b5f5a5efd611)。 
  
既定では、サブスクリプションは、アカウント< > **された会社名 .onmicrosoft.com** ドメインを使用します。 中国で 21Vianet Office 365 を使用している場合、既定のドメインは会社< > **.onmsChina.cn です**。 365 ドイツOffice使用している場合、既定のドメインは会社< > **.onmicrosoft.de** です。 onmicrosoft.com ドメインを保持するのではなく **、1** つ以上のカスタム ドメインを Microsoft に追加し、検証済みドメインのいずれかを使用してサインインするユーザーを割り当てできます。 Each user's assigned domain is the email address that will appear on sent and received email messages. 
  
最大 900 の登録済みインターネット ドメインをホストできます。それぞれが異なる名前空間で表されます。 
  
シングル サインオンを使用している組織の場合、ドメイン上のすべてのユーザーは、クラウド ID またはフェデレーション ID という同じ ID システムを使用する必要があります。 たとえば、オンプレミス システムにアクセスしないのでクラウド ID のみを必要とするユーザーのグループと、Microsoft およびオンプレミス システムを使用する別のユーザー グループを作成できます。 365 に 2 つのOffice **(contractors.contoso.com** や staff.contoso.com など)を追加し、その 1 つのドメインにのみ SSO を設定します。 ドメイン全体をクラウド ID からフェデレーション ID に、またはフェデレーション ID からクラウド ID に変換できます。
  
Office 365 におけるドメインの詳細については、「[ドメイン](domains.md)」のサービスの説明を参照してください。 
  
## <a name="authentication"></a>認証

SharePoint Online で作成された匿名アクセスのインターネット サイトを除き、ユーザーは Microsoft サービスにアクセスするときに認証する必要があります。 
  
- **モダン認証** - モダン認証を使用すると、Microsoft 認証ライブラリベースのサインインが、プラットフォームOfficeクライアント アプリに追加されます。 これにより、多要素認証 (MFA) によるサインイン、SAML ベースのサードパーティ製 ID プロバイダーから Office クライアント アプリケーションへのサインイン、スマート カードや証明書をベースとする認証機能を使用したサインインなどが可能になります。 また、Microsoft Outlook を使用していなくても基本認証プロトコルを使用できるようになります。 Office アプリケーション間でのモダン認証の可用性などの詳細については、「Office 2013 および Office クライアント アプリの最新の認証のしくみ」を [参照してください](/office365/enterprise/modern-auth-for-office-2013-and-2016)。
    
    Exchange Online では、最新の認証が既定でオンになっています。 有効または無効にする方法については、「Exchange Online でモダン認証を有効 [にする」を参照してください](/exchange/clients-and-mobile-in-exchange-online/enable-or-disable-modern-authentication-in-exchange-online)。
    
- **クラウド ID 認証** - クラウド ID を持つユーザーは、従来のチャレンジ/応答を使用して認証されます。 Web ブラウザーは Microsoft サインイン サービスにリダイレクトされ、仕事用または学校用のアカウントのユーザー名とパスワードを入力します。 サインイン サービスは、資格情報を認証し、Web ブラウザーが要求されたサービスに投稿してログインするサービス トークンを生成します。 
    
- **フェデレーション ID 認証** - フェデレーション ID を持つユーザーは、Active Directory フェデレーション サービス (AD FS) 2.0 または他のセキュリティ トークン サービスを使用して認証されます。 Web ブラウザーは Microsoft サインイン サービスにリダイレクトされ、ユーザー プリンシパル名 (UPN) という形式で会社 ID を入力します。たとえば、次の *isabel@contoso.com。* サインイン サービスは、フェデレーション ドメインの一部と判断し、認証のためにオンプレミスのフェデレーション サーバーにリダイレクトする機能を提供します。 デスクトップ (ドメインに参加している) にログオンしている場合は、(Kerberos または NTLMv2 を使用して) 認証され、オンプレミスのセキュリティ トークン サービスによってログオン トークンが生成され、Web ブラウザーが Microsoft サインイン サービスに投稿します。 サインイン サービスは、ログオン トークンを使用して、Web ブラウザーが要求されたサービスに投稿し、ログインするサービス トークンを生成します。 使用可能なセキュリティ トークン サービスの一覧については、「シングル サインオン [ロードマップ」を参照してください](/previous-versions/azure/azure-services/hh967643(v=azure.100))。
    
Microsoft はフォーム ベース認証を使用し、ネットワーク上の認証トラフィックは常にポート 443 を使用して TLS/SSL で暗号化されます。 認証トラフィックは、Microsoft サービスの帯域幅のごくわずかの割合を使用します。 
  
### <a name="multi-factor-authentication"></a>多要素認証

多要素認証では、ユーザーはパスワードを正しく入力した後、スマートフォンで電話、テキスト メッセージ、またはアプリ通知を確認する必要があります。 Only after this second authentication can the user sign in. Microsoft 管理者は、Microsoft 365 管理センターで多要素認証のためにユーザーを登録できます。 多要素認証 [の詳細については、次のページを参照してください](/office365/admin/security-and-compliance/set-up-multi-factor-authentication)。
  
### <a name="rich-client-authentication"></a>リッチ クライアント認証

Microsoft Office デスクトップ アプリケーションなどのリッチ クライアントの場合、2 つの方法で認証を実行できます。
  
- **Microsoft Online Services Sign-In アシスタント** - デスクトップ セットアップによってインストールされるサインイン アシスタントには、サインイン サービスからサービス トークンを取得し、リッチ クライアントに返すクライアント サービスが含まれます。 
    
  - クラウド ID がある場合は、資格情報の入力を求めるプロンプトが表示され、クライアント サービスは (WS-Trust を使用して) 認証のためにサインイン サービスに送信します。
    
  - フェデレーション ID がある場合、クライアント サービスは最初に AD FS 2.0 サーバーに連絡して資格情報 (Kerberos または NTLMv2 を使用) を認証し、サインイン サービス (WS-Federation と WS-Trust を使用) に送信されるログオン トークンを取得します。
    
- **SSL を使用した基本/プロキシ認証** - Outlook クライアントは、SSL を使用して基本認証資格情報を Exchange Online に渡します。 Exchange Online は認証要求を ID プラットフォームにプロキシし、次にオンプレミスの Active Directory フェデレーション サーバー (SSO 用) にプロキシします。 
    
Microsoft サービスの適切な検出と認証を行う場合、管理者は、リッチ クライアント (Microsoft Office 2010 など) を使用し、Office 365 に接続する各ワークステーションにコンポーネントと更新プログラムのセットを適用する必要があります。 デスクトップセットアップは、必要な更新プログラムを使用してワークステーションを構成する自動化されたツールです。 詳細については、「現在のデスクトップ アプリ [を使用するOfficeを参照してください](https://support.office.com/article/3324b8b8-dceb-45e2-ac24-c642720108f7)。
  
### <a name="sign-in-experience"></a>サインイン方法

サインイン エクスペリエンスは、使用されている ID の種類に応じて変わります。<br><br>
  
| サービス | クラウド ID | フェデレーション ID |
|:-----|:-----|:-----|
|Outlook 2016  <br/> |セッションごとにサインイン <sup>1</sup> <br/> |セッションごとにサインイン <sup>2</sup> <br/> |
|Outlook 2013  <br/> |セッションごとにサインイン <sup>1</sup> <br/> |セッションごとにサインイン <sup>2</sup> <br/> |
|Windows 7 で Outlook 2010 または Office 2007 を使用  <br/> |セッションごとにサインイン <sup>1</sup> <br/> |セッションごとにサインイン <sup>2</sup> <br/> |
|Windows Vista で Outlook 2010 または Office Outlook 2007 を使用  <br/> |セッションごとにサインイン <sup>1</sup> <br/> |セッションごとにサインイン <sup>2</sup> <br/> |
|Microsoft Exchange ActiveSync  <br/> |セッションごとにサインイン <sup>1</sup> <br/> |セッションごとにサインイン <sup>2</sup> <br/> |
|POP、IMAP、Outlook for Mac  <br/> |セッションごとにサインイン <sup>1</sup> <br/> |セッションごとにサインイン <sup>2</sup> <br/> |
|Web エクスペリエンス: Microsoft 365 管理センター / Outlook on the web/ SharePoint Online / Office Web 用  <br/> |ブラウザー セッションごとにサインイン <sup>4</sup> <br/> |セッションごとにサインイン <sup>3</sup> <br/> |
|SharePoint Online で Office 2010 または Office 2007 を使用  <br/> |SharePoint Online セッションごとにサインイン <sup>4</sup> <br/> |SharePoint Online セッションごとにサインイン <sup>3</sup> <br/> |
|Skype for Business Online  <br/> |セッションごとにサインイン <sup>1</sup> <br/> |プロンプトなし  <br/> |
|Outlook for Mac  <br/> |セッションごとにサインイン <sup>1</sup> <br/> |セッションごとにサインイン <sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> 最初にメッセージが表示されたら、将来の使用のためにパスワードを保存できます。 パスワードを変更するまで、別のプロンプトを受け取ることはありません。 <br/> 
<sup>2</sup> 会社の資格情報を入力します。 パスワードを保存すると、パスワードが変更されるまで再びメッセージが表示されません。 <br/> 
<sup>3</sup> すべてのアプリで、サインインするユーザー名を入力または選択する必要があります。 コンピューターがドメインに参加している場合は、パスワードの入力は要求されません。 [サインインして **保持する] を** 選択した場合は、サインアウトするまで再びメッセージが表示されません。 <br/> 
<sup>4</sup> [サインインした状態に **保** つ] を選択すると、サインアウトするまで再びメッセージが表示されません。 
  
## <a name="create-user-accounts"></a>Create user accounts

ユーザーを追加する方法は複数あります。 詳細については、「ユーザーを個別または一括で追加する [-](/office365/admin/add-users/add-users) [Microsoft 365](https://support.office.com/article/6e80db58-c36b-4add-b1c8-cc5135f111f3)管理センター プレビューでユーザーを追加、削除、管理する 」を参照してください。 中国で運用している Office 365 を使用している場合は、「[21Vianet が運用している Office 365 でユーザー アカウントを作成または編集する - 管理者向けヘルプ](/office365/admin/add-users/add-users)」を参照してください。
  
## <a name="delete-user-accounts"></a>ユーザー アカウントの削除

アカウントを削除する方法は、ディレクトリ同期を使用しているかどうかによって異なります。 
  
- ディレクトリ同期を使用していない場合は、管理ページを使用するか、管理者ページを使用してアカウントを削除Windows PowerShell。
    
- ディレクトリ同期を使用している場合は、Office 365 ではなく、ローカルの Active Directory からユーザーを削除する必要があります。
    
アカウントは、削除されると非アクティブになります。 削除後約 30 日間は、アカウントを復元することができます。 アカウントの削除と復元の詳細については、「ユーザーの削除[](/office365/admin/add-users/delete-a-user)とユーザーの[](/office365/admin/add-users/restore-user)復元」、または中国の 21Vianet が運営する Office 365 を使用している場合は[、「21Vianet](/office365/admin/add-users/add-users)が運営する Office 365 でユーザー アカウントを作成または編集する - 管理者ヘルプ」を参照してください。
  
## <a name="password-management"></a>パスワードの管理

パスワード管理のポリシーと手順は、ID システムによって異なります。
  
### <a name="cloud-identity-password-management"></a>クラウド ID パスワード管理
  
クラウド ID を使用する場合、パスワードは、アカウントが作成されたときに自動的に生成されます。
  
- クラウド ID パスワードの強度要件の詳細については、「[パスワード ポリシー](/previous-versions/azure/jj943764(v=azure.100))」を参照してください。
    
- セキュリティを強化するには、ユーザーが Microsoft サービスに初めてアクセスするときにパスワードを変更する必要があります。 その結果、ユーザーが Microsoft サービスにアクセスする前に、Microsoft 365 管理センターにサインインする必要があります。そこで、パスワードの変更を求めるメッセージが表示されます。
    
- 管理者は、パスワード有効期限ポリシーを設定できます。詳しくは、「[組織のパスワード有効期限ポリシーを設定します。](/office365/admin/manage/set-password-expiration-policy)」を参照してください。
    
クラウド ID を持つユーザーのパスワードを再設定するには、いくつか方法があります。
  
- **管理者がパスワードをリセット** する - ユーザーがパスワードを紛失または忘れた場合、管理者は管理センターまたは管理者のパスワードを使用して、ユーザーのパスワードをWindows PowerShell。 ユーザーは、自分の現在のパスワードを知っている場合に、自分のパスワードだけを変更できます。 
    
    エンタープライズ プランの場合、管理者がパスワードを紛失または忘れた場合、グローバル管理者の役割を持つ別の管理者は、Microsoft 365 管理センターまたは Windows PowerShell を使用して管理者のパスワードをリセットできます。 詳細については、「[Office 365 の管理者パスワードを再設定する](/office365/admin/add-users/reset-passwords)」を参照してください。 中国で 21Vianet が運用している Office 365 で作業している場合は、「[21Vianet が運用している Office 365 でパスワードを変更または再設定する](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b)」を参照してください。
    
- **ユーザーが Outlook on the web** でパスワードを変更する - [Web オプション] ページの Outlook には[パスワードの変更] ハイパーリンクが含まれています。このハイパーリンクは、ユーザーを [パスワードの変更] ページ **にリダイレクト** します。 ユーザーは、以前のパスワードを知っている必要があります。 詳細については、「 [Outlook Web アプリでパスワードを変更する](https://support.office.com/article/change-password-in-outlook-web-app-50bb1309-6f53-4c24-8bfd-ed24ca9e872c)」を参照してください。 中国で 21Vianet が運用している Office 365 を使用している場合は、「[21Vianet が運用している Office 365 でパスワードを変更または再設定する](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b)」を参照してください。
    
- **役割** ベースのパスワードのリセット権限 - エンタープライズ プランの場合、ヘルプデスク スタッフなどの承認されたユーザーには、完全なサービス管理者になることなく、定義済みまたはカスタムの役割を使用してパスワードを変更する権限とパスワードを変更する権限を割り当てることができます。 既定では、エンタープライズ プランでは、グローバル管理者、パスワード管理者、またはユーザー管理管理者の役割を持つ管理者はパスワードを変更できます。 詳細については、「[管理者ロールを割り当てる](/office365/admin/add-users/assign-admin-roles)」を参照してください。
    
- **[パスワードを使用してパスワードWindows PowerShell** をリセットする - サービス管理者は、パスワードWindows PowerShellをリセットするために使用できます。 
    
### <a name="federated-identity-password-management"></a>フェデレーション ID パスワード管理
  
フェデレーション ID を使用する場合、パスワードは Active Directory で管理されます。 オンプレミスのセキュリティ トークン サービスは、インターネット上でユーザーのローカル Active Directory パスワードを 365 に渡さずにフェデレーション ゲートウェイOfficeします。 ローカル パスワード ポリシーを使用するか、Web クライアントの場合には 2 要素認証を使用します。 Outlook on the web には、パスワードの変更ハイパーリンクは含めされません。 ユーザーは、標準の社内ツールを使用して、またはデスクトップ PC のログオン オプションでパスワードを変更します。
  
組織環境でシングル サインオン [(SSO)](/previous-versions/azure/azure-services/dn441213(v=azure.100)) を有効にしたディレクトリ同期が有効で、フェデレーション ID プロバイダーに影響する停止がある場合は、フェデレーション サインイン用のパスワード同期バックアップによって、ドメインを手動でパスワード同期に切り替えるオプションが提供されます。パスワード同期を使用すると、停止が修正されている間にユーザーがアクセスできます。 パスワード同期を使用すると、ユーザーは停止の修復作業中でも Office 365 にアクセスできます。[シングル サインオンからパスワード同期に切り替える方法](https://go.microsoft.com/fwlink/p/?LinkId=509832)をご確認ください。
  
## <a name="license-management"></a>ライセンス管理

ライセンスを使用すると、ユーザーは一連の Microsoft サービスにアクセスできます。 管理者は、必要なサービスにアクセスするためのライセンスを各ユーザーに割り当てます。 たとえば、Skype for Business Online へのアクセス権は割り当て、SharePoint Online へのアクセス権は割り当てないということができます。
  
Microsoft 請求管理者は、ユーザー ライセンスの数や会社が使用する追加サービスの数など、サブスクリプションの詳細を変更できます。 「ライセンスの [割り当てまたは削除」を参照してください](/office365/admin/subscriptions-and-billing/assign-licenses-to-users)。 中国で 21Vianet が運用している Office 365 を使用している場合は、「[21Vianet が運用している Office 365 でライセンスの割り当てまたは削除を行う](/office365/admin/subscriptions-and-billing/assign-licenses-to-users)」を参照してください。
  
## <a name="group-management"></a>グループの管理

SharePoint Online では、セキュリティ グループを使用してサイトへのアクセスを制御します。 セキュリティ グループは、Microsoft 365 管理センターで作成できます。 セキュリティ グループの詳細については、「[セキュリティ グループを作成、編集、削除する](/office365/admin/email/create-edit-or-delete-a-security-group)」を参照してください。
  
## <a name="administrator-roles"></a>管理者の役割

Office 365 for enterprise は、役割ベースのアクセス制御 (RBAC) モデルに従います。権限と機能は管理役割によって定義されます。 組織で 365 にOfficeするユーザーは、自動的にグローバル管理者またはトップ レベルの管理者になります。 管理者の役割は、グローバル管理者、課金管理者、パスワード管理者、サービス管理者、ユーザー管理管理者の 5 つの役割です。 エンタープライズ向け Office 365 での管理者ロールの詳細 (Exchange Online、SharePoint Online、Skype for Business Online 管理への適用方法など)については、「管理者の役割の割り当て」を [参照](/previous-versions/windows/it-pro/windows-server-2012-R2-and-2012/jj878348(v=ws.11))してください。 中国の 21Vianet Office 365 を使用している場合は、「ビジネス向け Office [365](/office365/admin/add-users/assign-admin-roles)で管理者の役割を割り当てる」を参照してください。
  
## <a name="delegated-administration-and-support-for-partners"></a>代理管理とパートナーのサポート

顧客に代わってアカウントを管理する権限をパートナーに付与することができます。 お客様は、パートナーが使用するユーザー アカウントを必要としないし、委任された管理権限を付与するときにライセンスを使用しない。 パートナーは、無制限のアクセスまたは制限付きのアクセスを組織内のユーザーに割り当てることができます。 制限付きのアクセスには、パスワードの再設定、サービス リクエストの管理、およびサービス正常性の監視などの権限が含まれます。 
  
> [!NOTE]
> 代理管理者としてパートナーを使用および指定できるかどうかは、地域によって異なります。 
  
## <a name="azure-active-directory-services"></a>Azure Active Directory サービス

Azure Active Directory (AD) は、Office 365 に対して包括的な ID およびアクセス管理の機能を提供します。 開発者のために、ディレクトリ サービス、高度な ID ガバナンス、アプリケーション アクセス管理、機能豊富な標準ベースのプラットフォームを組み合わせています。 AD 365 Officeの機能の詳細については、「サインイン ページのブランド化とクラウド ユーザーのセルフサービス パスワードのリセット」を[参照してください]() https://go.microsoft.com/fwlink/?linkid=2144147 。 Azure Active [Directory の無料エディション、基本エディション、プレミアム エディションの詳細については、以下を参照してください](/previous-versions/azure/dn532272(v=azure.100))。 
  
## <a name="feature-availability"></a>機能の可用性

プラン、スタンドアロン オプション、オンプレミス ソリューションの機能の可用性を表示するには [、「Microsoft 365 および Office 365](office-365-platform-service-description.md)プラットフォーム サービスの説明」を参照してください。
