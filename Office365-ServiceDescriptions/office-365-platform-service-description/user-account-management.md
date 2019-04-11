---
title: ユーザー アカウント管理
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-user-account-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: e7616079-5b13-4f1c-99ed-b20174e0808d
description: Microsoft Office 365 は、ユーザーを作成、管理、および認証するための以下の方法をサポートしています。
ms.openlocfilehash: 76a47ba99c9b163c98b7370407d3390c20235ed5
ms.sourcegitcommit: a6d9057a955ca220db9e4dbc29cd9ea0053616fc
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2019
ms.locfileid: "31764855"
---
# <a name="user-account-management"></a>ユーザー アカウント管理

Microsoft Office 365 は、ユーザーを作成、管理、および認証するための以下の方法をサポートしています。 
  
> [!NOTE]
> このトピックには、Office 365 の個別のリソース (たとえば、Microsoft Exchange Online における役割ベースのアクセス制御や、Microsoft SharePoint Online でのセキュリティ構成など) へのアクセスを許可または禁止するセキュリティ機能に関する情報は含まれていません。これらの機能の詳細については、「[Exchange Online サービスの説明](../exchange-online-service-description/exchange-online-service-description.md)」および「[SharePoint Online サービスの説明](../sharepoint-online-service-description/sharepoint-online-service-description.md)」を参照してください。 
  
