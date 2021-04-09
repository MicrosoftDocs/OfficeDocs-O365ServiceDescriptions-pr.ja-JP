---
title: セキュリティとコンプライアンスに関する Microsoft 365 &ガイダンス
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.reviewer: v-trscho
audience: ITPro
ms.topic: reference
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: この記事では、ライセンスのないアクセスによるサービスの中断を回避するために、Microsoft 365 コンプライアンスのライセンス ガイダンスを提供します。
ms.openlocfilehash: 755fc9701a270f7c1f5651643f01c5b1937bf5dc
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652661"
---
# <a name="microsoft-365-licensing-guidance-for-security-amp-compliance"></a>セキュリティコンプライアンスに関する Microsoft 365 ライセンス &amp; ガイダンス

この記事では、テナント レベルのサービスは、テナント内のすべてのユーザー (スタンドアロンまたは &mdash; Office 365 または Microsoft 365 プランの一部として) を購入した場合に、テナント内のすべてのユーザーに対して一部または完全にアクティブ化されるオンライン サービスです。 &mdash; 一部のライセンスのないユーザーは技術的にサービスにアクセスできる場合があります。サービスの恩恵を受ける予定のユーザーにはライセンスが必要です。

> [!NOTE]
> 一部のテナント サービスでは、現在、特定のユーザーにメリットを制限できません。 サービスの利点をライセンスユーザーに限定するための取り組みを行う必要があります。 これにより、ターゲット設定機能が利用可能な場合に、組織の潜在的なサービスの中断を回避できます。

