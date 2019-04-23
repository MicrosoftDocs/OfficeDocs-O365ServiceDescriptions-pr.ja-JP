---
title: クライアントとモバイル デバイス
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 04/10/2019
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-clients-and-mobile-devices
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: fce4ac03-f30a-4152-9145-4a9ce564c966
ms.openlocfilehash: 380f542c6db323d5dac647dc694c0b320bf13be6
ms.sourcegitcommit: a2746a765ff23624c62e617bcd521b5276bec57b
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/22/2019
ms.locfileid: "31981641"
---
# <a name="clients-and-mobile-devices"></a><span data-ttu-id="1cff8-102">クライアントとモバイル デバイス</span><span class="sxs-lookup"><span data-stu-id="1cff8-102">Clients and Mobile Devices</span></span>

## <a name="microsoft-outlook"></a><span data-ttu-id="1cff8-103">Microsoft Outlook</span><span class="sxs-lookup"><span data-stu-id="1cff8-103">Microsoft Outlook</span></span>

<span data-ttu-id="1cff8-104">Microsoft Outlook は、予定表、連絡先、タスク、および以下の主な機能をサポートする電子メール プログラムです。</span><span class="sxs-lookup"><span data-stu-id="1cff8-104">Microsoft Outlook is an email program that includes support for calendar, contacts, tasks, and the following key features:</span></span>
  