管理タスクの実行に役立つツールの情報については、「[Office 365 アカウントを管理するためのツール](https://go.microsoft.com/fwlink/?linkid=847777)」を参照してください。日常的な管理タスクを実行する方法については、「[Office 365 の一般的な管理タスク](https://go.microsoft.com/fwlink/?linkid=847778)」を参照してください。
  
## <a name="need-help-signing-in-installing-or-uninstalling-or-canceling-your-subscription"></a>サインイン、インストール、アンインストール、またはサブスクリプションのキャンセルについてヘルプが必要ですか?

次のページを参照してください: [Office 365 にサインインする場所](http://go.microsoft.com/fwlink/?LinkID=529144&amp;clcid=0x409) | [Office 365 Solo を PC または Mac にダウンロードしてインストールする](http://go.microsoft.com/fwlink/?LinkID=827202&amp;clcid=0x409) | [一般法人向け Office 365 サブスクリプションをキャンセルする](https://support.office.com/en-us/article/Cancel-Office-365-for-business-b1bc0bef-4608-4601-813a-cdd9f746709a)
  
Office 365 の他の問題については、[Microsoft サポート センター](https://go.microsoft.com/fwlink/?LinkID=808783)にアクセスしてください。中国の 21Vianet が運用している Office 365 に対するサポートを受けるには、[21Vianet サポート チーム](https://support.office.com/en-US/article/Get-technical-billing-and-subscription-support-for-Office-365-operated-by-21Vianet-671FB12E-F5D8-4CDF-B3E9-E8068A9AA496)にお問い合わせください。Office 365 Germany の場合、[Office 365 Germany サポート チーム](https://support.office.com/en-us/article/Get-technical-and-billing-support-for-Office-365-Germany-83ef2266-2543-48d7-a41a-1b56b403a8e9?ui=en-US&amp;rs=en-US&amp;ad=US&amp;fromAR=1)にお問い合わせください。 
  
## <a name="sign-in-options"></a>サインイン オプション

Office 365 は、ユーザー ID のために使用できる 2 つのシステムを備えています。
  
- **職場または学校のアカウント (クラウド ID)** ユーザーは、Office 365 や他の Microsoft のクラウド サービス にサインインするために、他のデスクトップや会社の資格情報とは別に、Azure Active Directory クラウド資格情報を受け取ります。これは既定の ID で、展開の複雑さを最小にするためにこの ID を使用することをお勧めします。職場または学校のアカウント用のパスワードは、Azure Active Directory [ パスワード ポリシー ](http://go.microsoft.com/fwlink/?LinkID=730689&amp;clcid=0x409) を使用します。
    
- **フェデレーション アカウント (フェデレーション ID)** シングル サインオン (SSO) を使う社内 Active Directory を利用する組織のすべてのサブスクリプションで、ユーザーは自分の Active Directory 資格情報を使用して Office 365 サービスにサインインできます。会社の Active Directory は、パスワード ポリシーを格納し制御します。SSO の詳細については、「 [シングル サインオンのロードマップ](https://go.microsoft.com/fwlink/p/?LinkID=270015)」を参照してください。
    
ID の種類は、ユーザー エクスペリエンスおよびユーザー アカウントの管理オプションに加えて、ハードウェアとソフトウェアの要件や、展開に関する他の検討事項にも影響します。
  
### <a name="custom-domains-and-identity-options"></a>カスタム ドメインと ID オプション

新しいユーザーを作成すると、ユーザーのサインイン名と電子メールアドレスが、Microsoft 365 管理センターで設定されている既定のドメインに割り当てられます。 詳細については、「[Office 365 でドメインの所有者の確認方法](https://support.office.com/en-us/article/Add-your-users-and-domain-to-Office-365-6383f56d-3d09-4dcb-9b41-b5f5a5efd611)」を参照してください。 
  
By default, the Office 365 subscription uses the \< _company name_\> **.onmicrosoft.com** domain that was created with the account.\* You can add one or more custom domains to Office 365 rather than retaining the onmicrosoft.com domain, and can assign users to sign in with any of the validated domains. Each user's assigned domain is the email address that will appear on sent and received email messages. 
  
Office 365 では、それぞれが別々の名前空間で表現される最大 900 の登録済みインターネット ドメインをホストできます。 
  
シングルサインオンを使用する組織では、ドメイン上のすべてのユーザーが同じ id システムを使用する必要があります。これは、クラウド id とフェデレーション id のどちらかです。 たとえば、クラウド id のみを必要とするユーザーグループを1つ持つことができます。これは、オンプレミスのシステムにアクセスせず、Office 365 とオンプレミスのシステムを使用しているユーザーの別のグループであるためです。 contractors.contoso.com や staff.contoso.com などの2つのドメインを Office 365 に追加し、そのうち1つの SSO のみを設定します。 ドメイン全体を、クラウド id からフェデレーション id に変換するか、フェデレーション id からクラウド id に変換することができます。
  
Office 365 におけるドメインの詳細については、「[ドメイン](domains.md)」のサービスの説明を参照してください。 
  
\* 中国で 21Vianet が運用している Office 365 を使用している場合、既定のドメインは、\<companyname\> **.onmsChina.cn** です。Office 365 Germany を使用している場合の既定ドメインは、\<companyname\> **.onmicrosoft.de** です。
  
## <a name="authentication"></a>認証

SharePoint Online で作成される匿名アクセス用のインターネット サイトの例外として、Office 365 サービスにアクセスする場合、ユーザーは認証を受ける必要があります。 
  
- **先進認証**: 先進認証によって、各種プラットフォームにおける Office クライアント アプリへの Active Directory 認証ライブラリ (ADAL) ベースのサインインを行えます。これにより、多要素認証 (MFA) によるサインイン、SAML ベースのサードパーティ製 ID プロバイダーから Office クライアント アプリケーションへのサインイン、スマート カードや証明書をベースとする認証機能を使用したサインインなどが可能になります。また、Microsoft Outlook を使用していなくても基本認証プロトコルを使用できるようになります。Office アプリケーション間における先進認証の可用性を含む詳細については、「[Office 2013 および Office 2016 クライアント アプリにおける先進認証のしくみ](http://go.microsoft.com/fwlink/?LinkID=717892&amp;clcid=0x409)」および「[Office クライアントで Office 365 先進認証を使用する](http://go.microsoft.com/fwlink/?LinkID=717893&amp;clcid=0x409)」をご覧ください。
    
    Exchange Online に対しては、先進認証は既定で無効です。有効にする方法については、「[Exchange Online で先進認証を有効にする](http://go.microsoft.com/fwlink/?LinkID=717894&amp;clcid=0x409)」をご覧ください。
    
- **クラウド ID の認証** クラウド ID を持つユーザーは、従来のチャレンジ / レスポンスを使用して認証されます。Web ブラウザーは Office 365 サインイン サービスにリダイレクトされるため、職場または学生アカウント用のユーザー名とパワードを入力します。サインイン サービスは、ユーザーの資格情報を認証し、サービス トークンを生成します。Web ブラウザーは、このサービス トークンを要求されたサービスに表示して、ユーザーを登録します。 
    
- **フェデレーション id 認証**フェデレーション id を持つユーザーは、Active Directory フェデレーションサービス (AD FS) 2.0 またはその他のセキュリティトークンサービスを使用して認証されます。 web ブラウザーは Office 365 サインインサービスにリダイレクトされ、ユーザープリンシパル名 (UPN isabel@contoso.com) の形式で会社 ID を入力します (例:)。 サインインサービスは、フェデレーションドメインの一部であることを確認し、認証のためにオンプレミスのフェデレーションサーバーにリダイレクトすることを提供します。 デスクトップ (ドメインに参加) にログオンしている場合は、(Kerberos または NTLMv2 を使用して) 認証され、オンプレミスのセキュリティトークンサービスが、web ブラウザーが Office 365 サインインサービスにポストするログオントークンを生成します。 サインインサービスは、ログオントークンを使用して、web ブラウザーが要求されたサービスにポストしてログインするサービストークンを生成します。 利用可能なセキュリティトークンサービスの一覧については、「[シングルサインオンのロードマップ](https://go.microsoft.com/fwlink/p/?LinkID=270015)」を参照してください。
    
Office 365 は形式ベースの認証を使用しており、ネットワークを網羅する認証トラフィックは、ポート 443 を使用して常に TLS/SSL で暗号化されます。認証トラフィックが Office 365 サービスに使用する帯域幅はごくわずかです。 
  
### <a name="multi-factor-authentication-for-office-365"></a>Office 365 で Multi-Factor Authentication

Office 365 で多要素認証を使用する場合、ユーザーは、パスワードを正確に入力した後に、スマートフォンで電話、テキストメッセージ、またはアプリの通知に同意する必要があります。 Only after this second authentication can the user sign in. Office 365 管理者は、Microsoft 365 管理センターで多要素認証のためにユーザーを登録することができます。 Learn more about [Multi-Factor Authentication for Office 365](https://go.microsoft.com/fwlink/p/?LinkId=392429).
  
### <a name="rich-client-authentication"></a>リッチ クライアント認証

Microsoft Office デスクトップ アプリケーションなどのリッチ クライアントの場合、2 つの方法で認証を実行できます。
  
- **Microsoft Online Services サインイン アシスタント** Office 365 デスクトップ セットアップ にインストールされる サインイン アシスタント には、Office 365 サインイン サービスからサービス トークンを取得し、リッチ クライアントに返すクライアント サービスが含まれています。 
    
  - クラウド ID を持っている場合、ユーザーは資格情報のプロンプトを受け取ります。クライアント サービスは、認証のために、このプロンプトを Office 365 サインイン サービスに送信します (WS-Trust を使用)。
    
  - ユーザーがフェデレーション ID を所有している場合、クライアント サービスは、まず AD FS 2.0 サーバーに接続し、資格情報を認証して (Kerberos または NTLMv2 を使用) ログオン トークンを取得します。このログオン トークンは Office 365 サインイン サービスに送信されます (WS-Federation および WS-Trust を使用)。
    
- **SSL による基本/プロキシ認証** Outlook クライアントは、基本認証の資格情報を SSL で Exchange Online に送ります。Exchange Online は、Office 365 ID プラットフォームに認証要求をプロキシし、次に社内 Active Directory フェデレーション サーバー (SSO 用) にプロキシします。 
    
Office 365 サービスの適切な検出と認証を確認するため、管理者は、一連のコンポーネントおよび更新プログラムをリッチ クライアント (Microsoft Office 2010 など) を使用する各ワークステーションに適用してから、Office 365 に接続します。Office 365 デスクトップ セットアップは、必要な更新でワークステーションを構成する自動ツールです。詳細については、「[Office 2010 デスクトップ プログラムをセットアップして一般法人向けの Office 365 と連係させる](https://go.microsoft.com/fwlink/p/?LinkID=270049)」を参照してください。
  
### <a name="sign-in-experience"></a>サインイン方法

サインイン方法は、使用中の Office 365 ID の種類に応じて異なります。
  
||**クラウド ID**|**フェデレーション ID**|
|:-----|:-----|:-----|
|Outlook 2016  <br/> |セッションごとにサインイン <sup>1</sup> <br/> |セッションごとにサインイン <sup>2</sup> <br/> |
|Outlook 2013  <br/> |セッションごとにサインイン <sup>1</sup> <br/> |セッションごとにサインイン <sup>2</sup> <br/> |
|Windows 7 で Outlook 2010 または Office 2007 を使用  <br/> |セッションごとにサインイン <sup>1</sup> <br/> |セッションごとにサインイン <sup>2</sup> <br/> |
|Windows Vista で Outlook 2010 または Office Outlook 2007 を使用  <br/> |セッションごとにサインイン <sup>1</sup> <br/> |セッションごとにサインイン <sup>2</sup> <br/> |
|Microsoft Exchange ActiveSync  <br/> |セッションごとにサインイン <sup>1</sup> <br/> |セッションごとにサインイン <sup>2</sup> <br/> |
|POP、IMAP、Outlook for Mac  <br/> |セッションごとにサインイン <sup>1</sup> <br/> |セッションごとにサインイン <sup>2</sup> <br/> |
|Web エクスペリエンス:Office 365 ポータル / Outlook Web App/ SharePoint Online / Office Online  <br/> |ブラウザー セッションごとにサインイン <sup>4</sup> <br/> |セッションごとにサインイン <sup>3</sup> <br/> |
|SharePoint Online で Office 2010 または Office 2007 を使用  <br/> |SharePoint Online セッションごとにサインイン <sup>4</sup> <br/> |SharePoint Online セッションごとにサインイン <sup>3</sup> <br/> |
|Skype for Business Online  <br/> |セッションごとにサインイン <sup>1</sup> <br/> |プロンプトなし  <br/> |
|Outlook for Mac  <br/> |セッションごとにサインイン <sup>1</sup> <br/> |セッションごとにサインイン <sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> 最初に要求された時点で、今後の使用を目的にパスワードを保存することができます。パスワードを変更するまで、別のプロンプトを受け取ることはありません。 > <sup>2</sup> 会社の資格情報を入力します。パスワードを保存することができます。保存すると、パスワードを変更するまで、再度要求されることはありません。 > <sup>3</sup> すべてのアプリは、サインするためにユーザー名の入力かクリックが必要です。コンピューターがドメインに参加している場合は、パスワードの入力は要求されません。 **[サインアウトしない]** をクリックすると、サインアウトするまで要求されることはありません。 > <sup>4</sup> **[サインアウトしない]** をクリックすると、サインアウトするまで要求されることはありません。 
  
## <a name="creating-user-accounts"></a>ユーザー アカウントの作成

Office 365 にユーザーを追加する方法は複数あります。 詳細については、「[ユーザーを個別にまたは一括で Office 365 に追加する-管理者向けヘルプ](https://go.microsoft.com/fwlink/p/?linkid=860006)」および「 [Microsoft 365 管理センタープレビューでユーザーを追加、削除、および管理](http://go.microsoft.com/fwlink/?LinkID=624101&amp;clcid=0x409)する」を参照してください。 中国で運用している Office 365 を使用している場合は、「[21Vianet が運用している Office 365 でユーザー アカウントを作成または編集する - 管理者向けヘルプ](http://go.microsoft.com/fwlink/?LinkID=730724&amp;clcid=0x409)」を参照してください。
  
## <a name="deleting-accounts"></a>アカウントの削除

アカウントを削除する方法は、ディレクトリ同期を使用しているかどうかによって異なります。 
  
- ディレクトリ同期を使用していない場合、Office 365 の管理者ページを使用するか、Windows PowerShell を使用して削除することができます。
    
- ディレクトリ同期を使用している場合は、Office 365 ではなく、ローカルの Active Directory からユーザーを削除する必要があります。
    
アカウントは、削除されると非アクティブになります。削除後約 30 日間は、アカウントを復元することができます。アカウントの削除および復元については、「[Office 365 でユーザーを削除する](https://go.microsoft.com/fwlink/p/?LinkID=270053)」、または中国で 21Vianet が運用している Office 365 を使用している場合は、「[21Vianet が運用している Office 365 でユーザー アカウントを作成または編集する - 管理者向けヘルプ](http://go.microsoft.com/fwlink/?LinkID=730724&amp;clcid=0x409)」を参照してください。
  
## <a name="password-management"></a>パスワードの管理

パスワード管理のポリシーと手順は、ID システムによって異なります。
  
 **クラウド ID パスワードの管理:**
  
クラウド ID を使用する場合、パスワードは、アカウントが作成されたときに自動的に生成されます。
  
- クラウド ID パスワードの強度要件の詳細については、「[パスワード ポリシー](http://go.microsoft.com/fwlink/?LinkID=730689&amp;clcid=0x409)」を参照してください。
    
- セキュリティを強化するため、最初に Office 365 サービスにアクセスする時点で、ユーザーはパスワードを変更する必要があります。そのため、ユーザーが Office 365 サービスにアクセスできるようにするには、Office 365 ポータルにサインインし、プロンプトに従ってパスワードを変更する必要があります。
    
- 管理者は、パスワード有効期限ポリシーを設定できます。詳しくは、「[組織のパスワード有効期限ポリシーを設定します。](https://go.microsoft.com/fwlink/p/?LinkID=285381)」を参照してください。
    
クラウド ID を持つユーザーのパスワードを再設定するには、いくつか方法があります。
  
- **管理者によるパスワードの再設定** ユーザーが自分のパスワードをなくすか忘れた場合、管理者が Office 365 ポータルで、または Windows PowerShell を使用してユーザーのパスワードを再設定できます。ユーザーは、自分の現在のパスワードを知っている場合に、自分のパスワードだけを変更できます。 
    
    エンタープライズプランでは、管理者がパスワードを紛失または忘れた場合、グローバル管理者の役割を持つ別の管理者が、Microsoft 365 管理センターまたは Windows PowerShell を使用して、管理者のパスワードを再設定することができます。 詳細については、「[Office 365 の管理者パスワードを再設定する](https://go.microsoft.com/fwlink/p/?LinkID=270062)」を参照してください。 中国で 21Vianet が運用している Office 365 で作業している場合は、「[21Vianet が運用している Office 365 でパスワードを変更または再設定する](http://go.microsoft.com/fwlink/?LinkID=730731&amp;clcid=0x409)」を参照してください。
    
- **Outlook Web App を使用したユーザーによるパスワード変更** Outlook Web App オプション ページには、ユーザーを **[パスワードの変更]** ページにリダイレクトする、パスワード変更のハイパーリンクが含まれています。ユーザーは、以前のパスワードを知っている必要があります。詳細については、「 [Outlook Web アプリでパスワードを変更する](https://go.microsoft.com/fwlink/p/?LinkID=270063)」を参照してください。中国で 21Vianet が運用している Office 365 を使用している場合は、「[21Vianet が運用している Office 365 でパスワードを変更または再設定する](http://go.microsoft.com/fwlink/?LinkID=730731&amp;clcid=0x409)」を参照してください。
    
- **パスワードを再設定する役割ベースの権限** Enterprise プランでは、ヘルプデスクのスタッフなどの承認されたユーザーには、 **[パスワードの再設定]** を実行するユーザー権限や、Office 365 の定義済みの役割やカスタムの役割を使用して、全サービスの管理者にすることなく、パスワードを変更する権限を割り当てることができます。既定では、Enterprise プランの場合、全体管理者、パスワード管理者、またはユーザー管理の管理者の役割が割り当てられた管理者がパスワードを変更できます。詳細については、「 [一般法人向け Office 365 で管理者ロールを割り当てる](https://go.microsoft.com/fwlink/p/?LinkID=270061)」を参照してください。
    
- **Windows PowerShell を使用してパスワードを再設定する** サービス管理者は、Windows PowerShell を使用してパスワードを再設定することができます。 
    
 **フェデレーション ID パスワードの管理:**
  
フェデレーション ID を使用する場合、パスワードは Active Directory で管理されます。社内のセキュリティ トークン サービスは、ユーザーのローカル Active Directory のパスワードをインターネット経由で Office 365 に渡すことなく、Office 365 Federation Gateway による認証をネゴシエートします。ローカル パスワード ポリシーを使用するか、Web クライアントの場合には 2 要素認証を使用します。Outlook Web App には、パスワード変更のハイパーリンクは含まれていません。ユーザーは、標準の社内ツールを使用して、またはデスクトップ PC のログオン オプションでパスワードを変更します。
  
[ディレクトリ同期とシングル サインオン](https://go.microsoft.com/fwlink/p/?LinkId=509831)が Office 365 環境で有効で、フェデレーション ID プロバイダーに影響する停止が生じた場合、フェデレーション サインインのパスワード同期バックアップにより、ドメインを手動でパスワード同期に切り替えることができます。パスワード同期を使用すると、ユーザーは停止の修復作業中でも Office 365 にアクセスできます。[シングル サインオンからパスワード同期に切り替える方法](https://go.microsoft.com/fwlink/p/?LinkId=509832)をご確認ください。
  
## <a name="license-management"></a>ライセンスの管理

Office 365 ライセンスは、Office 365 サービスのセットへのアクセスをユーザーに提供します。管理者は、必要なサービスにアクセスするためのライセンスを各ユーザーに割り当てます。たとえば、Skype for Business Online へのアクセス権は割り当て、SharePoint Online へのアクセス権は割り当てないということができます。
  
Office 365 の課金管理者は、会社で使用するユーザー ライセンス数や追加するサービスの数など、サブスクリプションの詳細を変更できます。詳しくは、「[一般法人向け Office 365 ライセンスの割り当てまたは解除方法](https://go.microsoft.com/fwlink/p/?LinkID=270069)」を参照してください。中国で 21Vianet が運用している Office 365 を使用している場合は、「[21Vianet が運用している Office 365 でライセンスの割り当てまたは削除を行う](http://go.microsoft.com/fwlink/?LinkID=730747&amp;clcid=0x409)」を参照してください。
  
## <a name="group-management"></a>グループの管理

SharePoint Online では、セキュリティ グループを使用してサイトへのアクセスを制御します。 セキュリティグループは、Microsoft 365 管理センターで作成できます。 セキュリティ グループの詳細については、「[セキュリティ グループを作成、編集、削除する](http://go.microsoft.com/fwlink/?LinkID=733611&amp;clcid=0x409)」を参照してください。
  
## <a name="administrator-roles"></a>管理者の役割

Office 365 Enterprise は、ロールベースのアクセス制御 (RBAC) モデルを採用しています。そのため、アクセス許可や機能は、管理の役割によって定義されます。自分の組織の Office 365 にサインアップしたユーザーが、自動的に全体管理者または最上位管理者になります。管理者の役割には、全体管理者、課金管理者、パスワード管理者、サービス管理者、およびユーザー管理の管理者の 5 つがあります。管理者の役割を Exchange Online、SharePoint Online、および Skype for Business Online の管理に適用する方法など、Office 365 Enterprise の管理者役割の詳細については、「[一般法人向け Office 365 で管理者ロールを割り当てる](https://go.microsoft.com/fwlink/p/?LinkID=282732)」を参照してください。中国で 21Vianet が運用している Office 365 を使用している場合は、「[一般法人向け Office 365 で管理者ロールを割り当てる](https://go.microsoft.com/fwlink/p/?linkid=270061)」を参照してください。
  
## <a name="delegated-administration-and-support-for-partners"></a>代理管理とパートナーのサポート

顧客に代わってアカウントを管理する権限をパートナーに付与することができます。 顧客は、パートナーのユーザー アカウントを必要とせず、代理管理権限を付与するときに Office 365 のライセンスを使用することもありません。 パートナーは、無制限のアクセスまたは制限付きのアクセスを組織内のユーザーに割り当てることができます。 制限付きのアクセスには、パスワードの再設定、サービス リクエストの管理、およびサービス正常性の監視などの権限が含まれます。 
  
> [!NOTE]
> 代理管理者としてパートナーを使用および指定できるかどうかは、地域によって異なります。 
  
## <a name="azure-active-directory-services"></a>Azure Active Directory サービス

Azure Active Directory (AD) は、Office 365 に対して包括的な ID およびアクセス管理の機能を提供します。開発者のために、ディレクトリ サービス、高度な ID ガバナンス、アプリケーション アクセス管理、機能豊富な標準ベースのプラットフォームを組み合わせています。Office 365 における AD 機能について詳しくは、「[サインイン ページのブランド化とクラウド ユーザーのセルフサービスによるパスワードのリセット](https://blogs.office.com/2015/02/17/sign-page-branding-cloud-user-self-service-password-reset-office-365/)」をご覧ください。[Azure Active Directory のエディション](https://msdn.microsoft.com/en-us/library/azure/dn532272.aspx)の詳細をご確認ください。 
  
## <a name="feature-availability"></a>機能の可用性

Office 365 のプラン、スタンドアロンのオプションとオンプレミスのソリューションで利用できる機能を確認するには、「[Office 365 プラットフォーム サービスの説明](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx)」を参照してください。
  
