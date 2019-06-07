---
title: 検索
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 06/05/2019
audience: ITPro
ms.topic: reference
f1_keywords:
- sharepoint-online-search-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cb36484c-0e8f-480e-be88-5daa8bf2d47d
description: SharePoint Online は、組織がデジタル情報を格納、共有、および管理するのに役立つ Web ベースのツールとテクノロジの集合です。 このホスト型サービスは Microsoft SharePoint Server 2013 上に構築されており、プロジェクトの作業、データとドキュメントの一元的な保存、および他のユーザーとの情報の共有を行うのに適しています。 次の検索機能は、ユーザーが業務の遂行に必要な情報を検索するために役立ちます。 検索は、関連性、絞り込み条件、ユーザーの組み合わせです。
ms.openlocfilehash: 512ebe26388ed4fdfb49f5a55c7a2adfe2b64cd7
ms.sourcegitcommit: 02cceb48c46295b2c75835b872a5bda17ba1a424
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/06/2019
ms.locfileid: "34742166"
---
# <a name="search"></a><span data-ttu-id="31b31-106">検索</span><span class="sxs-lookup"><span data-stu-id="31b31-106">Search</span></span>

<span data-ttu-id="31b31-107">SharePoint Online は、組織がデジタル情報を格納、共有、および管理するのに役立つ Web ベースのツールとテクノロジの集合です。</span><span class="sxs-lookup"><span data-stu-id="31b31-107">SharePoint Online is a collection of Web-based tools and technologies that help your organization store, share, and manage digital information.</span></span> <span data-ttu-id="31b31-108">このホスト型サービスは Microsoft SharePoint Server 2013 上に構築されており、プロジェクトの作業、データとドキュメントの一元的な保存、および他のユーザーとの情報の共有を行うのに適しています。</span><span class="sxs-lookup"><span data-stu-id="31b31-108">Built on Microsoft SharePoint Server 2013, this hosted service is ideal for working on projects, storing data and documents in a central location, and sharing information with others.</span></span> <span data-ttu-id="31b31-109">次の検索機能は、ユーザーが業務の遂行に必要な情報を検索するために役立ちます。</span><span class="sxs-lookup"><span data-stu-id="31b31-109">The following Search features help people find the information that they need to do their jobs.</span></span> <span data-ttu-id="31b31-110">検索は、関連性、絞り込み条件、ユーザーの組み合わせです。</span><span class="sxs-lookup"><span data-stu-id="31b31-110">Search is a combination of relevance, refinement, and people.</span></span>
  
## <a name="continuous-crawls"></a><span data-ttu-id="31b31-111">継続的クロール</span><span class="sxs-lookup"><span data-stu-id="31b31-111">Continuous crawls</span></span>
<span data-ttu-id="31b31-112"><a name="bkmk_ContinuousCrawl"> </a></span><span class="sxs-lookup"><span data-stu-id="31b31-112"></span></span>

