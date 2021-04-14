---
title: クライアントとモバイル デバイス
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-clients-and-mobile-devices
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: fce4ac03-f30a-4152-9145-4a9ce564c966
description: Exchange Online は、Outlook のデスクトップバージョンとモバイル バージョン、および Outlook on the web で動作します。
ms.openlocfilehash: 3aa0c2bbdf9b55b6a3544919143fd9d5e5cfed24
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653119"
---
# <a name="clients-and-mobile-devices"></a><span data-ttu-id="6df91-103">クライアントとモバイル デバイス</span><span class="sxs-lookup"><span data-stu-id="6df91-103">Clients and mobile devices</span></span>

## <a name="microsoft-outlook"></a><span data-ttu-id="6df91-104">Microsoft Outlook</span><span class="sxs-lookup"><span data-stu-id="6df91-104">Microsoft Outlook</span></span>

<span data-ttu-id="6df91-105">Microsoft Outlook は、予定表、連絡先、タスク、および以下の主な機能をサポートする電子メール プログラムです。</span><span class="sxs-lookup"><span data-stu-id="6df91-105">Microsoft Outlook is an email program that includes support for calendar, contacts, tasks, and the following key features:</span></span>
  
- <span data-ttu-id="6df91-106">**MAPI over HTTP** - メッセージング アプリケーション プログラム インターフェイス (MAPI) over HTTP を使用すると、Outlook ユーザーは組織のファイアウォールの外部からインターネットを使用して Exchange Online メールボックスに接続できます。</span><span class="sxs-lookup"><span data-stu-id="6df91-106">**MAPI over HTTP** - Messaging Application Program Interface (MAPI) over HTTP allows Outlook users to connect to Exchange Online mailboxes over the internet from outside their organization's firewall.</span></span> <span data-ttu-id="6df91-107">MAPI over HTTP は、Outlook Anywhere の長期的な置き換えとしてサポートされています。</span><span class="sxs-lookup"><span data-stu-id="6df91-107">MAPI over HTTP, the long term replacement for Outlook Anywhere.</span></span> <span data-ttu-id="6df91-108">この接続方法は、接続回復力の向上、より安全なサインイン、拡張性、および IT とサポートの拡張機能を提供します。</span><span class="sxs-lookup"><span data-stu-id="6df91-108">This connectivity method offers improved connection resiliency, more secure sign-in, extensibility, as well as enhancements for IT and support.</span></span> <span data-ttu-id="6df91-109">詳細については、「 [Office 365 における RPC over HTTP のサポート終了 (2017 年 10 月 31 日) に関する情報](/exchange/troubleshoot/administration/rpc-over-http-end-of-support)」および「[MAPI over HTTP](/exchange/mapi-over-http-exchange-2013-help)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="6df91-109">To learn more, see [RPC over HTTP reaches end of support in Office 365](/exchange/troubleshoot/administration/rpc-over-http-end-of-support) and [MAPI over HTTP](/exchange/mapi-over-http-exchange-2013-help).</span></span>

- <span data-ttu-id="6df91-110">**自動検出** - 自動検出サービス機能は、Exchange Online で動作する Outlook を自動的に構成します。</span><span class="sxs-lookup"><span data-stu-id="6df91-110">**Autodiscover** - The Autodiscover service feature automatically configures Outlook to work with Exchange Online.</span></span> <span data-ttu-id="6df91-111">Outlook ユーザーは、電子メール アドレスとパスワードを使って初めて Exchange Online にサインインしたときに、必要なプロファイル設定を受信します。</span><span class="sxs-lookup"><span data-stu-id="6df91-111">Outlook users can receive their required profile settings directly from Exchange Online the first time they sign in with their email address and password.</span></span> <span data-ttu-id="6df91-112">これらの設定は、ユーザーのプロファイルの作成と管理に必要な情報で Outlook クライアントを自動的に更新します。</span><span class="sxs-lookup"><span data-stu-id="6df91-112">These settings automatically update the Outlook client with the information necessary to create and maintain the user's profile.</span></span> <span data-ttu-id="6df91-113">自動検出サービスを使用するには SSL 証明書が必要です。</span><span class="sxs-lookup"><span data-stu-id="6df91-113">An SSL certificate is required to use the Autodiscover service.</span></span> <span data-ttu-id="6df91-114">この SSL 証明書は、単一のプライマリ SSL ドメインに限定されます。</span><span class="sxs-lookup"><span data-stu-id="6df91-114">This SSL certificate is limited to a single primary SSL domain.</span></span> 