2020 年 4 月 1 日の Microsoft 365 コンプライアンス機能のメリットをユーザーにライセンスするためのオプションを確認するには、詳細な Microsoft 365 コンプライアンス ライセンス比較をダウンロードしてください。 [(PDF)](https://www.microsoft.com/download/details.aspx?id=102403)  | [(Excel)](https://www.microsoft.com/download/details.aspx?id=102427)

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

Azure Active Directory Identity Protection は Azure Active Directory Premium P2 プランの機能で、組織の ID に影響を与える潜在的な脆弱性を検出し、組織の ID に関連する疑わしいアクションを検出するように自動応答を構成し、疑わしいインシデントを調査し、それらを解決するための適切なアクションを実行できます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

SecOps アナリストとセキュリティ 専門家は、機械学習アルゴリズムに基づいてフラグが設定されたユーザーとリスク イベントの統合ビューを利用できます。 エンド ユーザーは、リスクベースの条件付きアクセスを通じて提供される自動保護と、脆弱性に対応して提供されるセキュリティの強化を利用できます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>サービスのメリットをユーザーに提供する権限を提供するライセンスは何ですか?

Enterprise Mobility + Security E5/A5、Microsoft 365 E5/A5、Microsoft 365 E5/A5 Security、Azure Active Directory Premium Plan 2 は、Azure Active Directory Identity Protection のメリットをユーザーに提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニングおよび展開方法

既定では、Azure AD Id Protection 機能はテナント内のすべてのユーザーに対してテナント レベルで有効になっています。 Azure AD ID 保護の詳細については [、「What is Identity Protection」を参照してください。](/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得しているテナント内のユーザーにのみサービスを適用する方法

管理者は、パスワードのリセットADレベルを定義するリスク ポリシーを割り当て、ライセンスユーザーにのみアクセスを許可することで、Azure AD Id Protection のスコープを設定できます。 Azure AD Id Protection の展開の範囲を指定する方法については、「リスク ポリシーを構成して有効にする方法 [」を参照してください](/azure/active-directory/identity-protection/howto-sign-in-risk-policy)。

## <a name="azure-active-directory-identity-governance"></a>Azure Active Directory ID ガバナンス

Azure Active Directory Identity Governance を使用すると、セキュリティと従業員の生産性に対する組織の必要性と、適切なプロセスと可視性をバランスさせることができます。 権利管理、アクセス レビュー、特権 ID 管理、および使用条件ポリシーを使用して、適切なユーザーが適切なリソースに適切にアクセスできます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

Azure Active Directory Identity Governance は、アプリ、グループ、および Microsoft Teams へのアクセスを 1 つのアクセス パッケージで要求しやすくすることで、ユーザーの生産性を向上させます。 ユーザーは、管理者を巻き込む必要なく、承認者として構成できます。 アクセス レビューでは、ユーザーはグループのメンバーシップを確認し、スマートな推奨事項を使用して一定の間隔でアクションを実行できます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>サービスのメリットをユーザーに提供する権限を提供するライセンスは何ですか?

Enterprise Mobility + Security E5/A5、Microsoft 365 E5/A5、Microsoft 365 E5/A5 Security、Azure Active Directory Premium Plan 2 は、Azure Active Directory Identity Governance の恩恵を受ける権限をユーザーに提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニングおよび展開方法

Azure AD ID ガバナンス機能はテナント レベルで有効になっていますが、ユーザーごとに実装されます。 Azure AD ID ガバナンスの詳細については [、「What is Azure AD Identity Governance」を参照してください。](/azure/active-directory/governance/identity-governance-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得しているテナント内のユーザーにのみサービスを適用する方法

管理者は、アクセス パッケージ、アクセス レビュー AD特権 ID 管理をライセンス ユーザーにのみ割り当て、Azure id ガバナンスのスコープを設定できます。 Azure Id ガバナンスの展開を対象範囲AD手順については、以下を参照してください。

- [Azure ADのライセンス要件](/azure/active-directory/governance/entitlement-management-overview#license-requirements)
- [Azure AD レビュー ライセンス要件](/azure/active-directory/governance/access-reviews-overview#license-requirements)
- [特権 ID 管理を使用するライセンス要件](/azure/active-directory/privileged-identity-management/subscription-requirements)

## <a name="microsoft-defender-for-identity"></a>Microsoft Defender for Identity

Microsoft Defender for Identity (旧 Azure Advanced Threat Protection) は、複数の種類の高度な標的型サイバー攻撃やインサイダー脅威からエンタープライズ ハイブリッド環境を保護するのに役立つクラウド サービスです。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

SecOp アナリストとセキュリティ 専門家は、Microsoft Defender for Identity が高度な脅威、侵害された ID、悪意のあるインサイダーアクションを検出して調査する機能を利用できます。 エンド ユーザーは、Microsoft Defender for Identity によってデータを監視することでメリットを得る。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>サービスのメリットをユーザーに提供する権限を提供するライセンスは何ですか?

Enterprise Mobility + Security E5/A5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 Security、Microsoft Defender for Identity for Users は、Microsoft Defender for Identity の恩恵を受ける権利を提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニングおよび展開方法

既定では、Microsoft Defender for Identity 機能はテナント内のすべてのユーザーに対してテナント レベルで有効になっています。 Azure ATP の構成の詳細については、「Create [your Microsoft Defender for Identity instance 」を参照してください](/defender-for-identity/install-step1)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得しているテナント内のユーザーにのみサービスを適用する方法

現在、Microsoft Defender for Identity サービスでは、特定のユーザーに機能を制限する機能はありません。 利益を得る予定のすべてのユーザーにライセンスを取得する必要があります。

## <a name="microsoft-defender-for-office-365"></a>Microsoft Defender for Office 365

Microsoft Defender for Office 365 (Office 365 Advanced Threat Protection) は、フィッシングやゼロデイ マルウェアなどの高度な攻撃から組織を保護するのに役立ちます。 Microsoft Defender for Office 365 は、さまざまなデータからのシグナルを関連付け、潜在的な脅威に対処する方法に関する推奨事項を特定、優先順位付け、および提供することで、アクション可能な分析情報も提供します。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

Microsoft Defender for Office 365 は、フィッシングやゼロデイ マルウェアなどの高度な攻撃からユーザーを保護します。 プラン 1 とプラン 2 で提供されるサービスの完全な一覧については [、「Microsoft Defender for Office 365」を参照してください](/microsoft-365/security/office-365-security/office-365-atp)。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>サービスのメリットをユーザーに提供する権限を提供するライセンスは何ですか? 

Microsoft Defender for Office 365 プラン 1 および 2、Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 セキュリティ、および Microsoft 365 Business Premium は、microsoft Defender for Office 365 のメリットをユーザーに提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニングおよび展開方法

既定では、Microsoft Defender for Office 365 の機能は、テナント内のすべてのユーザーに対してテナント レベルで有効になっています。 ライセンスユーザーの 365 ポリシー Office Microsoft Defender の構成の詳細については [、「Microsoft Defender for Office 365」](/microsoft-365/security/office-365-security/office-365-atp)を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得しているテナント内のユーザーにのみサービスを適用する方法

Microsoft Defender for Office 365 のスコープを設定するには、安全なリンクと安全な添付ファイルの展開ポリシーに従います。

- ライセンスユーザー向けセーフ リンクの構成の詳細については、「Microsoft Defender for microsoft [Defender for Office 365」を参照してください](/microsoft-365/security/office-365-security/atp-safe-links)。

- ライセンスユーザーの安全な添付ファイルの構成の詳細については、「Microsoft Defender for microsoft [Defender for Office 365」を参照してください](/microsoft-365/security/office-365-security/atp-safe-attachments)。

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud App Security (OCAS) は Microsoft Cloud App Security のサブセットであり、機能は Office 365 に制限され、サードパーティのクラウド アプリと IaaS サービスに対する追加のセキュリティは提供されない。

OCAS を使用すると、組織は生産性クラウド アプリとサービスを可視化し、サイバー脅威を特定して対処するための高度な分析を提供し、Office 365 全体でデータを移動 &mdash; する方法を制御できます。

機能を比較するには、「Microsoft Cloud App Security と [365 Cloud App Security](/cloud-app-security/editions-cloud-app-security-o365)Officeの違い」を参照してください。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

OCAS はシャドウ IT を検出し、Office 365 全体で脅威保護を提供し、データにアクセスするアクセス許可を持つアプリを制御できます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>サービスのメリットをユーザーに提供する権限を提供するライセンスは何ですか?

Office 365 E5/A3/A5/G5 は、ユーザーが OCAS の恩恵を受ける権利を提供します。
詳細については [、「Microsoft Cloud App Security Licensing データシート」を参照してください](https://www.aka.ms/mcaslicensing)。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニングおよび展開方法

既定では、OCAS 機能はテナント内のすべてのユーザーに対してテナント レベルで有効になっています。

サービスの構成の詳細については [、「Cloud App Security の基本セットアップ」を参照してください](/cloud-app-security/general-setup)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得しているテナント内のユーザーにのみサービスを適用する方法

管理者は、OCAS 展開の範囲を指定して、特定のアプリへのアクセス方法を適用し、365 Cloud App Security で監視Officeグループを制限できます。 詳細については [、「Scoped deployment」を参照してください](/cloud-app-security/scoped-deployment)。

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) はクラウド アクセス セキュリティ ブローカー (CASB) ソリューションで、組織はクラウド アプリとサービスを可視化し、サイバー脅威を特定して対処するための高度な分析を提供し、データが任意のクラウド アプリ間で移動する方法を制御できます。 &mdash;

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

MCAS はシャドウ IT を検出して評価し、ファースト パーティとサード パーティのクラウド アプリ全体で脅威保護を提供し、ファースト パーティとサード パーティのクラウド アプリ間で情報を保護します。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>サービスのメリットをユーザーに提供する権限を提供するライセンスは何ですか?

MCAS、Enterprise Mobility + Security E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 セキュリティ、Microsoft 365 E5/A5/G5 Compliance、Microsoft 365 Information Protection and Governance は、MCAS の恩恵を受ける権利をユーザーに提供します。

Azure AD P1 には、MCAS の検出機能を利用する権限がユーザーに提供されます。

MCAS の条件付きアクセス アプリ制御機能を利用するには、エンタープライズ モビリティ + セキュリティ E3/A3/G3、Enterprise Mobility + Security E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 セキュリティに含まれる Azure Active Directory P1 のライセンスも必要です。

クライアント側の自動ラベル付けを利用するには、エンタープライズ モビリティ + セキュリティ E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 コンプライアンス、Microsoft 365 Information Protection and Governance に含まれる Azure Information Protection P2 のライセンスが必要です。

> [!NOTE]
> サーバー側の自動ラベル付けには、365 Officeプレミアム ライセンス (または) の情報保護が `MIP_S_CLP2` 必要です `efb0351d-3b08-4503-993d-383af8de41e3` 。 参照については、「ライセンスの [製品名とサービス プラン識別子」を参照してください](/azure/active-directory/enterprise-users/licensing-service-plan-reference)。

詳細については [、「Microsoft Cloud App Security Licensing データシート」を参照してください](https://www.aka.ms/mcaslicensing)。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニングおよび展開方法

既定では、MCAS 機能はテナント内のすべてのユーザーに対してテナント レベルで有効になっています。

ライセンスユーザー向け Microsoft Cloud App Security ポリシーの構成の詳細については、「Microsoft Cloud App Security の概要」 [を参照してください](/cloud-app-security/what-is-cloud-app-security)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得しているテナント内のユーザーにのみサービスを適用する方法

管理者は、サービスで利用可能なスコープ付き展開機能を使用して、MCAS 展開をライセンスユーザーに範囲指定できます。 詳細については [、「Scoped deployment」を参照してください](/cloud-app-security/scoped-deployment)。

## <a name="compliance-manager"></a>コンプライアンス マネージャー

コンプライアンスマネージャーを使用すると、コンプライアンスを簡素化し、リスクを軽減できます。 コンプライアンス マネージャーは、組織が規制、標準、会社のポリシー、または他の必要な制御フレームワークの要件を満たすのに役立ちます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

コンプライアンス マネージャー サービスのユーザーに対する利点は次のとおりです。

- 複雑な規制、標準、会社のポリシー、その他の必要な制御フレームワークを単純な言語に変換する
- 独自のコンプライアンスニーズを満たすために、独自の評価とカスタム評価の膨大なライブラリへのアクセスを提供します
- 規制コントロールを推奨される改善アクションにマップする
- 規制要件を満たすためにソリューションを実装する方法に関するステップバイステップのガイダンスを提供します。
- ユーザーが各アクションにスコアを関連付け、組織のコンプライアンスに最も大きな影響を与えるアクションの優先順位を設定するのに役立ちます

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>サービスのメリットをユーザーに提供する権限を提供するライセンスは何ですか?

E1 および E3/G3 ライセンスをお持ちのお客様は、既定のデータ保護基準評価にのみアクセスできます。 Office 365 E5/A5 および Microsoft 365 E5/A5 ライセンス (コンプライアンス、Info Protection & ガバナンス、電子情報開示と監査 SKU が含まれる) をお持ちのお客様は、データ保護基準、GDPR、NIST 800-53、ISO 27001 の標準評価にアクセスできます。 Office 365 G5 および Microsoft 365 G5 をお持ちのお客様は、データ保護基準、GDPR、NIST 800-53、ISO 27001、およびサイバーセキュリティ成熟度モデル認定 (CMMC) レベル 1 ~ 5 の標準評価にアクセスできます。 カスタム評価機能とプレミアム評価は、Office 365 E5/A5/G5 および Microsoft 365 E5/A5/G5 のお客様のために予約されています。 FedRAMP Moderate、FedRAMP High などのプレミアム評価は、2021 年前半から VL、CSP、WebDirect の間に E5/A5/G5 ライセンスをお持ちのお客様に購入できます。 Microsoft 販売者または Microsoft パートナーに問い合わせ、それぞれ VL チャネルまたは CSP チャネルを通じて購入してください。 WebDirect を使用して購入するには [、「WebDirect」を参照してください](https://aka.ms/ComplianceManager/WebDirect)。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニングおよび展開方法

コンプライアンス マネージャーは、テナントに対して既定でプロビジョニングされます。 管理者は、組織内の管理者以外のユーザーがコンプライアンス マネージャーの使用を開始できるよう、ユーザーのアクセス許可を設定し、役割を割り当てます。 詳細については、「コンプライアンス マネージャーの使用を開始する: ユーザーのアクセス許可を設定し、役割を割り当 [てる」を参照してください](/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles)。

## <a name="microsoft-defender-for-endpoint"></a>Microsoft Defender for Endpoint

Microsoft Defender for Endpoint (旧 Microsoft Defender ATP) は、リスクベースの脆弱性管理と評価を含むエンドポイント セキュリティ ソリューションです。攻撃表面の縮小機能。ビヘイビア ベースおよびクラウドベースの次世代保護。エンドポイントの検出と応答 (EDR)。自動調査と修復。および管理された狩猟サービス。 詳細については [、「Microsoft Defender for Endpoint」](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) ページを参照してください。

### <a name="which-users-benefit-from-the-service"></a>どのユーザーがサービスの恩恵を受けるか。

Windows 10 Enterprise E5、Windows 10 Education A5、Microsoft 365 E5/G5 のライセンスユーザーは、Windows 10 Enterprise E5、Microsoft 365 E5/A5/G5 セキュリティを含み、Microsoft Defender for Endpoint のメリットを利用できます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

SecOps アナリストとセキュリティ 専門家は、Microsoft Defender for Endpoint のエンドポイント セキュリティ機能を活用して、予防保護、侵害後の検出、自動調査、高度な脅威への対応を行います。 エンド ユーザーは、Microsoft Defender for Endpoint によって悪意のあるイベントを監視することでメリットを得る。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニングおよび展開方法

既定では、Microsoft Defender for Endpoint の機能は、テナント内のすべてのユーザーに対してテナント レベルで有効になっています。 展開の詳細については、「展開フェーズ [」を参照してください](/windows/security/threat-protection/microsoft-defender-atp/deployment-phases)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得しているテナント内のユーザーにのみサービスを適用する方法

Microsoft Defender for Endpoint 管理者は、役割ベースのアクセス制御 (RBAC) を使用して、セキュリティ運用チーム内に役割とグループを作成し、Microsoft Defender セキュリティ センターへの適切なアクセスを許可できます。 詳細については、「役割ベースのアクセス [制御を使用してポータル アクセスを管理する」を参照してください](/windows/security/threat-protection/microsoft-defender-atp/rbac)。

## <a name="microsoft-365-data-classification-analytics-overview-content-amp-activity-explorer"></a>Microsoft 365 データ分類分析: 概要コンテンツ &amp; アクティビティ エクスプローラー  

データ分類分析機能は、Microsoft 365 コンプライアンス センターエクスペリエンス内で利用できます。 概要には、デジタル コンテンツの場所と、最も一般的な機密情報の種類とラベルが表示されます。 コンテンツ エクスプローラーは、機密データの量と種類を表示し、ユーザーがラベルまたは機密の種類でフィルター処理して、機密データが格納されている場所の詳細なビューを取得できます。 アクティビティ エクスプローラーには、機密データやラベルに関連するアクティビティ (ラベルのダウングレードや外部共有など) が表示され、コンテンツがリスクにさらされる可能性があります。

アクティビティ エクスプローラーは、エンド ユーザーが使用している機密情報に関連するアクティビティに関する可視性を得る管理者向け単一のウィンドウを提供します。 これらのデータには、ラベル アクティビティ、データ損失防止 (DLP) ログ、自動ラベル付け、エンドポイント DLP などがあります。

コンテンツ エクスプローラーを使用すると、管理者は、サポートされている Microsoft 365 ワークロード内に格納されている機密ドキュメントにインデックスを作成し、保存している機密情報を特定できます。 さらに、コンテンツ エクスプローラーは、機密ラベルと保持ラベルで分類されたドキュメントを識別するのに役立ちます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

情報保護とコンプライアンス管理者は、サービスにアクセスして、これらのログとインデックス付きデータにアクセスして、機密データの保存場所と、このデータに関連付け、エンド ユーザーが実行するアクティビティを把握できます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>サービスのメリットをユーザーに提供する権限を提供するライセンスは何ですか?

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 コンプライアンス、Microsoft 365 E5/A5/G5 Information &amp; Protection Governance、Office 365 E5 のライセンスユーザーは、Microsoft 365 データ分類分析を利用できます。 

Microsoft 365 E3/A3/G3 および Office 365 E3/A3/G3 を使用すると、ユーザーはコンテンツ エクスプローラーのデータ集約のみを利用できます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニングおよび展開方法

既定では、概要コンテンツとアクティビティ エクスプローラーの機能は、テナント内のすべてのユーザーに対してテナント レベルで有効になっています。 ライセンスユーザーのデータ分類分析の構成の詳細については、以下を参照してください。

- **コンテンツ エクスプローラー**: [コンテンツ エクスプローラーの使用を開始する - Microsoft 365 コンプライアンス |Microsoft Docs](/microsoft-365/compliance/data-classification-content-explorer).
- **アクティビティ エクスプローラー**: [アクティビティ エクスプローラーの使用を開始する - Microsoft 365 コンプライアンス |Microsoft Docs](/microsoft-365/compliance/data-classification-activity-explorer).
- **データ分類のリリース ノート**: [データ分類リリース ノート - Microsoft 365 コンプライアンス |Microsoft Docs](/microsoft-365/compliance/data-classification-pub-preview-relnotes).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得しているテナント内のユーザーにのみサービスを適用する方法

この機能は、Microsoft 365 コンプライアンス ポータル内でソリューションを積極的に使用するユーザーの範囲を指定する必要があります。

## <a name="information-protection"></a>情報保護

情報保護は、組織が機密性の高いドキュメントや電子メールを検出、分類、ラベル付け、保護するのに役立ちます。 管理者は、ラベルを自動的に適用するルールと条件を定義したり、ユーザーが手動でラベルを適用したり、2 つの組み合わせを使用したりできます。ユーザーにはラベルの適用に関する推奨事項が表示されます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

ユーザーは、機密ラベルを手動でコンテンツに適用したり、コンテンツを自動的に分類したりすることでメリットを得る。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>サービスのメリットをユーザーに提供する権限を提供するライセンスは何ですか?

Microsoft 365 E5/A5/G5/E3/G3/F1/F3/Business Premium、Enterprise Mobility + Security F3/E3/E5、Office 365 E5/A5/E3/A3/F3、AIP プラン 1、および AIP プラン 2 は、ユーザーが手動の感度ラベル付けによるメリットを得る権利を提供します。

Microsoft 365 E5/A5/G5/E3/G3/F3/Business Premium、Enterprise Mobility + Security F3/E3/E5、AIP プラン 1、および AIP プラン 2 は、Power BI で感度ラベルを適用および表示し、Power BI から Excel、PowerPoint、または PDF にエクスポートするときにデータを保護する権限をユーザーに提供します。 

> [!NOTE]
> Power BI は Microsoft 365 E5/A5/G5 に含まれています。他のすべてのプランでは、Power BI は個別にライセンスを取得する必要があります。

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 コンプライアンス、Microsoft 365 E5/A5/G5 情報保護、ガバナンス、Office 365 E5、Enterprise Mobility + Security E5/A5/G5、および AIP プラン 2 は、自動感知ラベル付けによるメリットをユーザーに提供します。

ライセンス別の特定の権限については、詳細な Microsoft 365 コンプライアンス ライセンス比較を参照してください。 [(PDF)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  | [(Excel)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)機械学習 (トレーニング可能な分類子) に基づく自動分類の権限は含められない。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニングおよび展開方法

既定では、情報保護機能はテナント内のすべてのユーザーに対してテナント レベルで有効になっています。 ライセンスユーザーのポリシーの構成の詳細については、「Azure Rights Management のアクティブ化」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得しているテナント内のユーザーにのみサービスを適用する方法

AIP スキャナー機能を使用する場合を除き、ポリシーを特定のグループに範囲指定したり、ユーザーやレジストリを編集して、ライセンスのないユーザーが分類機能やラベル付け機能を実行したりすることはできません。 AIP 展開の範囲を指定する方法については [、「Azure Information Protection ポリシーの構成」を参照してください](/azure/information-protection/configure-policy)。

AIP スキャナー機能の場合、Microsoft はライセンスを取得していないユーザーにファイル分類、ラベル付け、または保護機能を提供しない。

## <a name="information-governance"></a>情報ガバナンス

情報ガバナンスは、組織がデータの検出、分類、ラベル付け、管理を通じてリスクを管理するのに役立ちます。 情報ガバナンスを使用すると、組織はビジネス要件と規制要件を満たすだけでなく、Microsoft 365 およびサード パーティのデータ全体で保持および削除機能を提供することで攻撃の表面を減らします。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

ユーザーは、特定のポリシーと規制を維持するために保持目的でデータを分類できるメリットがあります。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>サービスのメリットをユーザーに提供する権限を提供するライセンスは何ですか?

Microsoft 365 F3/Business Premium、Office 365 E1/A1/F3、スタンドアロン Exchange プランは、メールボックス データにレコード以外の保持ラベルを手動で適用するメリットをユーザーに提供します。

Microsoft 365 F3/F1/Business Premium、Office 365 E1/A1/F3、スタンドアロン SharePoint プランは、SharePoint または OneDrive のファイルにレコード以外の保持ラベルを手動で適用するメリットをユーザーに提供します。 

Microsoft 365 E5/A5/E3/A3/Business Premium、Office 365 E5/A5/G5/E3/A3、Exchange プラン 2、および Exchange Online Archiving は、基本的な組織全体または場所全体のメールボックス保持ポリシーの恩恵を受ける権限をユーザーに提供し、メールボックス データにレコード以外の保持ラベルを手動で適用する権限をユーザーに提供します。

Microsoft 365 E5/A5/G5/E3/A3、Office 365 E5/A5/G5/E3/A3、および SharePoint プラン 2 は、基本的な SharePoint または OneDrive 保持ポリシーの恩恵を受ける権利をユーザーに提供し、SharePoint または OneDrive のファイルにレコード以外の保持ラベルを手動で適用する権限をユーザーに提供します。

Microsoft 365 E5/A5/G5/E3/A3 および Office 365 E5/A5/G5/E3/A3 は、Teams アイテム保持ポリシーの恩恵を受ける権限をユーザーに提供します。

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 コンプライアンス、Microsoft 365 Information Protection and Governance E5/A5/G5、 Office 365 E5/A5 は、ユーザーが保持ラベルまたはポリシーを自動的に適用し、既定の保持ラベルまたはポリシーを適用し、カスタム イベントに基づいて保持ラベルの保持期間を開始し、ラベルの保持期間の最後に手動の廃棄レビューをトリガーし、ネイティブ データ コネクタを介してサードパーティデータをインポートし、ファイルを宣言し、ラベル付きコンテンツを検出し、ラベル付けアクティビティを監視する権限をユーザーに提供します。

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 コンプライアンス、Microsoft 365 E5/A5/G5 Information Protection、ガバナンスは、トレーニング可能な分類子に基づいて保持ラベルを自動的に適用するメリットをユーザーに提供します。

ライセンス別の特定の権限については、詳細な Microsoft 365 コンプライアンス ライセンス比較を参照してください。 [(PDF)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  | [(Excel)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニングおよび展開方法

既定では、情報ガバナンス機能はテナント内のすべてのユーザーに対してテナント レベルで有効になっています。 ライセンスユーザーに対して自動ラベル付けとポリシーを適用するための情報ガバナンスの構成の詳細については [、「Microsoft Information Governance in Microsoft 365」を参照してください](/microsoft-365/compliance/manage-information-governance)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得しているテナント内のユーザーにのみサービスを適用する方法

情報ガバナンス機能は、特定の場所 (チーム サイト、グループ サイトなど) のライセンスユーザーに適用できます。 ライセンスユーザーに対して自動ラベル付けとポリシーを適用するための情報ガバナンスの構成の詳細については [、「Microsoft Information Governance in Microsoft 365」を参照してください](/microsoft-365/compliance/manage-information-governance)。

## <a name="records-management"></a>レコード管理

レコード管理は、Microsoft 365 およびサード パーティのデータ全体で削除機能を検出、分類、ラベル付け、保持、および保護可能な削除機能を通じて、組織がビジネスおよび規制の記録保持義務を満たすのに役立ちます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>サービスのメリットをユーザーに提供する権限を提供するライセンスは何ですか?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 コンプライアンス、Microsoft 365 Information Protection and Governance E5/A5/G5、および Office 365 E5/A5/G5 は、レコードまたは規制レコードとしてアイテムを宣言し、保持ラベルまたはレコード ラベルを自動的に適用し、廃棄審査プロセスを実行する (トレーニング可能な分類子に基づいて保持ラベルを自動的に適用しない) など、レコード管理のメリットをユーザーに提供します。

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 コンプライアンス、および Microsoft 365 Information Protection and Governance は、トレーニング可能な分類子に基づいて保持ラベルまたはレコード ラベルを自動的に適用するメリットをユーザーに提供します。

ライセンス別の特定の権限については、詳細な Microsoft 365 コンプライアンス ライセンス比較を参照してください。 [(PDF)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  | [(Excel)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

ユーザーは、コンテンツをレコードとして宣言し、ポリシーの定義と宣言から延期可能な廃棄までの完全なレコード プロセスを管理できる利点があります。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニングおよび展開方法

既定では、レコード管理機能はテナント内のすべてのユーザーに対してテナント レベルで有効になっています。 ライセンスユーザーに適用するレコード管理の構成の詳細については [、「Microsoft 365](/microsoft-365/compliance/records-management)のレコード管理について」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得しているテナント内のユーザーにのみサービスを適用する方法

レコード管理機能は、特定の場所 (チーム サイト、グループ サイトなど) のライセンスユーザーに適用できます。 ライセンスユーザーに適用するレコード管理の構成の詳細については [、「Microsoft 365](/microsoft-365/compliance/records-management)のレコード管理について」を参照してください。

## <a name="data-connectors"></a>データ コネクタ 

Microsoft は、Microsoft 365 コンプライアンス センターで構成できるサード パーティ製のデータ コネクタを提供します。 Microsoft が提供するデータ コネクタの一覧については、「サード パーティ製データ コネクタ」 [の表を参照](/microsoft-365/compliance/archiving-third-party-data#third-party-data-connectors) してください。 この表では、Microsoft 365 でデータをインポートおよびアーカイブした後にサード パーティのデータに適用できるコンプライアンス ソリューションの概要と、各コネクタのステップ バイ ステップの手順にリンクします。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

Microsoft 365 でデータ コネクタを使用してサード パーティ製のデータをインポートおよびアーカイブする主な利点は、インポート後にさまざまな Microsoft 365 コンプライアンス ソリューションをデータに適用できる点です。 これにより、組織の Microsoft 以外のデータが、組織に影響を与える規制と標準に準拠しているのを確認できます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>サービスのメリットをユーザーに提供する権限を提供するライセンスは何ですか?

次のライセンスは、ユーザーがデータ コネクタの恩恵を受ける権限を提供します。

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 Info Protection &amp; Governance
- Microsoft 365 E5/A5/G5 コンプライアンス
- Microsoft 365 E5/A5/G5 Insider リスク管理
- Microsoft 365 E5/A5/G5 電子情報開示と監査
- Office 365 E5/A5/G5

Microsoft パートナーによって提供される Microsoft 365 セキュリティ コンプライアンス センターのデータ コネクタの場合、これらのコネクタを展開する前に、組織はパートナーとのビジネス関係を必要とします &amp; 。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニングおよび展開方法

コネクタは、セキュリティ コンプライアンス センターとコネクタ &amp; カタログを使用して構成されます。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得しているテナント内のユーザーにのみサービスを適用する方法

データ コネクタ サービスは、テナント レベルの値です。 このサービスの恩恵を受けるユーザーは、ライセンスを取得する必要があります。

## <a name="microsoft-graph-apis-for-teams-data-loss-prevention-dlp"></a>Microsoft Graph API for Teams データ損失防止 (DLP)

今年の初めに、Teams のメッセージに関する [Microsoft Graph 変更通知 API のパブリック プレビューを発表しました](https://go.microsoft.com/fwlink/?linkid=2143888)。 この API を使用すると、開発者は Microsoft Teams のメッセージをほぼリアルタイムで聞き取り、顧客と ISV の両方に対して DLP シナリオの実装を有効にできるアプリを構築できます。 さらに、Microsoft Graph Patch API では、Teams メッセージに DLP アクションを適用できます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

[データ損失防止 (DLP)](/microsoft-365/compliance/dlp-microsoft-teams) 機能は、特に組織がリモート作業に移行する中で、Microsoft Teams で広く使用されています。 組織に DLP がある場合は、Microsoft Teams チャネルまたはチャット セッションで機密情報を共有するユーザーを防止するポリシーを定義できます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>サービスのメリットをユーザーに提供する権限を提供するライセンスは何ですか?

Teams チャットで DLP 保護のサポートを受け取るには、次のいずれかのライセンスが必要です。

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 コンプライアンス
- Microsoft 365 E5/A5/G5 情報保護とガバナンス
- Office 365 E5/A5/G5 

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニングおよび展開方法

API アクセスはテナント レベルで構成されます。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得しているテナント内のユーザーにのみサービスを適用する方法

Microsoft Graph API for Teams DLP はテナント レベルの値です。 このサービスの恩恵を受けるユーザーは、ライセンスを取得する必要があります。

## <a name="ediscovery"></a>電子情報開示

電子情報開示は、Microsoft 365 システムからエクスポートする前に、調査または訴訟に関連するコンテンツを特定、収集、保存、削減、および確認するための、企業内の IT 部門および法務部門向け調査および電子情報開示ソリューションを提供します。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

ユーザーは、ユーザーがケースのデータ 保管担当者 (ドキュメントまたは電子ファイルの管理制御を持つユーザー) として選択されている場合、高度な電子情報開示のメリットを利用できます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>サービスのメリットをユーザーに提供する権限を提供するライセンスは何ですか?

Microsoft 365 E5/A5/E3/A3/G3、Office 365 E5/A5/G5/E3/A3/G3 は、コア電子情報開示の恩恵を受ける権利をユーザーに提供します。

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 コンプライアンス、Microsoft 365 E5/A5/G5 電子情報開示と監査、および Office 365 E5/A5/G5 は、高度な電子情報開示の恩恵を受ける権利をユーザーに提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニングおよび展開方法

既定では、管理者がセキュリティ コンプライアンス センターで電子情報開示のアクセス許可を割り当てると、テナント内のすべてのユーザーのテナント レベルで高度な電子情報開示機能が &amp; 有効になります。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得しているテナント内のユーザーにのみサービスを適用する方法

「Advanced [eDiscovery](/microsoft-365/compliance/add-custodians-to-case)ケースへの保管担当者の追加」の説明に従って、電子情報開示管理者は、Advanced eDiscovery の組み込みのカストディアン管理ツールを使用して、特定のユーザーをケースのデータ 保管担当者として選択できます。

## <a name="office-365-customer-key"></a>Office 365 カスタマー キー

顧客キーを使用すると、組織の暗号化キーを制御し、Office 365 を構成して、Microsoft データ センターで保存されているデータを暗号化します。 つまり、顧客キーを使用すると、独自のキーを使用して、自分に属する暗号化の層を追加できます。 保存されているデータには、SharePoint Online および OneDrive for Business 内のメールボックスおよびファイルに格納されている Exchange Online および Skype for Business のデータが含まれます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

ユーザーは、自分の組織によって提供、制御、管理される暗号化キーを使用して、保存中のデータをアプリケーション層で暗号化することで、顧客キーの恩恵を受ける。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>サービスのメリットをユーザーに提供する権限を提供するライセンスは何ですか?

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 コンプライアンス、Microsoft 365 E5/A5/G5 情報保護とガバナンス、および Office 365 E5/A5/G5 は、ユーザーが顧客キーの恩恵を受ける権利を提供します。 カスタマー キーの利点をフルに利用するには、Azure Key Vault のサブスクリプションも必要です。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニングおよび展開方法

Office 365 カスタマー キー暗号化キーは、Exchange Online および Skype for Business メールボックス、および SharePoint Online、OneDrive for Business、Teams ファイルに格納されているすべてのデータに対して有効にできます。 365 カスタマー Officeの詳細については、「Service Encryption with Customer [Key」を参照してください](/microsoft-365/compliance/customer-key-overview)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得しているテナント内のユーザーにのみサービスを適用する方法

Exchange Online および Skype for Business の場合、メールボックスは顧客キーを使用して暗号化できます。 顧客キーを 365 に使用するには、Azure をOfficeがあります。 必要な Azure [リソースを](/microsoft-365/compliance/customer-key-set-up) 作成および構成するために必要な手順と、365 で顧客キーを設定するための手順については、「顧客キーの設定」Office を参照してください。 Azure セットアップが完了したら、組織のメールボックスとファイルに割り当てるキーとポリシーを決定します。 ポリシーを割り当てないメールボックスとファイルは、Microsoft によって制御および管理される暗号化ポリシーを使用します。 顧客キーの詳細、または一般的な概要については、「顧客キーを使用した [サービス暗号化」を参照してください](/microsoft-365/compliance/customer-key-overview)。

## <a name="office-365-customer-lockbox"></a>Office 365 カスタマー ロックボックス

顧客ロックボックスは、サービス操作に対して明示的なアクセス許可を与える機能を顧客に提供することで、追加の制御層を提供します。 顧客ロックボックスは、明示的なデータ アクセス承認のための手順が実施されているという実証によって、組織が HIPAA や FedRAMP などの特定のコンプライアンス義務を果たすのに役立つ場合があります。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

カスタマー ロックボックスを使用すると、Microsoft の誰も顧客コンテンツにアクセスして、顧客の明示的な承認なしにサービス操作を実行できます。 顧客ロックボックスは、コンテンツにアクセスする要求の承認ワークフローに顧客を取り込む。 Microsoft のエンジニアがサポート プロセス中に、お客様から報告された問題のトラブルシューティングと修正を行う場合があります。 ほとんどの場合、Microsoft がサービスに対して提供している広範な利用統計情報とデバッグ ツールによって問題が修正されます。 ただし、根本的な原因を特定して問題を解決するために、Microsoft のエンジニアが顧客コンテンツにアクセスする必要がある場合があります。 カスタマー ロックボックスでは、承認ワークフローの最終ステップとして、エンジニアが顧客にアクセス要求を行う必要があります。 これにより、組織はこれらの要求を承認または拒否できます。これにより、Microsoft エンジニアが組織のエンド ユーザー データにアクセスできるかどうかを直接制御できます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>サービスのメリットをユーザーに提供する権限を提供するライセンスは何ですか?

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 コンプライアンス、および Microsoft 365 E5/A5/G5 Insider Risk Management は、ユーザーがカスタマー ロックボックスの恩恵を受ける権利を提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニングおよび展開方法

管理者は、Microsoft 365 管理センターで顧客ロックボックスを有効にできます。 詳細については、「Customer [Lockbox in Office 365」を参照してください](/microsoft-365/compliance/customer-lockbox-requests)。 Customer Lockbox が有効になっている場合、Microsoft は、コンテンツにアクセスする前に組織の承認を得る必要があります。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得しているテナント内のユーザーにのみサービスを適用する方法

現時点では、Customer Lockbox サービスを特定のユーザーに限定する必要があります。 利益を得る予定のすべてのユーザーにライセンスを取得する必要があります。

## <a name="privileged-access-management-in-office-365"></a>Office 365 での特権アクセス管理

[特権アクセス管理 (PAM) は](/microsoft-365/compliance/privileged-access-management-configuration) 、365 の特権管理者タスクに対する詳細なアクセスOfficeします。 PAM を有効にした後、管理者特権のタスクと特権タスクを完了するには、ユーザーは、高度な範囲と時間にバインドされた承認ワークフローを通じて、Just-in-time アクセスを要求する必要があります。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

PAM を有効にすると、組織は永続的な特権をゼロで操作できます。 ユーザーは、データへの完全なアクセスを提供する永続的な管理アクセスから生じる脆弱性に対する防御層の追加の恩恵を受ける。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>サービスのメリットをユーザーに提供する権限を提供するライセンスは何ですか? 

Office 365 E5/A5、Microsoft 365 E5/A5、Microsoft 365 E5/A5 コンプライアンス、および Microsoft 365 E5/A5 Information Protection and Governance は、PAM の恩恵を受ける権利をユーザーに提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニングおよび展開方法

既定では、PAM 機能はテナント内のすべてのユーザーに対してテナント レベルで有効になっています。 PAM ポリシーの構成の詳細については、「特権アクセス管理の開始 [」を参照してください](/microsoft-365/compliance/privileged-access-management-configuration)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得しているテナント内のユーザーにのみサービスを適用する方法

顧客は、承認者グループとアクセス ポリシーを通じて、ユーザー単位で PAM を管理できます。このポリシーは、ライセンスユーザーに適用できます。 詳細については [、「Privileged access management in Office 365」を参照してください](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751)。

## <a name="double-key-encryption-for-microsoft-365"></a>Microsoft 365 のダブル キー暗号化 

Microsoft 365 のダブル キー暗号化を使用すると、機密性の高いデータを保護して、特別な要件を満たして暗号化キーを完全に制御できます。 ダブル キー暗号化では、2 つのキーを使用してデータを保護します。コントロール内の 1 つのキーと、Microsoft Azure によってセキュリティで保護された 2 番目のキー。 データを表示するには、両方のキーにアクセスできる必要があります。 Microsoft は 1 つのキーにしかアクセスできないので、キーとデータは Microsoft では使用できなくなったので、データのプライバシーとセキュリティを完全に制御できます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

ユーザーは、暗号化されたデータをクラウドに移行することで、二重キー暗号化の恩恵を受けるので、キーがユーザーの制御に残っている限り、サードパーティのアクセスを妨げる。 ユーザーは、他の感度ラベルで保護されたコンテンツと同様に、Double Key Encrypted コンテンツを保護および使用できます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>サービスのメリットをユーザーに提供する権限を提供するライセンスは何ですか?

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 コンプライアンス、Microsoft 365 E5/A5/G5 情報保護とガバナンス、および Office 365 E5/A5/G5 は、ユーザーがダブル キー暗号化の恩恵を受ける権利を提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニングおよび展開方法

ダブル キー暗号化は、Windows 用のデスクトップ Microsoft Officeをサポートします。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得しているテナント内のユーザーにのみサービスを適用する方法

ライセンスユーザーの Office 365 および/または Microsoft 365 組織内のデータに暗号化キーを割り当てるには、ダブル キー暗号化の展開手順に従います。

## <a name="office-365-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Office、SharePoint Online、OneDrive for Business の 365 データ損失防止

Exchange Online、SharePoint Online、OneDrive for Business の Office 365 データ損失防止 (DLP) を使用すると、組織は電子メールやファイル (Microsoft Teams ファイル リポジトリに保存されているファイルを含む) 全体の機密情報を識別、監視、および自動的に保護できます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

ユーザーは、組織の DLP ポリシーで構成されている電子メールとファイルが機密情報の検査を受ける際に、Exchange Online、SharePoint Online、OneDrive for Business の DLP を利用できます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>サービスのメリットをユーザーに提供する権限を提供するライセンスは何ですか?

Microsoft 365 E3/A3/Business Premium、Office 365 E3/A3、および Office 365 データ損失防止は、Exchange Online、SharePoint Online、および OneDrive for Business の Office 365 DLP の恩恵を受ける権限をユーザーに提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニングおよび展開方法

既定では、Exchange Online の電子メール、SharePoint サイト、および OneDrive アカウントは、テナント内のすべてのユーザーに対してこれらの DLP 機能の有効な場所 *(ワークロード)* です。 DLP ポリシーの使用の詳細については、「データ損失防止の [概要」を参照してください](/microsoft-365/compliance/data-loss-prevention-policies)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得しているテナント内のユーザーにのみサービスを適用する方法

管理者は、セキュリティ コンプライアンス センターの [データ損失防止の場所] の下で、場所 (ワークロード)、組み込みユーザー、および除外されたユーザー &amp; **を**  >  **カスタマイズできます**。

## <a name="communication-data-loss-prevention-for-teams"></a>Teams の通信データ損失防止

Teams の通信 DLP を使用すると、組織は、財務情報、個人識別情報、健康関連情報、その他の機密情報などの機密情報を含むチャットやチャネル メッセージをブロックできます。

### <a name="which-users-benefit-from-the-service"></a>どのユーザーがサービスの恩恵を受けるか。

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 のライセンスを持つユーザーは、Teams の通信 DLP を利用できます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

送信者は、組織の DLP ポリシーで構成されている機密情報について、送信チャットおよびチャネル メッセージで機密情報を検査することでメリットを得る。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニングおよび展開方法

既定では、Teams チャットメッセージとチャネル メッセージは、テナント内のすべてのユーザーに対して有効な場所 *(ワークロード)* です。 DLP ポリシーの使用の詳細については、「データ損失防止の [概要」を参照してください](/office365/securitycompliance/data-loss-prevention-policies)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得しているテナント内のユーザーにのみサービスを適用する方法

管理者は、セキュリティ コンプライアンス センターの [データ損失防止の場所] の下で、場所 (ワークロード)、組み込みユーザー、および除外されたユーザー &amp; **を**  >  **カスタマイズできます**。

## <a name="information-barriers"></a>情報バリア

情報バリアは、ユーザーまたはグループが相互に通信するのを防ぐために、管理者が構成できるポリシーです。 これは、たとえば、ある部署が他の部署と共有すべきではない情報を処理している場合や、グループが外部の連絡先との通信を妨げる必要がある場合に役立ちます。 情報バリア ポリシーは、参照と検出も防止します。 つまり、通信しない相手と通信しようとすると、そのユーザーがユーザー選択リストに表示されないという意味です。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

ユーザーは、他のユーザーとの通信が制限されている場合に、情報バリアの高度なコンプライアンス機能を利用できます。 情報バリア ポリシーを定義して、特定のセグメントのユーザーがそれぞれのセグメントと通信したり、特定のセグメントが特定のセグメントとのみ通信したりするために定義できます。 情報バリア ポリシーの定義の詳細については、「情報バリア ポリシーの [定義」を参照してください](/microsoft-365/compliance/information-barriers-policies)。 2 つのグループが相互に通信できないシナリオでは、両方のグループのユーザーがサービスのメリットを得るライセンスを必要とします (以下の例を参照)。<br><br>

| シナリオ | ライセンスが必要なユーザー |
|:------|:------|
| 2 つのグループ (グループ 1 とグループ 2) は相互に通信できません (つまり、グループ 1 のユーザーはグループ 2 ユーザーとの通信を制限され、グループ 2 ユーザーはグループ &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 1 ユーザーとの通信を制限されます)。 | グループ 1 とグループ &nbsp; &nbsp; 2 の両方のユーザー |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>サービスのメリットをユーザーに提供する権限を提供するライセンスは何ですか?

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 コンプライアンス、Microsoft 365 E5/A5/G5 Insider Risk Management、および Office 365 E5/A5/G5 は、情報バリアの恩恵を受ける権利をユーザーに提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニングおよび展開方法

管理者は、セキュリティ コンプライアンス センターで PowerShell コマンドレットを使用して情報バリア ポリシーを &amp; 作成および管理します。 情報バリア ポリシーを作成するには、管理者に Microsoft 365 Enterprise Global Administrator、Office 365 グローバル管理者、またはコンプライアンス管理者の役割を割り当てる必要があります。 既定では、これらのポリシーはテナント内のすべてのユーザーに適用されます。 情報バリアの詳細については [、「Microsoft Teams の情報バリア」を参照してください](/MicrosoftTeams/information-barriers-in-teams)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得しているテナント内のユーザーにのみサービスを適用する方法

管理者は、セキュリティ コンプライアンス センターの場所 (ワークロード)、含まれるユーザー、除外されたユーザー &amp; をカスタマイズできます。 たとえば、すべてのユーザーが Office 365 E3 のライセンスを取得し、Office 365 Advanced Compliance/E5 のライセンスを取得しない場合、組織の情報バリア ポリシーを作成する必要がなされません。 詳細については、[Microsoft Teams における情報バリア](/MicrosoftTeams/information-barriers-in-teams)に関するページを参照してください。

## <a name="office-365-message-encryption"></a>Office 365 Message Encryption

Office 365 Message Encryption (OME) は、Azure Rights Management (Azure RMS) で構築され、宛先のメール アドレス (Gmail、Yahoo! Mail、Outlook.com など) に関係なく、暗号化された電子メールを組織内外の宛先に送信できるようにするサービスです。

暗号化メッセージを表示するために、受信者は 1 回限りのパスコードを取得するか、Microsoft アカウントでサインインするか、Office 365 に関連付けられている職場または学校のアカウントでサインインできます。 受信者は暗号化された返事を送信することもできます。 暗号化されたメッセージを表示したり、暗号化された返信を送信したりするには、サブスクリプションは必要ない。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

メッセージ送信者は、365 Message Encryption によって提供される機密性の高いOffice制御を利用できます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>サービスのメリットをユーザーに提供する権限を提供するライセンスは何ですか?

Microsoft 365 E3/A3/G3、Office 365 E3/A3/G3、Azure Information Protection Plan 1 は、ユーザーが Office 365 メッセージ暗号化を利用する権限を提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニングおよび展開方法

管理者は、[メール フロールール] Office Exchange 管理センターで 365 メッセージ暗号化ポリシーを作成および  >  **管理します**。 既定では、これらのルールはテナント内のすべてのユーザーに適用されます。 365 Message Encryption の新しい機能Office詳細については、「新しいメッセージ暗号化機能をセットアップする」 [を参照してください](/office365/securitycompliance/set-up-new-message-encryption-capabilities)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得しているテナント内のユーザーにのみサービスを適用する方法

管理者は、365 メッセージ暗号化のメール フロー ルールOfficeライセンスユーザーにのみ適用する必要があります。 メール フロー ルールの定義の詳細については、「メール フロー ルールを定義して電子メール メッセージを暗号化 [する」を参照してください](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)。

## <a name="office-365-advanced-message-encryption"></a>Office 365 Advanced Message Encryption

Office 365 Advanced Message Encryption は、外部受信者に対するより柔軟な制御と暗号化された電子メールへのアクセスを必要とするコンプライアンスの義務を満たすのに役立ちます。 Advanced Message Encryption を使用すると、管理者は機密情報の種類 (個人識別情報、財務または正常性の識別など) を検出できる自動ポリシーを使用して組織外で共有される機密メールを制御したり、カスタムメール テンプレートを適用したり、セキュリティで保護された Web ポータルを通じて暗号化されたメールへのアクセスを期限切れにしたりすることで、キーワードを使用して保護を強化できます。 さらに、管理者は、セキュリティで保護された Web ポータルを介して外部からアクセスされる暗号化された電子メールを、いつでも取り外して制御できます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

メッセージ送信者は、高度なメッセージ暗号化によって提供される機密性の高い電子メールに対する追加の制御の恩恵を受ける。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>サービスのメリットをユーザーに提供する権限を提供するライセンスは何ですか?

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 コンプライアンス、Microsoft 365 E5/A5/G5 Information Protection and Governance は、高度なメッセージ暗号化のメリットをユーザーに提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニングおよび展開方法

管理者は、[メール フロールール] の下の Exchange 管理センターで高度なメッセージ暗号化 **ポリシーを作成および**  >  **管理します**。 既定では、これらのルールはテナント内のすべてのユーザーに適用されます。 新しいメッセージ暗号化機能の設定の詳細については [、「365](/office365/securitycompliance/set-up-new-message-encryption-capabilities)Message Encryption の新しい機能Officeを参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得しているテナント内のユーザーにのみサービスを適用する方法

管理者は、高度なメッセージ暗号化のメール フロー ルールをライセンスユーザーにのみ適用する必要があります。 メール フロー ルールの定義の詳細については、「Define mail flow rules to encrypt email messages in Office [365」を参照してください](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)。

## <a name="communication-compliance"></a>通信コンプライアンス

Microsoft 365 の通信コンプライアンスは、組織内の不適切なメッセージの検出、キャプチャ、修復アクションの実行を支援することで、通信リスクを最小限に抑えるのに役立ちます。 組織内の内部および外部の電子メール、Microsoft Teams、またはサード パーティの通信をキャプチャする特定のポリシーを定義できます。 レビュー担当者は適切な修復アクションを実行して、組織のメッセージ標準に準拠している必要があります。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

コンプライアンス スペシャリストは、コミュニケーション コンプライアンス ポリシーによって組織の通信を監視することで、サービスの恩恵を受ける。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>サービスのメリットをユーザーに提供する権限を提供するライセンスは何ですか?

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 コンプライアンス、Microsoft 365 E5/A5/G5 Insider Risk Management は、通信コンプライアンスの恩恵を受ける権利をユーザーに提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニングおよび展開方法

管理者およびコンプライアンス スペシャリストは、Microsoft 365 コンプライアンス センターに通信コンプライアンス ポリシーを作成します。 これらのポリシーは、組織内で確認対象となる通信とユーザーを定義し、通信が満たす必要があるカスタム条件を定義し、レビューを実行するユーザーを指定します。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得しているテナント内のユーザーにのみサービスを適用する方法

管理者は、通信コンプライアンス ポリシーに含める特定のユーザーまたはグループを選択します。 グループを選択すると、グループ内の特定のユーザーを選択して、通信コンプライアンス ポリシーから除外できます。 通信コンプライアンス ポリシーの詳細については [、「Microsoft 365](/microsoft-365/compliance/communication-compliance-configure)での通信コンプライアンスの概要」を参照してください。

## <a name="insider-risk-management"></a>インサイダー リスク管理

Insider リスク管理は Microsoft 365 のソリューションであり、組織内の危険なアクティビティを検出、調査、および実行することで内部リスクを最小限に抑えるのに役立ちます。

カスタム ポリシーを使用すると、必要に応じて、Microsoft Advanced 電子情報開示へのケースのエスカレートなど、組織内の悪意のある危険なアクティビティを検出してアクションを実行できます。 組織内のリスク アナリストは、適切なアクションを迅速に実行して、ユーザーが組織のコンプライアンス基準に準拠している必要があります。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

ユーザーは、自分のアクティビティにリスクを監視することでメリットを得る。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>サービスのメリットをユーザーに提供する権限を提供するライセンスは何ですか?

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 コンプライアンス、Microsoft 365 E5/A5/G5 Insider Risk Management は、Insider リスク管理の恩恵を受ける権限をユーザーに提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニングおよび展開方法

Insider リスク管理ポリシーは、Microsoft 365 コンプライアンス センターで作成し、ユーザーに割り当てる必要があります。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得しているテナント内のユーザーにのみサービスを適用する方法

Microsoft 365 コンプライアンス センターでポリシーを作成する場合は、[ユーザーとグループの選択] ページで、[ユーザーまたはグループの選択] を選択してライセンスユーザーのみを選択するか、すべてのユーザーがライセンスを取得している場合は、[すべてのユーザーとメールが有効なグループ] チェック ボックスをオンにできます。  詳細については、「Insider [リスク管理の使用を開始する」を参照してください](/microsoft-365/compliance/insider-risk-management-configure)。

## <a name="conditional-access-policies"></a>条件付きアクセス ポリシー

条件付きアクセスは、Azure Active Directory がシグナルをまとめ、決定を下し、組織のポリシーを適用するために使用するツールです。 条件付きアクセスは、ID 駆動型の制御の中心にあります。 条件付きアクセス ポリシーは、最も簡単に言うと if-then ステートメントです。 ユーザーがリソースにアクセスする場合は、アクションを完了する必要があります。 例: 給与計算マネージャーが給与計算アプリケーションにアクセスする場合は、多要素認証を実行してアクセスする必要があります。

### <a name="which-users-benefit-from-the-service"></a>どのユーザーがサービスの恩恵を受けるか。

Enterprise Mobility + Security E3/A3、Microsoft 365 F3/E3/A3/Business Premium、Azure Active Directory Premium Plan 1 のライセンスユーザーは、条件付きアクセス ポリシーを利用できます。 Enterprise Mobility + Security E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft E5/G5 Security、Azure Active Directory Premium Plan 2 のライセンスユーザーは、Identity Protection (リスクベースの条件付きアクセス ポリシー) を利用できます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

セキュリティ運用アナリストとセキュリティ 専門家は、組織のポリシーをユーザーに適用し、企業コンテンツへのアクセスを許可する前に、特定の条件を満たす必要があります。 エンド ユーザーは、組織の資産を保護しながら、いつでもどこでも自分の作業にアクセスできるメリットがあります。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニングおよび展開方法

既定では、条件付きアクセス機能はテナント内のすべてのユーザーに対してテナント レベルで有効になっています。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得しているテナント内のユーザーにのみサービスを適用する方法

ID 保護と条件付きアクセスの場合は、ユーザーをグループに含めるか、条件付きアクセス ポリシーに追加する必要があります。 条件付きアクセス ポリシーでは、ユーザーとグループの条件が必須です。 ポリシーで、[すべてのユーザー] または [特定 **のユーザー** とグループ] を選択できます。 適切なライセンスを持つユーザーとグループのみを選択する必要があります。 詳細については、「条件付きアクセス [: 条件」を参照してください](/azure/active-directory/conditional-access/conditions)。

## <a name="advanced-audit"></a>高度な監査

Microsoft 365 の高度な監査では、ユーザーおよび管理アクティビティの監査ログを 1 年間保持し、他の Microsoft 365 サービスの監査ログ保持を管理するためのカスタム監査ログ保持ポリシーを作成できます。 また、調査のための重要なイベントへのアクセスと、365 管理アクティビティ API への高帯域幅アクセスOffice提供します。 詳細については [、「Advanced Audit in Microsoft 365」を参照してください](/microsoft-365/compliance/advanced-audit)。

また、アドオン SKU を使用して 10 年間の保持期間を有効にできます。 アドオン SKU は、2021 年初めから必要になります。

### <a name="which-users-benefit-from-the-service"></a>どのユーザーがサービスの恩恵を受けるか。

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 コンプライアンス、および Microsoft 365 E5/A5/G5 電子情報開示および監査のライセンスユーザーは、高度な監査を利用できます。

高度な監査と 10 年間の監査ログ保持アドオンを持つライセンスユーザーは、10 年間の監査ログ保持の恩恵を受ける可能性があります。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

Microsoft 365 サービスのユーザー アクティビティに関連する監査レコードを最大 1 年間保持できるので、ユーザーは高度な監査を利用できます。 さらに、ユーザーのメールボックス内のアイテムにアクセスまたは読み取りを行う場合など、価値の高い監査イベントがログに記録されます。 詳細については [、「Advanced Audit in Microsoft 365」を参照してください](/microsoft-365/compliance/advanced-audit)。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニングおよび展開方法

既定では、高度な監査は、Office 365 または Microsoft 365 E5/A5/G5 サブスクリプションを持つすべての組織のテナント レベルで有効にされ、Azure Active Directory、Exchange、および SharePoint のアクティビティ (適切なライセンスを持つユーザーによって実行される) の監査ログの 1 年間の保持が自動的に提供されます。 さらに、組織は監査ログ保持ポリシーを使用して、他の Microsoft 365 サービスのアクティビティによって生成された監査レコードの保持期間を管理できます。 10 年間の監査ログ保持機能も、同じ保持ポリシーを使用して有効になります。 詳細については、「[監査ログ保持ポリシーを管理する](/microsoft-365/compliance/audit-log-retention-policies)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得しているテナント内のユーザーにのみサービスを適用する方法

監査ログの 1 年間の保持と重要なイベントの監査は、適切なライセンスを持つユーザーにのみ適用されます。 さらに、管理者は監査ログ保持ポリシーを使用して、特定のユーザーの監査ログの保持期間を短く指定できます。

監査ログの 10 年間の保持は、適切なアドオン ライセンスを持つユーザーにのみ適用されます。 アドオン SKU は、2021 年初めから必要になります。