- <span data-ttu-id="1cff8-p101">**MAPI over HTTP** Messaging Application Program Interface (MAPI) over HTTP を使用すると、組織のファイアウォールの外からインターネット経由で Exchange Online のメールボックスに接続できます。MAPI over HTTP は、Outlook Anywhere の長期的な置き換えとしてサポートされています。この接続方法は、接続回復力の向上、より安全なサインイン、拡張性、および IT とサポートの拡張機能を提供します。詳細については、「 [Office 365 における RPC over HTTP のサポート終了 (2017 年 10 月 31 日) に関する情報](https://go.microsoft.com/fwlink/?linkid=863890)」および「[MAPI over HTTP](https://go.microsoft.com/fwlink/?linkid=393041)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="1cff8-p101">**MAPI over HTTP** Messaging Application Program Interface (MAPI) over HTTP allows Outlook users to connect to Exchange Online mailboxes over the Internet from outside their organization's firewall. MAPI over HTTP, the long term replacement for Outlook Anywhere. This connectivity method offers improved connection resiliency, more secure sign-in, extensibility, as well as enhancements for IT and support. To learn more, see [RPC over HTTP reaches end of support in Office 365](https://go.microsoft.com/fwlink/?linkid=863890) and [MAPI over HTTP](https://go.microsoft.com/fwlink/?linkid=393041).</span></span>
    
- <span data-ttu-id="1cff8-p102">**自動検出** 自動検出サービスは、Exchange Online と連携するように Outlook を自動的に構成します。Outlook ユーザーは、電子メール アドレスとパスワードを使って初めて Exchange Online にサインインしたときに、必要なプロファイル設定を受信します。これらの設定は、ユーザーのプロファイルの作成と管理に必要な情報で Outlook クライアントを自動的に更新します。自動検出サービスを使用するには SSL 証明書が必要です。この SSL 証明書は、単一のプライマリ SSL ドメインに限定されます。</span><span class="sxs-lookup"><span data-stu-id="1cff8-p102">**Autodiscover** The Autodiscover service feature automatically configures Outlook to work with Exchange Online. Outlook users can receive their required profile settings directly from Exchange Online the first time they sign in with their email address and password. These settings automatically update the Outlook client with the information necessary to create and maintain the user's profile. An SSL certificate is required to use the Autodiscover service. This SSL certificate is limited to a single primary SSL domain.</span></span> 
    
- <span data-ttu-id="1cff8-p103">**Exchange キャッシュ モード** Exchange キャッシュ モードを使うと、インターネットに接続していないときに、Outlook から Exchange Online メールボックスのローカル コピーにアクセスできます。Exchange キャッシュ モードは、ユーザーの Exchange メールボックスのクライアント側のコピーを Outlook 内に保持し、コピーと電子メール サーバーを自動的に同期します。Outlook は Exchange キャッシュ モードで使用してください。オフライン アクセスが可能になり、クライアントとサーバー間のネットワーク状態が理想的でない場合にもユーザーの操作に素早く反応するからです。</span><span class="sxs-lookup"><span data-stu-id="1cff8-p103">**Cached Exchange Mode** The Cached Exchange Mode feature allows Outlook users to access local copies of their Exchange Online mailboxes when they are not connected to the Internet. Cached Exchange Mode retains a client-side copy of users' Exchange mailboxes in Outlook and automatically synchronizes this copy with the email server. We recommend using Outlook in Cached Exchange Mode because it provides offline access and helps to provide a responsive user experience even when network conditions between the client and the server are not ideal.</span></span> 
    
<span data-ttu-id="1cff8-p104">既定では、すべてのユーザーが Outlook からアクセスできます。管理者は Windows PowerShell を使って特定のユーザーまたはグループのアクセスを無効にできます。Exchange Online へのアクセスには、最新の Service Pack をインストールした最新バージョンの Outlook を使用してください。</span><span class="sxs-lookup"><span data-stu-id="1cff8-p104">By default, Outlook access is enabled for all users. Administrators can disable access for specific users or groups through Windows PowerShell. We recommend using the latest version of Outlook—with the latest service pack installed—to access Exchange Online.</span></span> 
  
<span data-ttu-id="1cff8-120">Exchange 2016 と Exchange Online でサポートされている Outlook クライアントの詳細については、「[Exchange 2016 のシステム要件](https://go.microsoft.com/fwlink/?LinkID=828972)」の「サポートされるクライアント」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="1cff8-120">For information about which Outlook clients are supported by Exchange 2016 and Exchange Online, see "Supported clients" in [Exchange 2016 system requirements](https://go.microsoft.com/fwlink/?LinkID=828972).</span></span>
  
> [!IMPORTANT]
>  <span data-ttu-id="1cff8-121">Outlook は、Exchange Online サブスクリプションの価格には含まれません。</span><span class="sxs-lookup"><span data-stu-id="1cff8-121">Outlook is not provided as part of the Exchange Online subscription price.</span></span> <span data-ttu-id="1cff8-122">Microsoft Office Pro Plus (Microsoft Outlook を含みます) は、一部の Office 365 プランに含まれている他、個別のサブスクリプションとしても購入できます。</span><span class="sxs-lookup"><span data-stu-id="1cff8-122">Microsoft Office Pro Plus (which includes Microsoft Outlook) is included in some Office 365 plans and can be purchased as a separate subscription.</span></span> <span data-ttu-id="1cff8-123">pop を使用して Exchange Online の電子メールアカウントに接続する場合は、次の制限があります。 > ない予定表情報 > no free/busy 情報 > no free/busy information POP 経由で接続するときに、すべてのメッセージがダウンします。クライアントに対して実行されており、複数のコンピューターまたはデバイス (ノート pc と電話間など) 間の同期はありません。</span><span class="sxs-lookup"><span data-stu-id="1cff8-123">You will see the following limitations if you use POP to connect to an Exchange Online email account: >  No calendar information >  No free/busy information >  No Global Address List >  No push email >  When connecting through POP, all messages will be downloaded to the client and there will be no synchronization between multiple computers or devices (such as between a laptop and a phone).</span></span> 
  
## <a name="outlook-on-the-web"></a><span data-ttu-id="1cff8-124">Outlook on the web</span><span class="sxs-lookup"><span data-stu-id="1cff8-124">Outlook on the web</span></span>

<span data-ttu-id="1cff8-p106">Outlook on the web は、Exchange Online と連携する Web ベースの Outlook 電子メール プログラムです。インターネットに接続していれば、どこからでも電子メール、予定表、連絡先に Web ブラウザーでアクセスできます。サポートされているブラウザーについては、「[Office のシステム要件](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="1cff8-p106">Outlook on the web is a web-based version of the Outlook email program that is used with Exchange Online. It enables users to access their email, calendar, and contacts through a web browser from wherever they connect to the Internet. For information about supported browsers, see [Supported browsers for Outlook on the web for business](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006).</span></span>
  
<span data-ttu-id="1cff8-128">Outlook on the web のクライアントには 2 つのバージョンがあり、どちらも Exchange Online とともに利用できます。</span><span class="sxs-lookup"><span data-stu-id="1cff8-128">Outlook on the web comes in two client versions, both of which can be used with Exchange Online:</span></span>
  
- <span data-ttu-id="1cff8-p107">**Outlook on the web** Outlook on the web の標準バージョンでは、Exchange Online ユーザーに、Outlook ユーザーに一番近いメッセージング エクスペリエンスを提供します。ほとんどの新しいブラウザーをサポートしており、タブレットやスマートフォンだけでなく、デスクトップやノート PC での利用にも最適化されています。メッセージの送受信、連絡先の整理、予定と会議のスケジュールを実行できます。アクティビティ ベースのタイムアウトの既定値は 6 時間ですが、5 分から 8 時間までの範囲で [管理者が Windows PowerShell で構成できます](https://go.microsoft.com/fwlink/p/?LinkId=399155)。このタイムアウトは、ボタンのクリックやメッセージの選択など、Web アプリ内でのユーザーの操作に依存します。さらに、別個のセキュリティに基づくタイムアウトがあります。これは構成はできず、ユーザー アクティビティとは関係なく発生します。ユーザーのログインから 8 時間が経過すると、OWA が自動的にユーザーをログアウトし、再認証を要求します。</span><span class="sxs-lookup"><span data-stu-id="1cff8-p107">**Outlook on the web** The standard version of Outlook on the web provides Exchange Online users with a messaging experience most similar to that of Outlook users. It supports most newer web browsers and is optimized for use on tablets and smartphones as well as desktops and laptops. Users can read and send messages, organize contacts, and schedule appointments and meetings. The default activity-based time-out is set at six hours, but it can be [configured by an administrator in Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) from 5 minutes to 8 hours. This time-out depends on user interactions within the web app, such as clicking a button or selecting a message. There is also a separate security-driven time-out, which is not configurable and will occur regardless of user activity. If a user is logged in for 8 hours, OWA will automatically log the user out and ask for re-authentication.</span></span> 
    
- <span data-ttu-id="1cff8-p108">**Outlook on the web の Light バージョン** Outlook on the web の Light バージョンによって、Exchange Online ユーザーはほぼすべての Web ブラウザーからメールボックスにアクセスできます。メッセージの送受信、連絡先の整理、予定と会議のスケジュールを実行できます。アクティビティ ベースのタイムアウトの既定値は 6 時間ですが、5 分から 8 時間までの範囲で [管理者が Windows PowerShell で構成できます](https://go.microsoft.com/fwlink/p/?LinkId=399155)。このタイムアウトは、ボタンのクリックやメッセージの選択など、Web アプリ内でのユーザーの操作に依存します。さらに、別個のセキュリティに基づくタイムアウトがあります。これは構成はできず、ユーザー アクティビティとは関係なく発生します。ユーザーのログインから 8 時間が経過すると、OWA の Light バージョンは自動的にユーザーをログアウトし、再認証を要求します。</span><span class="sxs-lookup"><span data-stu-id="1cff8-p108">**The light version of Outlook on the web** The light version of Outlook on the web provides Exchange Online users access to the mailbox using almost any web browser. Users can read and send messages, organize contacts, and schedule appointments and meetings. The default activity-based time-out is set at six hours, but it can be [configured by an administrator in Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) from 5 minutes to 8 hours. This time-out depends on user interactions within the web app, such as clicking a button or selecting a message. There is also a separate security-driven time-out, which is not configurable and will occur regardless of user activity. If a user is logged in for 8 hours, the light version of OWA will automatically log the user out and ask for re-authentication.</span></span> 
    
<span data-ttu-id="1cff8-p109">Outlook on the web は、モバイル バージョンでも利用可能です。詳細については、「[このページ](http://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="1cff8-p109">Outlook on the web also is available in mobile versions. For more information, see [this page](http://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409).</span></span>
  
## <a name="outlook-for-mac"></a><span data-ttu-id="1cff8-144">Outlook for Mac</span><span class="sxs-lookup"><span data-stu-id="1cff8-144">Outlook for Mac</span></span>

<span data-ttu-id="1cff8-145">Exchange Online は Microsoft Outlook for Mac をサポートしています。Microsoft Outlook for Mac では電子メール、予定表、アドレス帳、タスク リスト、ノートの一覧を使用できます。</span><span class="sxs-lookup"><span data-stu-id="1cff8-145">Exchange Online supports Microsoft Outlook for Mac, which provides email, calendar, an address book, a task list, and a note list.</span></span>
  
## <a name="outlook-for-ios-android-and-windows-phone"></a><span data-ttu-id="1cff8-146">Outlook for iOS、Android、および Windows Phone</span><span class="sxs-lookup"><span data-stu-id="1cff8-146">Outlook for iOS, Android, and Windows Phone</span></span>

<span data-ttu-id="1cff8-p110">Exchange Online は、iOS、Android、および Windows Phone で使用可能な Outlook アプリで動作します。これらのデバイスのいずれかで、アプリ ストアを使用して Outlook アプリを検索します。モバイル OS での概要を次に示します。</span><span class="sxs-lookup"><span data-stu-id="1cff8-p110">Exchange Online works with Outlook apps available for iOS, Android, and Windows Phone. On any of these devices, use the app store to find the Outlook app. Here's a breakdown by mobile OS.</span></span>
  
|||||
|:-----|:-----|:-----|:-----|
|<span data-ttu-id="1cff8-150">デバイス</span><span class="sxs-lookup"><span data-stu-id="1cff8-150">Device</span></span>  <br/> |<span data-ttu-id="1cff8-151">Android</span><span class="sxs-lookup"><span data-stu-id="1cff8-151">Android</span></span>  <br/> |<span data-ttu-id="1cff8-152">iOS</span><span class="sxs-lookup"><span data-stu-id="1cff8-152">iOS</span></span>  <br/> |<span data-ttu-id="1cff8-153">Windows Phone</span><span class="sxs-lookup"><span data-stu-id="1cff8-153">Windows Phone</span></span>  <br/> |
|<span data-ttu-id="1cff8-154">Outlook モバイル アプリ利用の可否</span><span class="sxs-lookup"><span data-stu-id="1cff8-154">Outlook mobile app availability</span></span>  <br/> |<span data-ttu-id="1cff8-155">はい</span><span class="sxs-lookup"><span data-stu-id="1cff8-155">Yes</span></span>  <br/> [<span data-ttu-id="1cff8-156">Outlook for Android の入手</span><span class="sxs-lookup"><span data-stu-id="1cff8-156">Get Outlook for Android</span></span>](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |<span data-ttu-id="1cff8-157">可</span><span class="sxs-lookup"><span data-stu-id="1cff8-157">Yes</span></span>  <br/> [<span data-ttu-id="1cff8-158">Outlook for iOS の入手</span><span class="sxs-lookup"><span data-stu-id="1cff8-158">Get Outlook for iOS</span></span>](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |<span data-ttu-id="1cff8-159">組み込み</span><span class="sxs-lookup"><span data-stu-id="1cff8-159">Built-in</span></span>  <br/> |
|<span data-ttu-id="1cff8-160">Exchange Online と互換性のある組み込みの電子メール アプリ</span><span class="sxs-lookup"><span data-stu-id="1cff8-160">Built-in email apps compatible with Exchange Online</span></span>  <br/> |<span data-ttu-id="1cff8-161">Gmail アプリ/Samsung 電子メール アプリ</span><span class="sxs-lookup"><span data-stu-id="1cff8-161">Gmail app/Samsung Email app</span></span>  <br/> |<span data-ttu-id="1cff8-162">iOS メール アプリ</span><span class="sxs-lookup"><span data-stu-id="1cff8-162">iOS Mail app</span></span>  <br/> |<span data-ttu-id="1cff8-163">Outlook メール、予定表、連絡先</span><span class="sxs-lookup"><span data-stu-id="1cff8-163">Outlook Mail, calendar, contacts</span></span>  <br/> |
|<span data-ttu-id="1cff8-164">詳細情報</span><span class="sxs-lookup"><span data-stu-id="1cff8-164">More information</span></span>  <br/> |[<span data-ttu-id="1cff8-165">Android モバイルのセットアップ</span><span class="sxs-lookup"><span data-stu-id="1cff8-165">Android mobile setup</span></span>](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[<span data-ttu-id="1cff8-166">iPhone または iPad のセットアップ</span><span class="sxs-lookup"><span data-stu-id="1cff8-166">iPhone or iPad setup</span></span>](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[<span data-ttu-id="1cff8-167">Windows Phone のセットアップ</span><span class="sxs-lookup"><span data-stu-id="1cff8-167">Windows Phone setup</span></span>](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |
   
<span data-ttu-id="1cff8-168">また、Blackberry などのデバイスで Exchange Online を使用するためのオプションもあります。</span><span class="sxs-lookup"><span data-stu-id="1cff8-168">There are also options for using Exchange Online with devices, including Blackberry.</span></span>
  
### <a name="feature-availability"></a><span data-ttu-id="1cff8-169">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="1cff8-169">Feature availability</span></span>

<span data-ttu-id="1cff8-p111">Outlook は、ユーザーが最新のモバイル アプリに期待する高速で直感的な電子メールと予定表のエクスペリエンスを提供し、Office 365 の最高の機能をサポートする唯一のアプリです。これは、特に完全な Office 365 エクスペリエンスをサポートするように設計された唯一の電子メール アプリであり、ユーザーにデスクトップからモバイルまでの一貫したエクスペリエンスを提供します。Outlook は Intune、エンタープライズ モビリティとセキュリティ、および Exchange コントロールと統合され、データとユーザーの安全を確保します。</span><span class="sxs-lookup"><span data-stu-id="1cff8-p111">Outlook gives users the fast, intuitive email and calendar experience that they expect from a modern mobile app, while being the only app to provide support for the best features of Office 365. It is the only email app specifically designed to support the full Office 365 experience, giving users a coherent experience from desktop to mobile. Outlook is integrated with Intune, enterprise mobility and security, and Exchange controls to keep data and users safe.</span></span>
  
<span data-ttu-id="1cff8-173">Outlook を使用すると、次のことが可能になります。</span><span class="sxs-lookup"><span data-stu-id="1cff8-173">Outlook enables users to:</span></span>
  
- <span data-ttu-id="1cff8-174">全日をモバイル デバイスから管理できます。</span><span class="sxs-lookup"><span data-stu-id="1cff8-174">Manage their entire day from a mobile device.</span></span>
    
- <span data-ttu-id="1cff8-175">仕事と個人情報を分離して安全に保ちながら、生産性を高めるために必要なアプリやサービスに接続します。</span><span class="sxs-lookup"><span data-stu-id="1cff8-175">Connect to the apps and services they need to be productive, while keeping their work and personal information separate and secure.</span></span>
    
<span data-ttu-id="1cff8-176">Outlook for iOS、Outlook for Android、または Outlook for Windows Phone を使用すると、次のことが可能になります。</span><span class="sxs-lookup"><span data-stu-id="1cff8-176">With Outlook for iOS, Outlook for Android, or Outlook for Windows Phone, users can:</span></span> 
  
- <span data-ttu-id="1cff8-177">優先受信トレイから優先的に重要なメールを受信するメリットを得る</span><span class="sxs-lookup"><span data-stu-id="1cff8-177">Benefit from a focused inbox that priorities important email</span></span>
    
- <span data-ttu-id="1cff8-178">一意の電子メールの習慣に合わせてスワイプのジェスチャーをカスタマイズする</span><span class="sxs-lookup"><span data-stu-id="1cff8-178">Customize swipe gestures to match their unique email habits</span></span>
    
- <span data-ttu-id="1cff8-179">予定表に直接追加できる旅行日程を作成する (一目で確認できる重要な情報を付加できる)</span><span class="sxs-lookup"><span data-stu-id="1cff8-179">Create travel itineraries that can be added directly to the calendar, with key information available at a glance</span></span>
    
- <span data-ttu-id="1cff8-180">受信トレイから会議の出欠確認を行う</span><span class="sxs-lookup"><span data-stu-id="1cff8-180">RSVP to meetings from the inbox.</span></span>
    
- <span data-ttu-id="1cff8-181">電子メールと予定表の予定に、情報の迅速な処理に役立つ直感的なアイコンを使用する</span><span class="sxs-lookup"><span data-stu-id="1cff8-181">Use intuitive icons in email and calendar appointments that help them process information quickly</span></span>
    
- <span data-ttu-id="1cff8-182">すべてのデバイスで一貫性のある使い慣れた Outlook エクスペリエンスを使用する</span><span class="sxs-lookup"><span data-stu-id="1cff8-182">Use a consistent and familiar Outlook experience across all devices</span></span>
    
- <span data-ttu-id="1cff8-183">簡単に予定表から Skype 会議を起動して参加する</span><span class="sxs-lookup"><span data-stu-id="1cff8-183">Easily launch and join Skype meetings from the calendar</span></span>
    
- <span data-ttu-id="1cff8-184">IRM の暗号化され保護された電子メールを読み、返信する</span><span class="sxs-lookup"><span data-stu-id="1cff8-184">Read and respond to IRM encrypted and protected emails</span></span>
    
- <span data-ttu-id="1cff8-185">OneDrive for Business に保存されているファイルを共有する</span><span class="sxs-lookup"><span data-stu-id="1cff8-185">Share files stored in OneDrive for Business</span></span>
    
- <span data-ttu-id="1cff8-186">タップで自動応答を設定する</span><span class="sxs-lookup"><span data-stu-id="1cff8-186">Set Automatic Replies with a tap</span></span>
    
- <span data-ttu-id="1cff8-187">共有された予定表や委任された予定表を表示および管理する</span><span class="sxs-lookup"><span data-stu-id="1cff8-187">View and manage shared and delegated calendars</span></span>
    
- <span data-ttu-id="1cff8-188">数回のタップで会社のグローバル アドレス一覧を検索する</span><span class="sxs-lookup"><span data-stu-id="1cff8-188">Search their company's global address list with a few taps</span></span>
    
- <span data-ttu-id="1cff8-189">他のユーザーの空き時間情報を表示して、全員が参加できる会議時間をスケジュールする</span><span class="sxs-lookup"><span data-stu-id="1cff8-189">View coworker's availability and schedule a meeting time that works for everyone</span></span>
    
- <span data-ttu-id="1cff8-190">招待状の承諾、仮承諾、辞退のステータスを参照する</span><span class="sxs-lookup"><span data-stu-id="1cff8-190">See invitees accept, tentative, and decline status</span></span>
    
- <span data-ttu-id="1cff8-191">電話から予定表を直接共有する</span><span class="sxs-lookup"><span data-stu-id="1cff8-191">Share calendars right from their phones</span></span>
    
- <span data-ttu-id="1cff8-192">予定表から直接 Skype 会議を起動し、参加する</span><span class="sxs-lookup"><span data-stu-id="1cff8-192">Start and join Skype meetings right from a calendar</span></span>
    
- <span data-ttu-id="1cff8-193">1 か所で仕事と個人の予定表にアクセスする (アプリの切り替え不要)</span><span class="sxs-lookup"><span data-stu-id="1cff8-193">Access work and personal calendars in one place, without switching apps</span></span>
    
## <a name="exchange-activesync"></a><span data-ttu-id="1cff8-194">Exchange ActiveSync</span><span class="sxs-lookup"><span data-stu-id="1cff8-194">Exchange ActiveSync</span></span>

<span data-ttu-id="1cff8-195">Exchange Online は、モバイル デバイスと Exchange Online の間でメールボックス データを同期する Microsoft Exchange ActiveSync プロトコルをサポートしているため、電子メール、予定表、連絡先、タスクに外出先からアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="1cff8-195">Exchange Online supports the Microsoft Exchange ActiveSync protocol, which synchronizes mailbox data between mobile devices and Exchange Online, so users can access their email, calendar, contacts, and tasks on the go.</span></span>
  
<span data-ttu-id="1cff8-p112">Microsoft の Windows Phone、Apple の iPhone および iPad、Android の携帯電話およびタブレットなど、さまざまなモバイル デバイスが Exchange ActiveSync に対応しています。携帯電話やモバイル デバイスだけでなく、Windows Phone の電子メール アプリケーションも Exchange Online への接続に Exchange ActiveSync を使用しています。最新の Exchange ActiveSync ライセンシーの完全な一覧は、Exchange ActiveSync ライセンス サイトで提供しています。</span><span class="sxs-lookup"><span data-stu-id="1cff8-p112">A wide range of mobile devices work with Exchange ActiveSync, including Microsoft Windows Phone, Apple iPhone and iPad, and Android phones and tablets. In addition to mobile phones and devices, the Mail application in Windows Phone uses Exchange ActiveSync to connect to Exchange Online. A complete list of current Exchange ActiveSync licensees is available at the Exchange ActiveSync Licensing site.</span></span>
  
<span data-ttu-id="1cff8-199">Exchange ActiveSync の詳細については、「[Exchange Online のクライアントとモバイル](https://go.microsoft.com/fwlink/p/?LinkId=271792)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="1cff8-199">For more information about Exchange ActiveSync, see [Exchange ActiveSync](https://go.microsoft.com/fwlink/p/?LinkId=271792).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="1cff8-200">各メールボックスの Exchange ActiveSync デバイスの最大数は 100 です。</span><span class="sxs-lookup"><span data-stu-id="1cff8-200">The maximum number of Exchange ActiveSync devices per mailbox is 100.</span></span> 
  
## <a name="applications-developed-with-exchange-web-services-ews"></a><span data-ttu-id="1cff8-201">Exchange Web サービス (EWS) で開発されたアプリケーション</span><span class="sxs-lookup"><span data-stu-id="1cff8-201">Applications developed with Exchange Web Services (EWS)</span></span>

 <span data-ttu-id="1cff8-202">管理者は、Exchange Web サービス (EWS) または EWS Managed API を使用して開発されたアプリケーションを利用することで、社内で、Azure 内で、または他のホステッド サービス内で実行しているアプリケーションから Exchange Online で保存されたデータにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="1cff8-202">Applications developed using Exchange Web Services (EWS) or the EWS Managed API let administrators access data stored with Exchange Online from applications that are running on-premises, in Azure, or in other hosted services.</span></span> 
  
<span data-ttu-id="1cff8-203">Exchange Web サービスで開発されたアプリケーションの詳細については、「[Exchange の Web サービス](https://go.microsoft.com/fwlink/?LinkId=325346)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="1cff8-203">For more information on applications developed with Exchange Web Services, see [Web Services in Exchange](https://go.microsoft.com/fwlink/?LinkId=325346).</span></span>
  
## <a name="pop-and-imap"></a><span data-ttu-id="1cff8-204">POP と IMAP</span><span class="sxs-lookup"><span data-stu-id="1cff8-204">POP and IMAP</span></span>

<span data-ttu-id="1cff8-p113">Exchange Online は、POP3 および IMAP4 プロトコルによるメールボックスへのアクセスをサポートします。POP および IMAP でのアクセスには、SSL による暗号化が必要です。既定では、POP がすべてのユーザーに対して有効になっています。POP および IMAP の接続設定は Outlook on the web で確認できます。管理者はユーザーごとに POP および IMAP によるアクセスを無効にできます。</span><span class="sxs-lookup"><span data-stu-id="1cff8-p113">Exchange Online supports mailbox access through both POP3 and IMAP4 protocols. POP and IMAP access requires encryption using SSL. POP is enabled by default for all users. Users can view their POP and IMAP connection settings in Outlook on the web. Administrators can disable POP and IMAP access on a per-user basis.</span></span>
  
<span data-ttu-id="1cff8-210">POP3 および IMAP4 接続の詳細については、「[Exchange Server 2013 での POP3 と IMAP4](https://go.microsoft.com/fwlink/p/?LinkId=272070)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="1cff8-210">For more information about POP3 and IMAP4 connectivity, see [POP3 and IMAP4](https://go.microsoft.com/fwlink/p/?LinkId=272070).</span></span>
  
## <a name="smtp"></a><span data-ttu-id="1cff8-211">SMTP</span><span class="sxs-lookup"><span data-stu-id="1cff8-211">SMTP</span></span>

<span data-ttu-id="1cff8-p114">簡易メール転送プロトコル (SMTP) は、IMAP または POP で Exchange Online に接続しているクライアントからのメール送信に使用されます。SMTP は、Exchange サーバーを経由したルーティングおよび配信を行うためのプライマリ プロトコルです。Exchange Online は、SMTP によるメール送信を必要とするお客様社内の承認済みアプリケーションに対して、2 種類の SMTP リレー サービスをサポートしています。</span><span class="sxs-lookup"><span data-stu-id="1cff8-p114">Simple Mail Transfer Protocol (SMTP) is used to send outbound mail for clients that connect to Exchange Online through IMAP or POP. It is the primary protocol for routing and delivery through Exchange Server. Exchange Online supports two types of SMTP relay services for authorized internal customer applications that require SMTP mail submission:</span></span>
  
- <span data-ttu-id="1cff8-215">管理環境内のユーザーに対する SMTP メッセージの送信。</span><span class="sxs-lookup"><span data-stu-id="1cff8-215">SMTP message submission to users inside the managed environment.</span></span>
    
- <span data-ttu-id="1cff8-216">管理環境外のアドレスに対する認証済み SMTP メッセージ リレー。</span><span class="sxs-lookup"><span data-stu-id="1cff8-216">Authenticated SMTP message relay to addresses outside the managed environment.</span></span>
    
> [!IMPORTANT]
> <span data-ttu-id="1cff8-p115">SMTP リレーを行うには、承認済み送信元サーバーの IP アドレスが必要です。SMTP で電子メールを送信するには、トランスポート層セキュリティ (TLS) による暗号化と認証が必要です。</span><span class="sxs-lookup"><span data-stu-id="1cff8-p115">IP addresses for authorized source servers are required to allow SMTP relay. Transport Layer Security (TLS) encryption and authentication is required when using SMTP to send email.</span></span> 
  
## <a name="blackberry-devices"></a><span data-ttu-id="1cff8-219">BlackBerry® デバイス</span><span class="sxs-lookup"><span data-stu-id="1cff8-219">BlackBerry® devices</span></span>

<span data-ttu-id="1cff8-p116">Office 365 の電子メールは BlackBerry® デバイスで利用できます (Exchange ActiveSync 経由)。オプションの詳細については、次のトピックを参照してください。</span><span class="sxs-lookup"><span data-stu-id="1cff8-p116">Office 365 email is available on BlackBerry® devices via Exchange ActiveSync. To find out what your options are, see these topics:</span></span>
  
- [<span data-ttu-id="1cff8-222">BlackBerry で電子メールをセットアップする</span><span class="sxs-lookup"><span data-stu-id="1cff8-222">Set up email on a BlackBerry device</span></span>](https://go.microsoft.com/fwlink/?linkid=863394)
    
- [<span data-ttu-id="1cff8-223">BlackBerry デバイス 7.1 OS 以前で電子メールをセットアップする</span><span class="sxs-lookup"><span data-stu-id="1cff8-223">Set up email on a BlackBerry device 7.1 OS and earlier</span></span>](https://go.microsoft.com/fwlink/?linkid=863403)
    
<span data-ttu-id="1cff8-224">詳細については、「[BlackBerry](../office-365-platform-service-description/blackberry.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="1cff8-224">For more information, see [BlackBerry](../office-365-platform-service-description/blackberry.md).</span></span>
  
> [!NOTE]
> <span data-ttu-id="1cff8-p117">中国の 21Vianet が運用している Office 365 を使用している場合は、BlackBerry Business Cloud Services が使用できません。ただし、Exchange ActiveSync デバイスまたは Research in Motion (RIM: BlackBerry ワイヤレス電子メール ソリューション) からの製品を使用して、Blackberry Enterprise Server (BES) を実行することはできます。</span><span class="sxs-lookup"><span data-stu-id="1cff8-p117">If you are using Office 365 operated by 21Vianet in China, BlackBerry Business Cloud Services is not available. However, you can use Exchange ActiveSync devices or an offering from Research in Motion (RIM, the BlackBerry wireless email solution) to run Blackberry Enterprise Server (BES).</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="1cff8-227">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="1cff8-227">Feature Availability</span></span>

<span data-ttu-id="1cff8-228">Office 365 のプラン、スタンドアロンのオプション、オンプレミス ソリューション全体の機能の可用性を表示するには、「[Exchange Online サービスの説明](exchange-online-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="1cff8-228">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