- <span data-ttu-id="6df91-115">**Exchange キャッシュ モード** - Exchange キャッシュ モード機能を使用すると、Outlook ユーザーはインターネットに接続されていないときに Exchange Online メールボックスのローカル コピーにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="6df91-115">**Cached Exchange Mode** - The Cached Exchange Mode feature allows Outlook users to access local copies of their Exchange Online mailboxes when they are not connected to the internet.</span></span> <span data-ttu-id="6df91-116">Exchange キャッシュ モードは、Outlook でユーザーの Exchange メールボックスのクライアント側コピーを保持し、このコピーを電子メール サーバーと自動的に同期します。</span><span class="sxs-lookup"><span data-stu-id="6df91-116">Cached Exchange Mode retains a client-side copy of users' Exchange mailboxes in Outlook and automatically synchronizes this copy with the email server.</span></span> <span data-ttu-id="6df91-117">Exchange キャッシュ モードで Outlook を使用することをお勧めします。オフライン アクセスを提供し、クライアントとサーバー間のネットワーク状態が理想的ではない場合でも、応答性の高いユーザー エクスペリエンスを提供するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="6df91-117">We recommend using Outlook in Cached Exchange Mode because it provides offline access and helps to provide a responsive user experience even when network conditions between the client and the server are not ideal.</span></span> 

<span data-ttu-id="6df91-p104">既定では、すべてのユーザーが Outlook からアクセスできます。管理者は Windows PowerShell を使って特定のユーザーまたはグループのアクセスを無効にできます。Exchange Online へのアクセスには、最新の Service Pack をインストールした最新バージョンの Outlook を使用してください。</span><span class="sxs-lookup"><span data-stu-id="6df91-p104">By default, Outlook access is enabled for all users. Administrators can disable access for specific users or groups through Windows PowerShell. We recommend using the latest version of Outlook—with the latest service pack installed—to access Exchange Online.</span></span> 
  