<span data-ttu-id="31b31-p103">継続的クロールは、SharePoint サイト内のコンテンツを頻繁にクロールすることによって、検索結果を最新の状態に保ちます。SharePoint Online では継続的クロールが有効であり、Microsoft によって管理されたクロール頻度に従います。SharePoint Server 2013 では、管理者が継続的クロールを有効にして、継続的クロールの頻度を管理できます。[SharePoint での既定のクロール対象ファイルのファイル名拡張子および解析対象ファイルの種類](https://docs.microsoft.com/sharepoint/technical-reference/default-crawled-file-name-extensions-and-parsed-file-types)の詳細を確認してください。詳細については、「[SharePoint Server 2013 で継続的クロールを管理する](https://docs.microsoft.com/SharePoint/search/manage-continuous-crawls)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="31b31-p103">Continuous crawls help keep search results fresh by frequently crawling content in SharePoint sites. Continuous crawls are enabled in SharePoint Online, with crawl frequencies managed by Microsoft. In SharePoint Server 2013, administrators can enable continuous crawls and manage continuous crawl frequencies. Learn more about [default crawled file name extensions and parsed file types in SharePoint](https://docs.microsoft.com/sharepoint/technical-reference/default-crawled-file-name-extensions-and-parsed-file-types). Learn more about [managing continuous crawls](https://docs.microsoft.com/SharePoint/search/manage-continuous-crawls).</span></span>
  
## <a name="deep-links"></a><span data-ttu-id="31b31-118">ディープ リンク</span><span class="sxs-lookup"><span data-stu-id="31b31-118">Deep links</span></span>
<span data-ttu-id="31b31-119"><a name="bkmk_DeepLink"> </a></span><span class="sxs-lookup"><span data-stu-id="31b31-119"></span></span>

<span data-ttu-id="31b31-p104">検索システムは、頻繁にアクセスするメイン ページのサブセクションへの直接リンクを自動的に作成します。これらのリンクは、"ディープ リンク"と呼ばれます。詳細については、「[検索のヒント](https://docs.microsoft.com/sharepoint/dev/general-development/search-in-sharepoint)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="31b31-p104">The search system automatically creates links directly to sub-sections of a main page that is frequently visited. These links are called "deep links". Learn more about the [SharePoint search system](https://docs.microsoft.com/sharepoint/dev/general-development/search-in-sharepoint).</span></span>
  
## <a name="event-based-relevancy"></a><span data-ttu-id="31b31-123">イベント ベースの関連性</span><span class="sxs-lookup"><span data-stu-id="31b31-123">Event-based relevancy</span></span>
<span data-ttu-id="31b31-124"><a name="bkmk_EventBasedRelevancy"> </a></span><span class="sxs-lookup"><span data-stu-id="31b31-124"></span></span>

<span data-ttu-id="31b31-p105">検索システムは、コンテンツの接続方法、検索結果におけるアイテムの出現頻度、ユーザーがどの検索結果をクリックしたかによって検索結果の関連性を判断します。分析コンポーネントがこの情報を追跡および分析し、それを使用して継続的に関連性を改善します。詳細については、「[SharePoint Server 2013 の分析処理の概要](https://docs.microsoft.com/SharePoint/search/overview-of-analytics-processing)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="31b31-p105">The search system determines the relevance of search results in part by how content is connected, how often an item appears in search results, and which search results people click. The analytics component tracks and analyzes this information and uses it to continuously improve relevance. Learn more about [analytics processing](https://docs.microsoft.com/SharePoint/search/overview-of-analytics-processing).</span></span>
  
## <a name="expertise-search"></a><span data-ttu-id="31b31-128">専門知識の検索</span><span class="sxs-lookup"><span data-stu-id="31b31-128">Expertise Search</span></span>
<span data-ttu-id="31b31-129"><a name="bkmk_ExpertiseSearch"> </a></span><span class="sxs-lookup"><span data-stu-id="31b31-129"></span></span>

<span data-ttu-id="31b31-p106">SharePoint では、[人の検索] 機能により、特定のスキルまたは経験を備えた人物を簡単に検索できます。検索結果は、ユーザーがそれぞれの個人サイトで自身について入力したメタデータやユーザーが作成したコンテンツからの情報などの情報に基づいています。詳細については、「[検索ナビゲーション Web パーツの設定を変更する](https://docs.microsoft.com/sharepoint/search/configure-properties-of-the-search-navigation-web-part)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="31b31-p106">In SharePoint, it is easier to find people with specific skills or expertise in the People Search vertical. The search results are based on information such as the metadata users have entered about themselves on their personal sites, and information from the content that they have created. Learn more about [changing search vertical settings](https://docs.microsoft.com/sharepoint/search/configure-properties-of-the-search-navigation-web-part).</span></span>
  
## <a name="graphical-refiners"></a><span data-ttu-id="31b31-133">グラフィカルな絞り込み条件</span><span class="sxs-lookup"><span data-stu-id="31b31-133">Graphical refiners</span></span>
<span data-ttu-id="31b31-134"><a name="bkmk_GraphicalRefiners"> </a></span><span class="sxs-lookup"><span data-stu-id="31b31-134"></span></span>

<span data-ttu-id="31b31-p107">新しいグラフィカルな絞り込み条件は、検索結果をフィルター処理するより視覚的な方法を提供します。詳細については、「[絞り込み Web パーツの設定を変更する](https://support.office.com/article/About-configuring-the-Refinement-Web-Part-7cef67e8-b992-4659-b21a-ba534eea102e)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="31b31-p107">The new graphical refiners provide a more visual way of filtering search results. Learn more about [configuring the Refinement Web Part](https://support.office.com/article/About-configuring-the-Refinement-Web-Part-7cef67e8-b992-4659-b21a-ba534eea102e).</span></span>
  
## <a name="hybrid-search"></a><span data-ttu-id="31b31-137">ハイブリッド検索</span><span class="sxs-lookup"><span data-stu-id="31b31-137">Hybrid search</span></span>
<span data-ttu-id="31b31-138"><a name="bkmk_HybridSearch"> </a></span><span class="sxs-lookup"><span data-stu-id="31b31-138"></span></span>

<span data-ttu-id="31b31-p108">SharePoint のハイブリッド展開では、検索結果のコンテンツは、SharePoint Online サイトと SharePoint Server 2013 社内サイトの両方から取得できます。SharePoint のハイブリッド環境の詳細については、「[SharePoint Server 2013 のハイブリッド](https://docs.microsoft.com/SharePoint/hybrid/hybrid)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="31b31-p108">In a hybrid deployment of SharePoint, search result content can come from both SharePoint Online and SharePoint Server 2013 on-premises sites. To learn more about a hybrid SharePoint environment, see [Hybrid for SharePoint Server 2013](https://docs.microsoft.com/SharePoint/hybrid/hybrid).</span></span>
  
## <a name="manage-search-schema"></a><span data-ttu-id="31b31-141">検索スキーマを管理する</span><span class="sxs-lookup"><span data-stu-id="31b31-141">Manage search schema</span></span>
<span data-ttu-id="31b31-142"><a name="bkmk_manage_search_schema"> </a></span><span class="sxs-lookup"><span data-stu-id="31b31-142"></span></span>

<span data-ttu-id="31b31-p109">SharePoint サイト上でコンテンツを検索すると、検索インデックスに含まれているものが検索されます。検索インデックスは、SharePoint サイト上のコンテンツをクロールすることによって構築され、サイト上のすべてのドキュメントとページからの情報が含まれています。検索スキーマは、クローラーが収集すべきコンテンツとメタデータと、それらにインデックスを付ける方法を決定するのに役立ちます。検索スキーマを変更することによって、カスタマイズした検索エクスペリエンスをユーザーに提供できます。詳細については、「[SharePoint Online で検索スキーマを管理する](https://docs.microsoft.com/sharepoint/manage-search-schema)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="31b31-p109">When people search for content on your SharePoint sites, it's what's in your search index that determines what they'll find. The search index contains information from all documents and pages on your site and is built by crawling the content on your SharePoint site. The search schema helps the crawler decide what content and metadata to pick up and how to index it. By changing the search schema, you can create a customized search experience for your users. Learn more about [managing search schema in SharePoint Online](https://docs.microsoft.com/sharepoint/manage-search-schema).</span></span>
  
## <a name="on-hover-preview"></a><span data-ttu-id="31b31-148">ホバープレビュー</span><span class="sxs-lookup"><span data-stu-id="31b31-148">On-hover preview</span></span>
<span data-ttu-id="31b31-149"><a name="bkmk_Quickpreview"> </a></span><span class="sxs-lookup"><span data-stu-id="31b31-149"></span></span>

<span data-ttu-id="31b31-p110">ユーザーはポインターを検索結果の上に合わせ、結果の右側にあるホバー パネルで、ドキュメントやサイトのコンテンツのプレビューや操作ができます。プレビューには、豊富なメタデータが示され、ドキュメントまたはサイトのメイン セクションへのディープ リンクがあります。詳細については、「[検索のヒント](https://support.office.com/article/Not-getting-the-search-results-you-re-looking-for-in-SharePoint-D80687F7-1010-4E6D-ADD9-584B423289D9)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="31b31-p110">Users can rest the pointer over a search result to preview and interact with the document or site content in the hover panel to the right of the result. The preview shows rich metadata and has deep links to the main sections of the document or site. Learn more [tips for searching](https://support.office.com/article/Not-getting-the-search-results-you-re-looking-for-in-SharePoint-D80687F7-1010-4E6D-ADD9-584B423289D9).</span></span>
  
## <a name="phonetic-name-matching"></a><span data-ttu-id="31b31-153">フリガナ マッチング</span><span class="sxs-lookup"><span data-stu-id="31b31-153">Phonetic name matching</span></span>
<span data-ttu-id="31b31-154"><a name="bkmk_PhoneticNameMatching"> </a></span><span class="sxs-lookup"><span data-stu-id="31b31-154"></span></span>

<span data-ttu-id="31b31-p111">改善されたフリガナ マッチングが、読み方が類似の名前 (John か Jon か) の検索結果を見つけます。詳細については、「[検索先を管理する](https://docs.microsoft.com/sharepoint/manage-result-sources)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="31b31-p111">Improved phonetic name matching finds search results for similar sounding names (is it John or Jon?). Learn more about [managing result sources](https://docs.microsoft.com/sharepoint/manage-result-sources).</span></span>
  
## <a name="query-rulesadd-promoted-results"></a><span data-ttu-id="31b31-157">クエリ ルール — 昇格対象結果の追加</span><span class="sxs-lookup"><span data-stu-id="31b31-157">Query rules—add promoted results</span></span>
<span data-ttu-id="31b31-158"><a name="bkmk_QueryRulesAddpromotedresults"> </a></span><span class="sxs-lookup"><span data-stu-id="31b31-158"></span></span>

<span data-ttu-id="31b31-p112">クエリ ルールでは、条件と相関するアクションを指定します。クエリがクエリ ルールの条件を満たす場合、検索システムはルールに指定されたアクションを実行します。"昇格対象結果の追加" アクションを使うと、検索結果の上位に表示されるように個々の結果を昇格できます。詳細については、「[クエリ ルールを管理する](https://docs.microsoft.com/SharePoint/search/manage-query-rules)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="31b31-p112">In a query rule, specify conditions and correlated actions. When a query meets the conditions in a query rule, the search system performs the actions specified in the rule. The "Add promoted results" action lets you promote individual results so that they appear at the top of search results. Learn more about [managing query rules](https://docs.microsoft.com/SharePoint/search/manage-query-rules).</span></span>
  
## <a name="query-rulesadvanced-actions"></a><span data-ttu-id="31b31-163">クエリ ルール — 高度なアクション</span><span class="sxs-lookup"><span data-stu-id="31b31-163">Query rules—advanced actions</span></span>
<span data-ttu-id="31b31-164"><a name="bkmk_UserRulesAdvancedActions"> </a></span><span class="sxs-lookup"><span data-stu-id="31b31-164"></span></span>

<span data-ttu-id="31b31-p113">クエリ ルールでは、条件および相関するアクションを指定することができます。"結果ブロックの追加" アクションを使うと、検索結果のサブセットをグループとして表示することができます。"クエリの変更によるランク付けされた結果の変更" アクションでは、返される検索結果のランク付けを変更することができます。詳細については、「[クエリ ルールを管理する](https://docs.microsoft.com/SharePoint/search/manage-query-rules)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="31b31-p113">In a query rule, you can specify conditions and correlated actions. The "Add result blocks" action lets you display a subset of the search results as a group. The "Change ranked results by changing the query" action lets you change the ranking of the returned search results. Learn more about [managing query rules](https://docs.microsoft.com/SharePoint/search/manage-query-rules).</span></span>
  
## <a name="query-spelling-correction"></a><span data-ttu-id="31b31-169">クエリのスペル修正</span><span class="sxs-lookup"><span data-stu-id="31b31-169">Query spelling correction</span></span>
<span data-ttu-id="31b31-170"><a name="bkmk_QuerySpellingCorrection"> </a></span><span class="sxs-lookup"><span data-stu-id="31b31-170"></span></span>

<span data-ttu-id="31b31-p114">除外一覧と内包一覧を編集して、どのクエリのときに検索結果ページで代替のクエリ スペルを表示するかを決定します。この機能は通常、"検索語句の候補"と呼ばれています。詳細については、「[検索辞書を管理する](https://docs.microsoft.com/sharepoint/search/manage-query-spelling-correction)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="31b31-p114">Edit exclusions and inclusions lists to decide which queries the search results page should display alternative query spellings for. This feature is often called "Did you mean?". Learn more about [query spelling correction](https://docs.microsoft.com/sharepoint/search/manage-query-spelling-correction).</span></span>
  
## <a name="query-suggestions"></a><span data-ttu-id="31b31-174">クエリ候補</span><span class="sxs-lookup"><span data-stu-id="31b31-174">Query suggestions</span></span>
<span data-ttu-id="31b31-175"><a name="bkmk_Querysuggestions"> </a></span><span class="sxs-lookup"><span data-stu-id="31b31-175"></span></span>

<span data-ttu-id="31b31-p115">クエリ候補は、ユーザーがすでに検索済みの提案されたフレーズです。候補は、ユーザーがクエリを入力すると検索ボックスの下の一覧に表示されます。クエリ候補は自動的に生成され、"常に" 表示する場合はフレーズをシステムに追加できます。また、候補の表示を "オフ" にすることもできます。詳細については、「[クエリ候補の設定を管理する](https://docs.microsoft.com/sharepoint/search/manage-query-suggestions)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="31b31-p115">Query suggestions are suggested phrases that users have already searched for. The suggestions appear in a list below the Search Box as a user types a query. Query suggestions are generated automatically, and phrases can be added to the system as "always" or "never" suggest. Learn more about [managing query suggestions](https://docs.microsoft.com/sharepoint/search/manage-query-suggestions).</span></span>
  
## <a name="ranking-models"></a><span data-ttu-id="31b31-180">ランク付けモデル</span><span class="sxs-lookup"><span data-stu-id="31b31-180">Ranking models</span></span>
<span data-ttu-id="31b31-181"><a name="bkmk_Ranking_Models"> </a></span><span class="sxs-lookup"><span data-stu-id="31b31-181"></span></span>

<span data-ttu-id="31b31-p116">SharePoint では、最も関連性の高い項目が最初に表示されるように、ランク付けモデルを使用して検索結果に値が割り当てられます。ランク付けモデルは、特定の項目のランク スコアを計算するランク付け係数のセットです。SharePoint Online と SharePoint Server 2013 の両方に、カスタマイズせずに有効なランク付けを提供するいくつかのランク付けモデルが付属しています。ただし、検索結果をエンド ユーザーにとってより関連性の高いものにする必要がある場合は、ランク付けモデルをカスタマイズすることができます。ランク付けモデル チューニング アプリを使用すれば、SharePoint Online のお客様はカスタム ランク付けモデルを作成できます。このアプリは、既存のランク付けモデルをコピーして、一連のクエリ結果を評価し、ランク機能を追加または削除することでその重みを調整することによってランク付けモデルを "チューニング" するユーザー インターフェイスを提供します。検索結果のランク付けの詳細については、「[SharePoint Online 検索管理の概要](https://docs.microsoft.com/sharepoint/search/overview-of-search-result-ranking)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="31b31-p116">SharePoint uses ranking models to assign a value to search results so that the most relevant items appear first. A ranking model is a set of ranking factors that calculate the rank score of a particular item. Both SharePoint Online and SharePoint Server 2013 include several ranking models that provide effective rankings without any further customization. However, you can customize your ranking models if you need to make search results even more relevant to your end users. The Ranking Model Tuning App allows SharePoint Online customers to create a custom ranking model. The app provides a user interface to copy an existing ranking model, judge the results for a set of queries, and "tune" it by adding or removing rank features and adjusting the weight of those features. Learn more about [search result ranking](https://docs.microsoft.com/sharepoint/search/overview-of-search-result-ranking).</span></span>
  
## <a name="refiners"></a><span data-ttu-id="31b31-189">Refiners</span><span class="sxs-lookup"><span data-stu-id="31b31-189">Refiners</span></span>
<span data-ttu-id="31b31-190"><a name="bkmk_Refiners"> </a></span><span class="sxs-lookup"><span data-stu-id="31b31-190"></span></span>

<span data-ttu-id="31b31-p117">絞り込み条件は、SharePoint Server 検索結果の上位のドキュメントをユーザーが検索結果をフィルター処理できるグループに分類します。詳細については、「[絞り込み Web パーツの設定を変更する](https://support.office.com/article/About-configuring-the-Refinement-Web-Part-7cef67e8-b992-4659-b21a-ba534eea102e)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="31b31-p117">Refiners categorize the top documents in SharePoint Server search results into groups that let users filter the search results. Learn more about [configuring the Refinement Web Part](https://support.office.com/article/About-configuring-the-Refinement-Web-Part-7cef67e8-b992-4659-b21a-ba534eea102e).</span></span>
  
## <a name="restful-query-apiquery-om"></a><span data-ttu-id="31b31-193">REST 対応のクエリ API/クエリ OM</span><span class="sxs-lookup"><span data-stu-id="31b31-193">RESTful Query API/Query OM</span></span>
<span data-ttu-id="31b31-194"><a name="bkmk_RESTfulQueryAPI"> </a></span><span class="sxs-lookup"><span data-stu-id="31b31-194"></span></span>

<span data-ttu-id="31b31-p118">開発者は、パブリック検索オブジェクト モデルにアクセスする .NET コードを作成できます。これには、検索クエリの送信に加え、検索管理操作が含まれます。サービス側のオブジェクト モデルと対話するには, .NET コードをファーム内の Web サーバーで実行する必要があります。オブジェクト モードのサブセットには、クライアント側オブジェクト モデル (CSOM) を使用してリモート コンピューターからアクセスできます。クライアント側オブジェクト モデル (CSOM) の機能には、REST ベースの Web サービスまたは oData を使用してアクセスできます。これにより、開発者は一般の Web 開発ツールを使用して、クエリを SharePoint Server 2013 ファームに送信できます。</span><span class="sxs-lookup"><span data-stu-id="31b31-p118">Developers can create .NET code to access the public search object model. This includes search administration operations in addition to submitting search queries. To interact with the service side object model, the .NET code must run on a web server in the farm. A sub-set of the object mode can be accessed from a remote computer by using the Client Side Object Model (CSOM). Features of the Client Side Object model (CSOM) can be accessed by using a REST-based web service or oData. This allows developers to submit queries to the SharePoint Server 2013 farm using popular web development tools.</span></span>
  
## <a name="search-results-sorting"></a><span data-ttu-id="31b31-201">検索結果の並べ替え</span><span class="sxs-lookup"><span data-stu-id="31b31-201">Search results sorting</span></span>
<span data-ttu-id="31b31-202"><a name="bkmk_Searchresultssorting"> </a></span><span class="sxs-lookup"><span data-stu-id="31b31-202"></span></span>

<span data-ttu-id="31b31-p119">ユーザーは、関連性、新しさ、社会的距離 (人の名前) などのさまざまな条件で検索結果を並べ替えることができます。詳細については、「[検索結果 Web パーツの設定を変更する](https://support.office.com/article/change-settings-for-the-search-results-web-part-40ff85b3-bc5e-4230-b1dd-f088188e487e)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="31b31-p119">Users can choose to sort search results by different criteria, for example relevance, freshness, and social distance (people names). Learn more about [search results sorting](https://support.office.com/article/change-settings-for-the-search-results-web-part-40ff85b3-bc5e-4230-b1dd-f088188e487e).</span></span>
  
## <a name="this-list-searches"></a><span data-ttu-id="31b31-205">"このリスト" 検索</span><span class="sxs-lookup"><span data-stu-id="31b31-205">"This List" searches</span></span>
<span data-ttu-id="31b31-206"><a name="bkmk_ThisListSearches"> </a></span><span class="sxs-lookup"><span data-stu-id="31b31-206"></span></span>

<span data-ttu-id="31b31-p120">SharePoint Online と SharePoint Server 2013 では、検索対象を制限して、リストまたはライブラリだけで検索を行うことができます。SharePoint Foundation 2013 では、検索が実行されたサイト以下に存在するすべてのリストとライブラリから検索結果が返されます。</span><span class="sxs-lookup"><span data-stu-id="31b31-p120">In SharePoint Online and SharePoint Server 2013, a search can be limited to the list or library where the search is performed. In SharePoint Foundation 2013, a search will return results from all lists and libraries that exist at or below the site where the search is performed.</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="31b31-209">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="31b31-209">Feature Availability</span></span>
<span data-ttu-id="31b31-210"><a name="bkmk_ThisListSearches"> </a></span><span class="sxs-lookup"><span data-stu-id="31b31-210"></span></span>

<span data-ttu-id="31b31-211">Office 365 のプラン、スタンドアロンのオプション、オンプレミス ソリューション全体の機能の可用性を表示するには、「[SharePoint Online サービスの説明](sharepoint-online-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="31b31-211">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [SharePoint Online Service Description](sharepoint-online-service-description.md).</span></span>
  