<span data-ttu-id="6df91-121">Exchange 2016 および Exchange Online でサポートされている Outlook クライアントの詳細については、「System [Requirements for](https://products.office.com/office-system-requirements)exchange 2016」を参照Office。</span><span class="sxs-lookup"><span data-stu-id="6df91-121">For information about which Outlook clients are supported by Exchange 2016 and Exchange Online, see [System Requirements for Office](https://products.office.com/office-system-requirements).</span></span> 

<span data-ttu-id="6df91-122">Microsoft 365 は、最新のブラウザーとバージョンのブラウザーを使用するように設計Office。</span><span class="sxs-lookup"><span data-stu-id="6df91-122">Microsoft 365 is designed to work with the latest browsers and versions of Office.</span></span> <span data-ttu-id="6df91-123">以前のブラウザーとバージョンのブラウザーを使用している場合Officeメインストリーム サポートに含めなかった場合は、次のコマンドを実行します。</span><span class="sxs-lookup"><span data-stu-id="6df91-123">If you use older browsers and versions of Office that aren't in mainstream support:</span></span>

- <span data-ttu-id="6df91-124">Microsoft は意図的にサービスへの接続を妨げるのではなく、時間の流れによってエクスペリエンスの品質が低下する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6df91-124">Microsoft won't deliberately prevent you from connecting to the service, but the quality of your experience may diminish over time.</span></span>
- <span data-ttu-id="6df91-125">Microsoft は、セキュリティ以外の問題を解決するためのソフトウェア更新プログラムを提供しない。</span><span class="sxs-lookup"><span data-stu-id="6df91-125">Microsoft won't provide software updates to resolve non-security related problems.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="6df91-126">Outlook は、Exchange Online サブスクリプションの価格には含まれません。</span><span class="sxs-lookup"><span data-stu-id="6df91-126">Outlook is not provided as part of the Exchange Online subscription price.</span></span> <span data-ttu-id="6df91-127">Microsoft 365 Apps for enterprise (Microsoft Outlook を含む) は、一部のプランに含まれており、個別のサブスクリプションとして購入できます。</span><span class="sxs-lookup"><span data-stu-id="6df91-127">Microsoft 365 Apps for enterprise (which includes Microsoft Outlook) is included in some plans and can be purchased as a separate subscription.</span></span> <span data-ttu-id="6df91-128">POP を使用して Exchange Online の電子メール アカウントに接続する場合、次の制限事項が表示されます。</span><span class="sxs-lookup"><span data-stu-id="6df91-128">You will see the following limitations if you use POP to connect to an Exchange Online email account:</span></span>
> - <span data-ttu-id="6df91-129">予定表情報がない</span><span class="sxs-lookup"><span data-stu-id="6df91-129">No calendar information</span></span>
>- <span data-ttu-id="6df91-130">空き時間情報がない</span><span class="sxs-lookup"><span data-stu-id="6df91-130">No free/busy information</span></span>
>- <span data-ttu-id="6df91-131">グローバル アドレス一覧がない</span><span class="sxs-lookup"><span data-stu-id="6df91-131">No Global Address List</span></span>
>- <span data-ttu-id="6df91-132">プッシュ メールがない</span><span class="sxs-lookup"><span data-stu-id="6df91-132">No push email</span></span>
>- <span data-ttu-id="6df91-133">POP 経由で接続した場合、すべてのメッセージはクライアントにダウンロードされ、複数のコンピューターまたはデバイス間 (ノート PC と携帯電話の間など) で同期されることはありません。</span><span class="sxs-lookup"><span data-stu-id="6df91-133">When connecting through POP, all messages will be downloaded to the client and there will be no synchronization between multiple computers or devices (such as between a laptop and a phone).</span></span> 
  
## <a name="outlook-on-the-web"></a><span data-ttu-id="6df91-134">Web 上の Outlook</span><span class="sxs-lookup"><span data-stu-id="6df91-134">Outlook on the web</span></span>

<span data-ttu-id="6df91-135">Outlook on the web は、Exchange Online と連携する Web ベースの Outlook 電子メール プログラムです。</span><span class="sxs-lookup"><span data-stu-id="6df91-135">Outlook on the web is a web-based version of the Outlook email program that is used with Exchange Online.</span></span> <span data-ttu-id="6df91-136">これにより、ユーザーはインターネットに接続する場所から Web ブラウザーを介して電子メール、予定表、連絡先にアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="6df91-136">It lets users access their email, calendar, and contacts through a web browser from wherever they connect to the internet.</span></span> <span data-ttu-id="6df91-137">サポートされているブラウザーについては、「[Office のシステム要件](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="6df91-137">For information about supported browsers, see [Supported browsers for Outlook on the web for business](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006).</span></span>
  
<span data-ttu-id="6df91-138">Outlook on the web のクライアントには 2 つのバージョンがあり、どちらも Exchange Online とともに利用できます。</span><span class="sxs-lookup"><span data-stu-id="6df91-138">Outlook on the web comes in two client versions, both of which can be used with Exchange Online:</span></span>
  
- <span data-ttu-id="6df91-139">**Outlook on the web** - 標準バージョンの Outlook on the web は、Exchange Online ユーザーに Outlook ユーザーと最も似たメッセージング エクスペリエンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="6df91-139">**Outlook on the web** - The standard version of Outlook on the web provides Exchange Online users with a messaging experience most similar to that of Outlook users.</span></span> <span data-ttu-id="6df91-140">これは、ほとんどの新しい Web ブラウザーをサポートし、タブレットやスマートフォン、デスクトップ、ラップトップでの使用に最適化されています。</span><span class="sxs-lookup"><span data-stu-id="6df91-140">It supports most newer web browsers and is optimized for use on tablets and smartphones as well as desktops and laptops.</span></span> <span data-ttu-id="6df91-141">ユーザーは、メッセージの読み取りおよび送信、連絡先の整理、予定と会議のスケジュールを設定できます。</span><span class="sxs-lookup"><span data-stu-id="6df91-141">Users can read and send messages, organize contacts, and schedule appointments and meetings.</span></span> <span data-ttu-id="6df91-142">既定のアクティビティ ベースのタイム アウトは 6 時間に設定されますが[](/powershell/module/exchange/set-organizationconfig)、管理者は 5 分から 8 時間Windows PowerShellで構成できます。</span><span class="sxs-lookup"><span data-stu-id="6df91-142">The default activity-based time-out is set at six hours, but it can be [configured by an administrator in Windows PowerShell](/powershell/module/exchange/set-organizationconfig) from 5 minutes to 8 hours.</span></span> <span data-ttu-id="6df91-143">このタイム アウトは、ボタンの選択やメッセージの選択など、Web アプリ内でのユーザー操作によって異なります。</span><span class="sxs-lookup"><span data-stu-id="6df91-143">This time-out depends on user interactions within the web app, such as selecting a button or selecting a message.</span></span> <span data-ttu-id="6df91-144">セキュリティ駆動型の個別のタイム アウトも用意されています。これは構成可能ではなく、ユーザーのアクティビティに関係なく発生します。</span><span class="sxs-lookup"><span data-stu-id="6df91-144">There is also a separate security-driven time-out, which is not configurable and will occur regardless of user activity.</span></span> <span data-ttu-id="6df91-145">ユーザーが 8 時間ログインしている場合、OWA は自動的にユーザーをログアウトし、再認証を要求します。</span><span class="sxs-lookup"><span data-stu-id="6df91-145">If a user is logged in for 8 hours, OWA will automatically log the user out and ask for re-authentication.</span></span> 

- <span data-ttu-id="6df91-146">**Outlook on the web の** 軽量バージョン - Web 上の Outlook の軽量バージョンは、ほぼすべての Web ブラウザーを使用して Exchange Online ユーザーがメールボックスにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="6df91-146">**The light version of Outlook on the web** - The light version of Outlook on the web provides Exchange Online users access to the mailbox using almost any web browser.</span></span> <span data-ttu-id="6df91-147">ユーザーは、メッセージの読み取りおよび送信、連絡先の整理、予定と会議のスケジュールを設定できます。</span><span class="sxs-lookup"><span data-stu-id="6df91-147">Users can read and send messages, organize contacts, and schedule appointments and meetings.</span></span> <span data-ttu-id="6df91-148">既定のアクティビティ ベースのタイム アウトは 6 時間に設定されますが[](/powershell/module/exchange/set-organizationconfig)、管理者は 5 分から 8 時間Windows PowerShellで構成できます。</span><span class="sxs-lookup"><span data-stu-id="6df91-148">The default activity-based time-out is set at six hours, but it can be [configured by an administrator in Windows PowerShell](/powershell/module/exchange/set-organizationconfig) from 5 minutes to 8 hours.</span></span> <span data-ttu-id="6df91-149">このタイム アウトは、ボタンの選択やメッセージの選択など、Web アプリ内でのユーザー操作によって異なります。</span><span class="sxs-lookup"><span data-stu-id="6df91-149">This time-out depends on user interactions within the web app, such as selecting a button or selecting a message.</span></span> <span data-ttu-id="6df91-150">セキュリティ駆動型の個別のタイム アウトも用意されています。これは構成可能ではなく、ユーザーのアクティビティに関係なく発生します。</span><span class="sxs-lookup"><span data-stu-id="6df91-150">There is also a separate security-driven time-out, which is not configurable and will occur regardless of user activity.</span></span> <span data-ttu-id="6df91-151">ユーザーが 8 時間ログインしている場合、ライト バージョンの OWA は自動的にユーザーをログアウトし、再認証を求めるメッセージを表示します。</span><span class="sxs-lookup"><span data-stu-id="6df91-151">If a user is logged in for 8 hours, the light version of OWA will automatically log the user out and ask for re-authentication.</span></span> 

<span data-ttu-id="6df91-152">Outlook on the web は、モバイル バージョンでも利用可能です。</span><span class="sxs-lookup"><span data-stu-id="6df91-152">Outlook on the web also is available in mobile versions.</span></span> <span data-ttu-id="6df91-153">詳細については、「[このページ](https://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="6df91-153">For more information, see [this page](https://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409).</span></span>
  
## <a name="outlook-for-mac"></a><span data-ttu-id="6df91-154">Outlook for Mac</span><span class="sxs-lookup"><span data-stu-id="6df91-154">Outlook for Mac</span></span>

<span data-ttu-id="6df91-155">Exchange Online は Microsoft Outlook for Mac をサポートしています。Microsoft Outlook for Mac では電子メール、予定表、アドレス帳、タスク リスト、ノートの一覧を使用できます。</span><span class="sxs-lookup"><span data-stu-id="6df91-155">Exchange Online supports Microsoft Outlook for Mac, which provides email, calendar, an address book, a task list, and a note list.</span></span>
  
## <a name="outlook-for-ios-android-and-windows-phone"></a><span data-ttu-id="6df91-156">Outlook for iOS、Android、および Windows Phone</span><span class="sxs-lookup"><span data-stu-id="6df91-156">Outlook for iOS, Android, and Windows Phone</span></span>

<span data-ttu-id="6df91-p111">Exchange Online は、iOS、Android、および Windows Phone で使用可能な Outlook アプリで動作します。これらのデバイスのいずれかで、アプリ ストアを使用して Outlook アプリを検索します。モバイル OS での概要を次に示します。</span><span class="sxs-lookup"><span data-stu-id="6df91-p111">Exchange Online works with Outlook apps available for iOS, Android, and Windows Phone. On any of these devices, use the app store to find the Outlook app. Here's a breakdown by mobile OS.</span></span><br><br>
  
| <span data-ttu-id="6df91-160">デバイス</span><span class="sxs-lookup"><span data-stu-id="6df91-160">Device</span></span> | <span data-ttu-id="6df91-161">Android</span><span class="sxs-lookup"><span data-stu-id="6df91-161">Android</span></span> | <span data-ttu-id="6df91-162">iOS</span><span class="sxs-lookup"><span data-stu-id="6df91-162">iOS</span></span> | <span data-ttu-id="6df91-163">Windows Phone</span><span class="sxs-lookup"><span data-stu-id="6df91-163">Windows Phone</span></span> |
|:-----|:-----|:-----|:-----|
|<span data-ttu-id="6df91-164">Outlook モバイル アプリ利用の可否</span><span class="sxs-lookup"><span data-stu-id="6df91-164">Outlook mobile app availability</span></span>  <br/> |<span data-ttu-id="6df91-165">可</span><span class="sxs-lookup"><span data-stu-id="6df91-165">Yes</span></span>  <br/> [<span data-ttu-id="6df91-166">Outlook for Android の入手</span><span class="sxs-lookup"><span data-stu-id="6df91-166">Get Outlook for Android</span></span>](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |<span data-ttu-id="6df91-167">可</span><span class="sxs-lookup"><span data-stu-id="6df91-167">Yes</span></span>  <br/> [<span data-ttu-id="6df91-168">Outlook for iOS の入手</span><span class="sxs-lookup"><span data-stu-id="6df91-168">Get Outlook for iOS</span></span>](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |<span data-ttu-id="6df91-169">組み込み</span><span class="sxs-lookup"><span data-stu-id="6df91-169">Built-in</span></span>  <br/> |
|<span data-ttu-id="6df91-170">Exchange Online と互換性のある組み込みの電子メール アプリ</span><span class="sxs-lookup"><span data-stu-id="6df91-170">Built-in email apps compatible with Exchange Online</span></span>  <br/> |<span data-ttu-id="6df91-171">Gmail アプリ/Samsung 電子メール アプリ</span><span class="sxs-lookup"><span data-stu-id="6df91-171">Gmail app/Samsung Email app</span></span>  <br/> |<span data-ttu-id="6df91-172">iOS メール アプリ</span><span class="sxs-lookup"><span data-stu-id="6df91-172">iOS Mail app</span></span>  <br/> |<span data-ttu-id="6df91-173">Outlook メール、予定表、連絡先</span><span class="sxs-lookup"><span data-stu-id="6df91-173">Outlook Mail, calendar, contacts</span></span>  <br/> |
|<span data-ttu-id="6df91-174">詳細情報</span><span class="sxs-lookup"><span data-stu-id="6df91-174">More information</span></span>  <br/> |[<span data-ttu-id="6df91-175">Android モバイルのセットアップ</span><span class="sxs-lookup"><span data-stu-id="6df91-175">Android mobile setup</span></span>](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[<span data-ttu-id="6df91-176">iPhone または iPad のセットアップ</span><span class="sxs-lookup"><span data-stu-id="6df91-176">iPhone or iPad setup</span></span>](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[<span data-ttu-id="6df91-177">Windows Phone のセットアップ</span><span class="sxs-lookup"><span data-stu-id="6df91-177">Windows Phone setup</span></span>](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |

<span data-ttu-id="6df91-178">また、Blackberry などのデバイスで Exchange Online を使用するためのオプションもあります。</span><span class="sxs-lookup"><span data-stu-id="6df91-178">There are also options for using Exchange Online with devices, including Blackberry.</span></span>
  
### <a name="feature-availability"></a><span data-ttu-id="6df91-179">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="6df91-179">Feature availability</span></span>

<span data-ttu-id="6df91-180">Outlook を使用すると、最新のモバイル アプリに期待される高速で直感的な電子メールと予定表のエクスペリエンスがユーザーに提供され、最高の機能をサポートする唯一のアプリになります。</span><span class="sxs-lookup"><span data-stu-id="6df91-180">Outlook gives users the fast, intuitive email and calendar experience that they expect from a modern mobile app, while being the only app to provide support for the best features.</span></span> <span data-ttu-id="6df91-181">これは、Microsoft の完全なエクスペリエンスをサポートするように特別に設計された唯一の電子メール アプリで、デスクトップからモバイルまで一貫したエクスペリエンスをユーザーに提供します。</span><span class="sxs-lookup"><span data-stu-id="6df91-181">It is the only email app specifically designed to support the full Microsoft experience, giving users a coherent experience from desktop to mobile.</span></span> <span data-ttu-id="6df91-182">Outlook は Intune、エンタープライズ モビリティとセキュリティ、および Exchange コントロールと統合され、データとユーザーの安全を確保します。</span><span class="sxs-lookup"><span data-stu-id="6df91-182">Outlook is integrated with Intune, enterprise mobility and security, and Exchange controls to keep data and users safe.</span></span>
  
<span data-ttu-id="6df91-183">Outlook を使用すると、ユーザーは次の機能を使用できます。</span><span class="sxs-lookup"><span data-stu-id="6df91-183">With Outlook, users can:</span></span>
  
- <span data-ttu-id="6df91-184">全日をモバイル デバイスから管理できます。</span><span class="sxs-lookup"><span data-stu-id="6df91-184">Manage their entire day from a mobile device.</span></span>

- <span data-ttu-id="6df91-185">仕事と個人情報を分離して安全に保ちながら、生産性を高めるために必要なアプリやサービスに接続します。</span><span class="sxs-lookup"><span data-stu-id="6df91-185">Connect to the apps and services they need to be productive, while keeping their work and personal information separate and secure.</span></span>

<span data-ttu-id="6df91-186">Outlook for iOS、Outlook for Android、または Outlook for Windows Phone を使用すると、次のことが可能になります。</span><span class="sxs-lookup"><span data-stu-id="6df91-186">With Outlook for iOS, Outlook for Android, or Outlook for Windows Phone, users can:</span></span> 
  
- <span data-ttu-id="6df91-187">優先受信トレイから優先的に重要なメールを受信するメリットを得る</span><span class="sxs-lookup"><span data-stu-id="6df91-187">Benefit from a focused inbox that priorities important email</span></span>

- <span data-ttu-id="6df91-188">一意の電子メールの習慣に合わせてスワイプのジェスチャーをカスタマイズする</span><span class="sxs-lookup"><span data-stu-id="6df91-188">Customize swipe gestures to match their unique email habits</span></span>

- <span data-ttu-id="6df91-189">予定表に直接追加できる旅行日程を作成する (一目で確認できる重要な情報を付加できる)</span><span class="sxs-lookup"><span data-stu-id="6df91-189">Create travel itineraries that can be added directly to the calendar, with key information available at a glance</span></span>

- <span data-ttu-id="6df91-190">受信トレイから会議の出欠確認を行う</span><span class="sxs-lookup"><span data-stu-id="6df91-190">RSVP to meetings from the inbox.</span></span>

- <span data-ttu-id="6df91-191">電子メールと予定表の予定に、情報の迅速な処理に役立つ直感的なアイコンを使用する</span><span class="sxs-lookup"><span data-stu-id="6df91-191">Use intuitive icons in email and calendar appointments that help them process information quickly</span></span>

- <span data-ttu-id="6df91-192">すべてのデバイスで一貫性のある使い慣れた Outlook エクスペリエンスを使用する</span><span class="sxs-lookup"><span data-stu-id="6df91-192">Use a consistent and familiar Outlook experience across all devices</span></span>

- <span data-ttu-id="6df91-193">簡単に予定表から Skype 会議を起動して参加する</span><span class="sxs-lookup"><span data-stu-id="6df91-193">Easily launch and join Skype meetings from the calendar</span></span>

- <span data-ttu-id="6df91-194">IRM の暗号化され保護された電子メールを読み、返信する</span><span class="sxs-lookup"><span data-stu-id="6df91-194">Read and respond to IRM encrypted and protected emails</span></span>

- <span data-ttu-id="6df91-195">OneDrive for Business に保存されているファイルを共有する</span><span class="sxs-lookup"><span data-stu-id="6df91-195">Share files stored in OneDrive for Business</span></span>

- <span data-ttu-id="6df91-196">タップで自動応答を設定する</span><span class="sxs-lookup"><span data-stu-id="6df91-196">Set Automatic Replies with a tap</span></span>

- <span data-ttu-id="6df91-197">共有された予定表や委任された予定表を表示および管理する</span><span class="sxs-lookup"><span data-stu-id="6df91-197">View and manage shared and delegated calendars</span></span>

- <span data-ttu-id="6df91-198">数回のタップで会社のグローバル アドレス一覧を検索する</span><span class="sxs-lookup"><span data-stu-id="6df91-198">Search their company's global address list with a few taps</span></span>

- <span data-ttu-id="6df91-199">他のユーザーの空き時間情報を表示して、全員が参加できる会議時間をスケジュールする</span><span class="sxs-lookup"><span data-stu-id="6df91-199">View coworker's availability and schedule a meeting time that works for everyone</span></span>

- <span data-ttu-id="6df91-200">招待状の承諾、仮承諾、辞退のステータスを参照する</span><span class="sxs-lookup"><span data-stu-id="6df91-200">See invitees accept, tentative, and decline status</span></span>

- <span data-ttu-id="6df91-201">電話から予定表を直接共有する</span><span class="sxs-lookup"><span data-stu-id="6df91-201">Share calendars right from their phones</span></span>

- <span data-ttu-id="6df91-202">予定表から直接 Skype 会議を起動し、参加する</span><span class="sxs-lookup"><span data-stu-id="6df91-202">Start and join Skype meetings right from a calendar</span></span>

- <span data-ttu-id="6df91-203">1 か所で仕事と個人の予定表にアクセスする (アプリの切り替え不要)</span><span class="sxs-lookup"><span data-stu-id="6df91-203">Access work and personal calendars in one place, without switching apps</span></span>
    
## <a name="exchange-activesync"></a><span data-ttu-id="6df91-204">Exchange ActiveSync</span><span class="sxs-lookup"><span data-stu-id="6df91-204">Exchange ActiveSync</span></span>

<span data-ttu-id="6df91-205">Exchange Online は、モバイル デバイスと Exchange Online の間でメールボックス データを同期する Microsoft Exchange ActiveSync プロトコルをサポートしているため、電子メール、予定表、連絡先、タスクに外出先からアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="6df91-205">Exchange Online supports the Microsoft Exchange ActiveSync protocol, which synchronizes mailbox data between mobile devices and Exchange Online, so users can access their email, calendar, contacts, and tasks on the go.</span></span>
  
<span data-ttu-id="6df91-p113">Microsoft の Windows Phone、Apple の iPhone および iPad、Android の携帯電話およびタブレットなど、さまざまなモバイル デバイスが Exchange ActiveSync に対応しています。携帯電話やモバイル デバイスだけでなく、Windows Phone の電子メール アプリケーションも Exchange Online への接続に Exchange ActiveSync を使用しています。最新の Exchange ActiveSync ライセンシーの完全な一覧は、Exchange ActiveSync ライセンス サイトで提供しています。</span><span class="sxs-lookup"><span data-stu-id="6df91-p113">A wide range of mobile devices work with Exchange ActiveSync, including Microsoft Windows Phone, Apple iPhone and iPad, and Android phones and tablets. In addition to mobile phones and devices, the Mail application in Windows Phone uses Exchange ActiveSync to connect to Exchange Online. A complete list of current Exchange ActiveSync licensees is available at the Exchange ActiveSync Licensing site.</span></span>
  
<span data-ttu-id="6df91-209">Exchange ActiveSync の詳細については、「[Exchange Online のクライアントとモバイル](/exchange/clients-and-mobile-in-exchange-online/clients-and-mobile-in-exchange-online)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="6df91-209">For more information about Exchange ActiveSync, see [Exchange ActiveSync](/exchange/clients-and-mobile-in-exchange-online/clients-and-mobile-in-exchange-online).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="6df91-210">各メールボックスの Exchange ActiveSync デバイスの最大数は 100 です。</span><span class="sxs-lookup"><span data-stu-id="6df91-210">The maximum number of Exchange ActiveSync devices per mailbox is 100.</span></span> 
  
## <a name="applications-developed-with-exchange-web-services-ews"></a><span data-ttu-id="6df91-211">Exchange Web サービス (EWS) で開発されたアプリケーション</span><span class="sxs-lookup"><span data-stu-id="6df91-211">Applications developed with Exchange Web Services (EWS)</span></span>

 <span data-ttu-id="6df91-212">管理者は、Exchange Web サービス (EWS) または EWS Managed API を使用して開発されたアプリケーションを利用することで、社内で、Azure 内で、または他のホステッド サービス内で実行しているアプリケーションから Exchange Online で保存されたデータにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="6df91-212">Applications developed using Exchange Web Services (EWS) or the EWS Managed API let administrators access data stored with Exchange Online from applications that are running on-premises, in Azure, or in other hosted services.</span></span> 
  
<span data-ttu-id="6df91-213">Exchange Web サービスで開発されたアプリケーションの詳細については、「[Exchange の Web サービス](/exchange/client-developer/exchange-web-services/explore-the-ews-managed-api-ews-and-web-services-in-exchange)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="6df91-213">For more information on applications developed with Exchange Web Services, see [Web Services in Exchange](/exchange/client-developer/exchange-web-services/explore-the-ews-managed-api-ews-and-web-services-in-exchange).</span></span>
  
## <a name="pop-and-imap"></a><span data-ttu-id="6df91-214">POP と IMAP</span><span class="sxs-lookup"><span data-stu-id="6df91-214">POP and IMAP</span></span>

<span data-ttu-id="6df91-p114">Exchange Online は、POP3 および IMAP4 プロトコルによるメールボックスへのアクセスをサポートします。POP および IMAP でのアクセスには、SSL による暗号化が必要です。既定では、POP がすべてのユーザーに対して有効になっています。POP および IMAP の接続設定は Outlook on the web で確認できます。管理者はユーザーごとに POP および IMAP によるアクセスを無効にできます。</span><span class="sxs-lookup"><span data-stu-id="6df91-p114">Exchange Online supports mailbox access through both POP3 and IMAP4 protocols. POP and IMAP access requires encryption using SSL. POP is enabled by default for all users. Users can view their POP and IMAP connection settings in Outlook on the web. Administrators can disable POP and IMAP access on a per-user basis.</span></span>
  
<span data-ttu-id="6df91-220">POP3 および IMAP4 接続の詳細については、「[Exchange Server 2013 での POP3 と IMAP4](/exchange/pop3-and-imap4-in-exchange-server-2013-exchange-2013-help)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="6df91-220">For more information about POP3 and IMAP4 connectivity, see [POP3 and IMAP4](/exchange/pop3-and-imap4-in-exchange-server-2013-exchange-2013-help).</span></span>
  
## <a name="smtp"></a><span data-ttu-id="6df91-221">SMTP</span><span class="sxs-lookup"><span data-stu-id="6df91-221">SMTP</span></span>

<span data-ttu-id="6df91-p115">簡易メール転送プロトコル (SMTP) は、IMAP または POP で Exchange Online に接続しているクライアントからのメール送信に使用されます。SMTP は、Exchange サーバーを経由したルーティングおよび配信を行うためのプライマリ プロトコルです。Exchange Online は、SMTP によるメール送信を必要とするお客様社内の承認済みアプリケーションに対して、2 種類の SMTP リレー サービスをサポートしています。</span><span class="sxs-lookup"><span data-stu-id="6df91-p115">Simple Mail Transfer Protocol (SMTP) is used to send outbound mail for clients that connect to Exchange Online through IMAP or POP. It is the primary protocol for routing and delivery through Exchange Server. Exchange Online supports two types of SMTP relay services for authorized internal customer applications that require SMTP mail submission:</span></span>
  
- <span data-ttu-id="6df91-225">管理環境内のユーザーに対する SMTP メッセージの送信。</span><span class="sxs-lookup"><span data-stu-id="6df91-225">SMTP message submission to users inside the managed environment.</span></span>

- <span data-ttu-id="6df91-226">管理環境外のアドレスに対する認証済み SMTP メッセージ リレー。</span><span class="sxs-lookup"><span data-stu-id="6df91-226">Authenticated SMTP message relay to addresses outside the managed environment.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="6df91-p116">SMTP リレーを行うには、承認済み送信元サーバーの IP アドレスが必要です。SMTP で電子メールを送信するには、トランスポート層セキュリティ (TLS) による暗号化と認証が必要です。</span><span class="sxs-lookup"><span data-stu-id="6df91-p116">IP addresses for authorized source servers are required to allow SMTP relay. Transport Layer Security (TLS) encryption and authentication is required when using SMTP to send email.</span></span> 
  
## <a name="blackberry-devices"></a><span data-ttu-id="6df91-229">BlackBerry デバイス</span><span class="sxs-lookup"><span data-stu-id="6df91-229">BlackBerry devices</span></span>

<span data-ttu-id="6df91-230">電子メールは、BlackBerry デバイス &reg; 上で、Exchange ActiveSync。</span><span class="sxs-lookup"><span data-stu-id="6df91-230">Email is available on BlackBerry&reg; devices via Exchange ActiveSync.</span></span> <span data-ttu-id="6df91-231">オプションの詳細については、次のトピックを参照してください。</span><span class="sxs-lookup"><span data-stu-id="6df91-231">To find out what your options are, see these topics:</span></span>
  
- [<span data-ttu-id="6df91-232">BlackBerry で電子メールをセットアップする</span><span class="sxs-lookup"><span data-stu-id="6df91-232">Set up email on a BlackBerry device</span></span>](https://go.microsoft.com/fwlink/?linkid=863394)

- [<span data-ttu-id="6df91-233">BlackBerry デバイス 7.1 OS 以前で電子メールをセットアップする</span><span class="sxs-lookup"><span data-stu-id="6df91-233">Set up email on a BlackBerry device 7.1 OS and earlier</span></span>](https://go.microsoft.com/fwlink/?linkid=863403)

<span data-ttu-id="6df91-234">詳細については、「[BlackBerry](../office-365-platform-service-description/blackberry.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="6df91-234">For more information, see [BlackBerry](../office-365-platform-service-description/blackberry.md).</span></span>
  
> [!NOTE]
> <span data-ttu-id="6df91-p118">中国の 21Vianet が運用している Office 365 を使用している場合は、BlackBerry Business Cloud Services が使用できません。ただし、Exchange ActiveSync デバイスまたは Research in Motion (RIM: BlackBerry ワイヤレス電子メール ソリューション) からの製品を使用して、Blackberry Enterprise Server (BES) を実行することはできます。</span><span class="sxs-lookup"><span data-stu-id="6df91-p118">If you are using Office 365 operated by 21Vianet in China, BlackBerry Business Cloud Services is not available. However, you can use Exchange ActiveSync devices or an offering from Research in Motion (RIM, the BlackBerry wireless email solution) to run Blackberry Enterprise Server (BES).</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="6df91-237">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="6df91-237">Feature availability</span></span>

<span data-ttu-id="6df91-238">プラン、スタンドアロン オプション、オンプレミス ソリューションの機能の可用性を表示するには、「Exchange Online サービスの説明 [」を参照してください](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="6df91-238">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online service description](exchange-online-service-description.md).</span></span>
