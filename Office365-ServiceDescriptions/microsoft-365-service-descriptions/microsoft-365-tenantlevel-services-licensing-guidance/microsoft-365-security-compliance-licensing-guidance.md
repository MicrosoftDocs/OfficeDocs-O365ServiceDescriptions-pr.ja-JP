---
title: セキュリティ&コンプライアンスに関するMicrosoft 365ライセンスガイダンス
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
description: この記事では、ライセンスのないアクセスによるサービスの中断を回避するために、Microsoft 365コンプライアンスに関するライセンス ガイダンスを提供します。
ms.openlocfilehash: d4ddb9c492cccef13c86e450c64a2eb6efe61eaa
ms.sourcegitcommit: adcacf68ac75c4db2229ebf55be9c75aecd3070b
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52546014"
---
# <a name="microsoft-365-licensing-guidance-for-security-amp-compliance"></a>セキュリティコンプライアンスに関するMicrosoft 365ライセンスガイダンス &amp;

この記事では、テナント レベルのサービスは、 &mdash; テナント内の任意のユーザー (スタンドアロン、またはOffice 365またはMicrosoft 365プランの一部として) を購入すると &mdash; 、テナント内のすべてのユーザーに対して一部または完全にアクティブ化されるオンライン サービスです。 ライセンスを持っていないユーザーの中には、技術的にサービスにアクセスできる場合がありますが、サービスの恩恵を受ける予定のユーザーにはライセンスが必要です。

> [!NOTE]
> 一部のテナント サービスは、現在、特定のユーザーに対して特典を制限することができません。 サービスの特典をライセンスユーザーに限定する努力が必要です。 これにより、ターゲット機能が利用可能になると、組織でサービスが中断する可能性を回避できます。

Microsoft 365コンプライアンス機能を利用してユーザーにライセンスを付与するオプションを確認するには、「詳細なMicrosoft 365コンプライアンス ライセンス比較」をダウンロードしてください。 [(PDF)](https://www.microsoft.com/download/details.aspx?id=103010)  | [(Excel)](https://www.microsoft.com/download/details.aspx?id=103006)

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

Azure Active DirectoryID 保護は、組織の ID に影響を及ぼす潜在的な脆弱性を検出し、組織の ID に関連する疑わしいアクションを検出する自動応答を構成し、不審なインシデントを調査して適切な対処を行い、それらを解決するための適切なアクションを実行できる、Azure Active Directory プレミアム P2 プランの機能です。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーは、このサービスのメリットをどのように得られるでしょうか。

SecOpsのアナリストやセキュリティ専門家は、機械学習アルゴリズムに基づいて、フラグを立てられたユーザーとリスクイベントの統合ビューを使用すると、メリットを得られます。 エンド ユーザーは、リスクベースの条件付きアクセスによって提供される自動保護と、脆弱性に対する対策によって提供されるセキュリティの強化を活用できます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスはどれですか。

Enterprise Mobility + SecurityE5/A5、Microsoft 365 E5/A5、Microsoft 365 E5/A5セキュリティ、およびAzure Active Directory プレミアムプラン2は、ユーザーがアイデンティティ保護をAzure Active Directory利益を得るための権利を提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスはどのようにプロビジョニング/展開されますか?

既定では、テナント内のすべてのユーザーのテナント レベルで Azure AD ID 保護機能が有効になっています。 Azure AD ID 保護の詳細については[、「ID 保護とは」を](/azure/active-directory/identity-protection/overview-identity-protection)参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得したテナントのユーザーにのみ、サービスを適用する方法はありますか。

管理者は、パスワードリセットのレベルを定義するリスク ポリシーを割り当て、ライセンスユーザーのみにアクセスを許可することで、Azure AD ID 保護の範囲を設定できます。 Azure AD ID プロテクションのデプロイの範囲を設定する方法については、「 [リスク ポリシーを構成および有効化する方法](/azure/active-directory/identity-protection/howto-sign-in-risk-policy)」を参照してください。

## <a name="azure-active-directory-identity-governance"></a>Azure Active Directoryアイデンティティガバナンス

Azure Active Directoryアイデンティティ・ガバナンスを使用すると、組織のセキュリティと従業員の生産性に対するニーズと、適切なプロセスと可視性のバランスを取ることができます。 権利管理、アクセス レビュー、特権 ID 管理、使用条件ポリシーを使用して、適切なユーザーが適切なリソースに対して適切なアクセス権を持つようにします。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーは、このサービスのメリットをどのように得られるでしょうか。

Azure Active DirectoryIdentity Governanceは、1 つのアクセス パッケージでアプリ、グループ、Microsoft Teamsへのアクセスを簡単に要求することで、ユーザーの生産性を向上させます。 ユーザーは、管理者を必要とせずに承認者として構成することもできます。 アクセス レビューでは、ユーザーは、定期的にアクションを実行するスマートな推奨事項を持つグループのメンバーシップを確認できます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスはどれですか。

Enterprise Mobility + SecurityE5/A5、Microsoft 365 E5/A5、Microsoft 365 E5/A5セキュリティ、およびAzure Active Directory プレミアムプラン2は、ユーザーがアイデンティティガバナンスAzure Active Directory利益を得る権利を提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスはどのようにプロビジョニング/展開されますか?

Azure AD ID ガバナンス機能は、テナント レベルで有効にしますが、ユーザーごとに実装されます。 Azure AD ID ガバナンスの詳細については [、「Azure AD ID ガバナンスとは」を参照してください。](/azure/active-directory/governance/identity-governance-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得したテナントのユーザーにのみ、サービスを適用する方法はありますか。

管理者は、アクセス パッケージ、アクセス レビュー、または特権 ID 管理をライセンスユーザーのみに割り当てることで、Azure AD ID ガバナンスの範囲を限定できます。 Azure AD ID ガバナンスのデプロイのスコープを設定する方法については、次を参照してください。

- [Azure AD の資格管理ライセンス要件](/azure/active-directory/governance/entitlement-management-overview#license-requirements)
- [Azure AD アクセス レビュー ライセンス要件](/azure/active-directory/governance/access-reviews-overview#license-requirements)
- [Privileged Identity Managementを使用するためのライセンス要件](/azure/active-directory/privileged-identity-management/subscription-requirements)

## <a name="microsoft-defender-for-identity"></a>Microsoft Defender for Identity

Microsoft Defender for Identity (以前は Azure 高度な脅威対策) は、高度な標的型サイバー攻撃や内部からの脅威からエンタープライズ ハイブリッド環境を保護するクラウド サービスです。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーは、このサービスのメリットをどのように得られるでしょうか。

SecOp のアナリストとセキュリティ専門家は、高度な脅威、侵害された ID、悪意のある内部関係者のアクションを検出して調査する、Microsoft Defender の ID の機能を活用できます。 エンド ユーザーは、Id の Microsoft Defender によってデータを監視することで利益を得ます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスはどれですか。

Enterprise Mobility + SecurityE5/A5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5セキュリティ、およびユーザーのためのアイデンティティのためのマイクロソフトディフェンダーは、アイデンティティのためのマイクロソフトディフェンダーから利益を得る権利を提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスはどのようにプロビジョニング/展開されますか?

既定では、テナント内のすべてのユーザーのテナント レベルで、Id の Microsoft Defender 機能が有効になっています。 Azure ATP の構成の詳細については [、「ID 用 Microsoft Defender インスタンスの作成](/defender-for-identity/install-step1)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得したテナントのユーザーにのみ、サービスを適用する方法はありますか。

現在、特定のユーザーに対して機能を制限することはできません。 特典を受ける予定のすべてのユーザーにライセンスを付与する必要があります。

## <a name="microsoft-defender-for-office-365"></a>Microsoft Defender for Office 365

マイクロソフト Defender for Office 365 (以前Office 365高度な脅威対策) は、フィッシングやゼロデイ マルウェアなどの高度な攻撃から組織を保護するのに役立ちます。 また、Office 365用 Microsoft Defender は、さまざまなデータからの信号を関連付けることで、潜在的な脅威に対処する方法を特定し、優先順位を付け、推奨事項を提供することで、実践的な洞察を提供します。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーは、このサービスのメリットをどのように得られるでしょうか。

マイクロソフト Defender のOffice 365フィッシングやゼロデイ マルウェアなどの高度な攻撃からユーザーを保護します。 プラン 1 およびプラン 2 で提供されるサービスの完全な一覧については[、「Office 365の Microsoft Defender](/microsoft-365/security/office-365-security/office-365-atp)」を参照してください。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスはどれですか。 

Office 365計画 1 および 2、Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 セキュリティ、およびOffice 365の Microsoft Defender から利益を得る権利をユーザーに提供Microsoft 365 Business Premium Microsoft Defender。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスはどのようにプロビジョニング/展開されますか?

既定では、テナント内のすべてのユーザーのテナント レベルでOffice 365機能の Microsoft Defender が有効になっています。 ライセンスを取得したユーザーのポリシー Office 365 Microsoft Defender を構成する方法については[、「Office 365用の Microsoft Defender](/microsoft-365/security/office-365-security/office-365-atp)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得したテナントのユーザーにのみ、サービスを適用する方法はありますか。

Microsoft Defender のOffice 365の範囲を限定するには、「リンクのセーフと添付ファイルの展開ポリシーセーフに従います。

- ライセンスを取得したユーザーのセーフ リンクの構成については[、「Office 365用の Microsoft Defender のリンクセーフ」](/microsoft-365/security/office-365-security/atp-safe-links)を参照してください。

- ライセンスを持つユーザーの添付ファイルセーフ構成する方法については[、「Microsoft Defender でOffice 365の添付ファイルをセーフ](/microsoft-365/security/office-365-security/atp-safe-attachments)する」を参照してください。

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud App Security (OCAS) はMicrosoft Cloud App Securityのサブセットで、機能はOffice 365に限定され、サードパーティのクラウド アプリや IaaS サービスに対する追加のセキュリティは含まれず、含まれています。

OCAS は、組織が生産性のクラウド アプリやサービスを可視化し、サイバー脅威を特定して対処するための高度な分析を提供し、Office 365全体でのデータの移動方法を制御できるようにします &mdash; 。

機能を比較するには[、「Microsoft Cloud App SecurityとOffice 365 Cloud App Securityの違い](/cloud-app-security/editions-cloud-app-security-o365)」を参照してください。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーは、このサービスのメリットをどのように得られるでしょうか。

OCAS は Shadow IT を検出し、Office 365全体にわたって脅威を保護し、データにアクセスするアクセス許可を持つアプリを制御できます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスはどれですか。

Office 365E5/A3/A5/G5 は、ユーザーがOCASの恩恵を受ける権利を提供します。
詳細については、「 Microsoft Cloud App Security[ライセンス データシート](https://www.aka.ms/mcaslicensing)」を参照してください。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスはどのようにプロビジョニング/展開されますか?

既定では、OCAS 機能はテナント レベルでテナント内のすべてのユーザーに対して有効になっています。

サービスの構成については[、「Cloud App Securityの基本セットアップ」を](/cloud-app-security/general-setup)参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得したテナントのユーザーにのみ、サービスを適用する方法はありますか。

管理者は、OCAS の展開の範囲を設定して、特定のアプリへのアクセス方法を強制し、Office 365 Cloud App Securityで監視するユーザー グループを制限できます。 詳細については、「 [スコープ指定の展開](/cloud-app-security/scoped-deployment)」を参照してください。

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) は、クラウド アクセス セキュリティ ブローカー (CASB) ソリューションで、組織がクラウド アプリやサービスを可視化し、サイバー脅威を特定して対処するための高度な分析を提供し、クラウド アプリ間でのデータの移動方法 &mdash; を制御できるようにします。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーは、このサービスのメリットをどのように得られるでしょうか。

MCAS は、シャドウ IT を検出して評価し、第 1 およびサードパーティのクラウド アプリ全体で脅威を保護し、第 1 およびサードパーティのクラウド アプリ間で情報を保護します。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスはどれですか。

MCAS、Enterprise Mobility + Security E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5セキュリティ、Microsoft 365 E5/A5/G5コンプライアンス、およびMicrosoft 365情報保護とガバナンスは、ユーザーがMCASの恩恵を受ける権利を提供します。

Azure AD P1 は、MCAS の探索機能の恩恵を受けるユーザーの権限を提供します。

MCAS の条件付きアクセス アプリ制御機能を利用するには、Enterprise Mobility + Security E3/A3/G3、Enterprise Mobility + Security E5/A5/G5、Microsoft 365 E3/A5/G5、Microsoft 365 E5/A5/G5、およびMicrosoft 365 E5/A5/G5 セキュリティに含まれる Azure Active Directory P1 のライセンスも必要です。

クライアント側の自動ラベリングを利用するには、Enterprise Mobility + Security E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5コンプライアンス、およびMicrosoft 365情報保護とガバナンスに含まれる Azure 情報保護 P2 のライセンスを取得する必要があります。

> [!NOTE]
> サーバー側のラベル付けの自動実行には、Office 365プレミアムライセンス (または) に対する情報保護 `MIP_S_CLP2` `efb0351d-3b08-4503-993d-383af8de41e3` が必要です。 参照については、「 [ライセンスの製品名とサービスプラン識別子」を](/azure/active-directory/enterprise-users/licensing-service-plan-reference)参照してください。

詳細については、「 Microsoft Cloud App Security[ライセンス データシート](https://www.aka.ms/mcaslicensing)」を参照してください。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスはどのようにプロビジョニング/展開されますか?

既定では、MCAS 機能はテナント レベルでテナント内のすべてのユーザーに対して有効になっています。

ライセンスユーザーのMicrosoft Cloud App Securityポリシーの設定については[、Microsoft Cloud App Securityの概要](/cloud-app-security/what-is-cloud-app-security)を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得したテナントのユーザーにのみ、サービスを適用する方法はありますか。

管理者は、サービスで使用可能なスコープ付き展開機能を使用して、ライセンスを付与されたユーザーに MCAS 展開を限定できます。 詳細については、「 [スコープ指定の展開](/cloud-app-security/scoped-deployment)」を参照してください。

## <a name="compliance-manager"></a>コンプライアンス マネージャー

コンプライアンス・マネージャを使用してコンプライアンスを簡素化し、リスクを軽減します。 コンプライアンス・マネージャは、規制、標準、会社のポリシー、またはその他の必要な制御フレームワークの要件を満たす組織を支援します。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーは、このサービスのメリットをどのように得られるでしょうか。

コンプライアンス マネージャー サービスのユーザーには、次のような利点があります。

- 複雑な規制、標準、会社の方針、その他の望ましい制御フレームワークをシンプルな言語に変換
- 独自のコンプライアンスニーズに対応する、膨大な組み込み評価とカスタム評価ライブラリへのアクセスを提供
- 推奨される改善措置に対する規制管理のマップ
- 規制要件を満たすソリューションを実装する方法に関するステップ バイ ステップ のガイダンスを提供します。
- 各アクションにスコアを関連付けることで、組織のコンプライアンスに最も大きな影響を与えるアクションに優先順位を付けることができます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスはどれですか。

E1 および E3/G3 ライセンスをお持ちのお客様は、デフォルトのデータ保護ベースライン評価にのみアクセスできます。 E5/A5およびMicrosoft 365 E5/A5ライセンス(コンプライアンス、情報保護、&ガバナンス、電子情報開示および監査SKUを含む)をOffice 365お客様は、データ保護ベースライン、GDPR、NIST 800-53、およびISO 27001の標準評価にアクセスできます。 Office 365 G5 および Microsoft 365 G5 をお持ちのお客様は、データ保護ベースライン、GDPR、NIST 800-53、ISO 27001、サイバーセキュリティ成熟度モデル認定 (CMMC) レベル 1 ~ 5 段階の評価にアクセスできます。 カスタム評価機能とプレミアム評価は、E5/A5/G5およびMicrosoft 365 E5/A5/G5のお客様Office 365のために予約されています。 2021 年上半期には、VL、CSP、WebDirect を通じて、FedRAMP モデレート、フェドランプ ハイなどのプレミアム評価を E5/A5/G5 ライセンスをお持ちのお客様に購入できます。 マイクロソフトの販売者またはマイクロソフト パートナーに、それぞれ VL または CSP チャネルを通じて購入してください。 WebDirect を使用して購入するには [、「WebDirect」](https://aka.ms/ComplianceManager/WebDirect)を参照してください。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスはどのようにプロビジョニング/展開されますか?

コンプライアンス マネージャーは、テナントに既定でプロビジョニングされます。 管理者は、ユーザーのアクセス許可を設定し、組織内の管理者以外のユーザーがコンプライアンス マネージャーを使用して開始できるように、ロールを割り当てます。 詳細については、「コンプライアンス [マネージャの概要 : ユーザー権限の設定とロールの割り当て](/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles)」を参照してください。

## <a name="microsoft-defender-for-endpoint"></a>Microsoft Defender for Endpoint

エンドポイント用 Microsoft Defender (以前のMicrosoft Defender ATP) は、リスクベースの脆弱性の管理と評価を含むエンドポイント セキュリティ ソリューションです。攻撃面の縮小機能。行動ベースおよびクラウド駆動の次世代保護。エンドポイントの検出と応答(EDR);自動調査と修復;そして狩猟サービスを管理しました。 詳細については、「 [エンドポイント用の Microsoft Defender」](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) ページを参照してください。

### <a name="which-users-benefit-from-the-service"></a>サービスの恩恵を受けるユーザーはどれですか。

Windows 10 Enterprise E5、Windows 10 Education A5、Microsoft 365 E5/G5 のライセンスユーザー(Windows 10 Enterprise E5、Microsoft 365 E5/A5/G5 セキュリティを含む)は、エンドポイント用 Microsoft Defender の特典を受けることができます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーは、このサービスのメリットをどのように得られるでしょうか。

SecOps のアナリストとセキュリティ専門家は、予防的な保護、違反後の検出、自動調査、高度な脅威への対応を行う Microsoft Defender for Endpoint のエンドポイント セキュリティ機能の恩恵を受けます。 エンド ユーザーは、エンドポイントの Microsoft Defender によって監視される悪意のあるイベントを持つことで利益を得ます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスはどのようにプロビジョニング/展開されますか?

既定では、エンドポイントの Microsoft Defender 機能は、テナント内のすべてのユーザーのテナント レベルで有効になっています。 展開の詳細については、「 [展開フェーズ](/windows/security/threat-protection/microsoft-defender-atp/deployment-phases)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得したテナントのユーザーにのみ、サービスを適用する方法はありますか。

Microsoft Defender for Endpoint 管理者は、役割ベースのアクセス制御 (RBAC) を使用して、セキュリティ運用チーム内に役割とグループを作成し、Microsoft Defender セキュリティ センターに適切なアクセス権を付与できます。 詳細については、「 [ロールベースのアクセス制御を使用したポータル アクセスの管理](/windows/security/threat-protection/microsoft-defender-atp/rbac)」を参照してください。

## <a name="microsoft-365-data-classification-analytics-overview-content-amp-activity-explorer"></a>Microsoft 365データ分類分析: 概要コンテンツ &amp; アクティビティ エクスプローラー

データ分類分析機能は、コンプライアンス センターのエクスペリエンス内Microsoft 365利用できます。 概要は、デジタル コンテンツの場所と、最も一般的な機密情報の種類とラベルを示しています。 コンテンツ エクスプローラーでは、機密データの量と種類を表示でき、ユーザーはラベルまたは機密データの種類別にフィルター処理して、機密データが格納されている場所の詳細なビューを取得できます。 アクティビティ エクスプローラーには、コンテンツをリスクにさらす可能性のあるラベルのダウングレードや外部共有など、機密データやラベルに関連するアクティビティが表示されます。

アクティビティ エクスプローラーには、エンド ユーザーが使用している機密情報に関連するアクティビティの表示を管理者に提供する 1 つのウィンドウが用意されています。 これらのデータには、ラベル アクティビティ、データ損失防止 (DLP) ログ、自動ラベル付け、エンドポイント DLP などがあります。

Content Explorer は、サポートされているMicrosoft 365ワークロード内に格納されている機密ドキュメントをインデックス化し、保存している機密情報を特定する機能を管理者に提供します。 また、コンテンツ エクスプローラーは、機密度ラベルと保持ラベルで分類されたドキュメントを識別するのに役立ちます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーは、このサービスのメリットをどのように得られるでしょうか。

情報保護とコンプライアンス管理者は、サービスにアクセスしてこれらのログとインデックス付けされたデータにアクセスし、機密データが保存されている場所と、このデータに関連付けられており、エンド ユーザーが実行するアクティビティを把握できます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスはどれですか。

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5コンプライアンス、Microsoft 365 E5/A5/G5情報保護 &amp; ガバナンス、Office 365 E5のライセンスユーザーは、Microsoft 365データ分類分析のメリットを享受できます。 

Microsoft 365 E3/A3/G3 およびOffice 365 E3/A3/G3 では、コンテンツ エクスプローラのデータ集約のみを利用できます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスはどのようにプロビジョニング/展開されますか?

既定では、テナント レベルで [概要コンテンツ] および [アクティビティ エクスプローラー] 機能がテナント内のすべてのユーザーに対して有効になっています。 ライセンスユーザーのデータ分類分析の構成については、以下を参照してください。

- **コンテンツ エクスプローラー**:[コンテンツ エクスプローラーの概要 - コンプライアンス |Microsoft 365マイクロソフトドキュメント](/microsoft-365/compliance/data-classification-content-explorer).
- **アクティビティ エクスプローラー**:[アクティビティ エクスプローラーの概要 - Microsoft 365 コンプライアンス |マイクロソフトドキュメント](/microsoft-365/compliance/data-classification-activity-explorer).
- **データ分類リリース ノート**:[データ分類リリース ノート - Microsoft 365 コンプライアンス |マイクロソフトドキュメント](/microsoft-365/compliance/data-classification-pub-preview-relnotes).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得したテナントのユーザーにのみ、サービスを適用する方法はありますか。

この機能は、コンプライアンス ポータル内でソリューションをアクティブに使用するユーザー Microsoft 365対象範囲とする必要があります。

## <a name="information-protection"></a>情報保護

情報保護は、機密文書やメールを検出、分類、ラベル付けし、保護するのに役立ちます。 管理者は、ラベルを自動的に適用するルールと条件を定義したり、ユーザーがラベルを手動で適用したり、2 つの組み合わせを使用したりできます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーは、このサービスのメリットをどのように得られるでしょうか。

ユーザーは、コンテンツに手動で機密ラベルを適用したり、コンテンツを自動的に分類したりすることでメリットを得られます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスはどれですか。

Microsoft 365 E5/A5/G5/E3/A3/G3/G3/F1/F3/ビジネスプレミアム、Enterprise Mobility + Security F3/E3/E5、Office 365 E5/A5/E3/A3/F3、AIPプラン1、およびAIPプラン2は、ユーザーが手動感度ラベリングの恩恵を受ける権利を提供します。

Microsoft 365 E5/A5/G5/E3/A3/G3/G3/F1/F3/F3/ビジネスプレミアム、Enterprise Mobility + Security F3/E3/E5、AIPプラン1、AIPプラン2は、Power BIに機密ラベルを適用して表示し、Power BIからExcel、PowerPoint、またはPDFにエクスポートするときにデータを保護する権利を提供します。 

> [!NOTE]
> Power BIはMicrosoft 365 E5/A5/G5に含まれています。その他すべてのプランでは、Power BIは別々にライセンスを取得する必要があります。

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5コンプライアンス、Microsoft 365 E5/A5/G5情報保護、ガバナンス、e5、e5/A5/G5 Enterprise Mobility + Security、およびAIPプラン2 Office 365は、ユーザーが自動感度ラベル付けの恩恵を受ける権利を提供します。

ライセンス別の特定の権利については、コンプライアンス ライセンス比較の詳細Microsoft 365を参照してください。 [(PDF)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  | [(Excel)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)Machine Learning (トレーニング可能分類子) に基づく自動分類の権限は含まれません。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスはどのようにプロビジョニング/展開されますか?

既定では、情報保護機能は、テナント内のすべてのユーザーのテナント レベルで有効になっています。 ライセンスユーザーのポリシーの構成については、「Azure 権限管理のアクティブ化」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得したテナントのユーザーにのみ、サービスを適用する方法はありますか。

AIP スキャナー機能を使用する場合を除き、ポリシーのスコープを特定のグループまたはユーザーに設定し、ライセンスを持つユーザーが分類またはラベル付け機能を実行できないように、レジストリを編集できます。 AIP デプロイのスコープを設定する方法については [、「Azure 情報保護ポリシーの構成](/azure/information-protection/configure-policy)」を参照してください。

AIP スキャナー機能については、マイクロソフトは、ライセンスを持たないユーザーに対して、ファイルの分類、ラベル付け、または保護機能の提供を行いません。

## <a name="information-governance"></a>情報ガバナンス

情報ガバナンスは、組織がデータの検出、分類、ラベル付け、管理を行い、リスクを管理するのに役立ちます。 情報ガバナンスにより、組織はビジネスや規制上の要件を満たすだけでなく、Microsoft 365やサードパーティのデータ全体にわたって保持/削除機能を提供することで、攻撃の可能性を低減できます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーは、このサービスのメリットをどのように得られるでしょうか。

ユーザーは、特定のポリシーや規制を遵守するために、保存目的でデータを分類できることでメリットを得られます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスはどれですか。

Microsoft 365 F3/ビジネス プレミアム、Office 365 E1/A1/F3、およびスタンドアロン Exchange プランは、ユーザーが非レコード保持ラベルをメールボックス データに手動で適用することで利益を得る権利を提供します。

Microsoft 365 F3/F1/ビジネスプレミアム、Office 365 E1/A1/F3、およびスタンドアロンSharePointプランは、ユーザーがSharePointまたはOneDriveのファイルに非レコード保持ラベルを手動で適用することで利益を得る権利を提供します。 

Microsoft 365 E5/A5/G5/E3/A3/ビジネスプレミアム、E5/A5/G5/E3/A3 Office 365プラン2 Exchange、ユーザーが基本的な組織全体または場所全体のメールボックス保持ポリシーの恩恵を受ける権利を提供し、メールボックスデータに非レコード保持ラベル付けを手動で適用する権利を提供 Exchange Online Archivingします。

Microsoft 365 E5/A5/G5/E3/A3、Office 365 E5/A5/G5/E3/A3、SharePointプラン2は、ユーザーが基本的なSharePointまたはOneDrive保持ポリシーの恩恵を受ける権利を提供し、SharePointまたはOneDrive内のファイルに非記録保持ラベルを手動で適用します。

Microsoft 365 E5/A5/G5/E3/A3 および Office 365 E5/A5/G5/E3/A3 は、ユーザーがTeams保持ポリシーの恩恵を受ける権利を提供します。

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5コンプライアンス、 Microsoft 365情報保護とガバナンス E5/A5/G5、およびOffice 365 E5/A5 は、ユーザーが保持ラベルまたはポリシーを自動的に適用し、既定の保持ラベルまたはポリシーを適用し、カスタム イベントに基づいて保持ラベルの保持期間を開始し、ラベルの保持期間の終了時に手動の廃棄レビューをトリガーし、ネイティブ データ コネクタを通じてサード パーティのデータをインポートし、ラベル付けされたコンテンツを検出し、ラベル付けされたコンテンツを検出する権利をユーザーに提供します。

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5コンプライアンス、Microsoft 365 E5/A5/G5情報保護、ガバナンスは、ユーザーがトレーニング可能な分類器に基づいて自動的に保持ラベルを適用することで利益を得る権利を提供します。

ライセンス別の特定の権利については、コンプライアンス ライセンス比較の詳細Microsoft 365を参照してください。 [(PDF)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  | [(Excel)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-is-the-service-provisioneddeployed"></a>サービスはどのようにプロビジョニング/展開されますか?

既定では、情報ガバナンス機能は、テナント内のすべてのユーザーのテナント レベルで有効になっています。 ライセンスユーザーに自動ラベル付けとポリシーを適用するための情報ガバナンスの構成については[、「Microsoft 365のマイクロソフト情報ガバナンス](/microsoft-365/compliance/manage-information-governance)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得したテナントのユーザーにのみ、サービスを適用する方法はありますか。

情報ガバナンス機能は、特定の場所 (チーム サイト、グループ サイトなど) のライセンスユーザーに適用できます。 ライセンスユーザーに自動ラベル付けとポリシーを適用するための情報ガバナンスの構成については[、「Microsoft 365のマイクロソフト情報ガバナンス](/microsoft-365/compliance/manage-information-governance)」を参照してください。

## <a name="records-management"></a>レコード管理

レコード管理は、組織がMicrosoft 365およびサードパーティのデータ全体にわたって、企業のビジネスおよび規制による記録保持の義務を満たす上で、検出、分類、ラベル付け、保持、防御可能な削除機能を提供します。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスはどれですか。

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5コンプライアンス、Microsoft 365情報保護およびガバナンスE5/A5/G5、およびOffice 365 E5/A5/G5は、アイテムをレコードまたは規制記録として宣言し、保存または記録ラベルを自動的に適用し、廃棄レビュープロセスを実行する(訓練可能な分類器に基づいて保存ラベルを自動的に適用することを除く)など、レコード管理の利益を享受する権利をユーザーに提供します。

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5コンプライアンス、およびMicrosoft 365情報保護およびガバナンスは、ユーザーがトレーニング可能な分類器に基づいて保存またはレコードラベルを自動的に適用することで利益を得る権利を提供します。

ライセンス別の特定の権利については、コンプライアンス ライセンス比較の詳細Microsoft 365を参照してください。 [(PDF)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  | [(Excel)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーは、このサービスのメリットをどのように得られるでしょうか。

ユーザーは、コンテンツをレコードとして宣言し、ポリシー定義と宣言から、防御可能な処分によって完全なレコードプロセスを管理できることでメリットを得ます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスはどのようにプロビジョニング/展開されますか?

既定では、テナント内のすべてのユーザーに対して、テナント レベルでレコード管理機能が有効になっています。 ライセンスユーザーに適用するレコード管理の設定については[、「Microsoft 365のレコード管理について」](/microsoft-365/compliance/records-management)を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得したテナントのユーザーにのみ、サービスを適用する方法はありますか。

レコード管理機能は、特定の場所 (チーム サイト、グループ サイトなど) のライセンスユーザーに適用できます。 ライセンスユーザーに適用するレコード管理の設定については[、「Microsoft 365のレコード管理について」](/microsoft-365/compliance/records-management)を参照してください。

## <a name="data-connectors"></a>データ コネクタ 

マイクロソフトでは、Microsoft 365 コンプライアンス センターで構成できるサード パーティ製のデータ コネクタを提供しています。 Microsoft が提供するデータ コネクタの一覧については、 [サードパーティ製のデータ コネクタ](/microsoft-365/compliance/archiving-third-party-data#third-party-data-connectors) の表を参照してください。 また、この表では、Microsoft 365でデータをインポートおよびアーカイブした後にサード パーティのデータに適用できるコンプライアンス ソリューションと、各コネクタの手順に沿った手順へのリンクも示します。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーは、このサービスのメリットをどのように得られるでしょうか。

データ コネクタを使用してサード パーティ製 Microsoft 365データをインポートおよびアーカイブする主な利点は、インポート後にさまざまなMicrosoft 365コンプライアンス ソリューションをデータに適用できることです。 これにより、組織の Microsoft 以外のデータが、組織に影響する規制や標準に準拠していることを確認できます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスはどれですか。

次のライセンスは、ユーザーがデータ コネクタの恩恵を受ける権利を提供します。

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 情報保護 &amp; ガバナンス
- Microsoft 365 E5/A5/G5コンプライアンス
- Microsoft 365 E5/A5/G5 インサイダーリスクマネジメント
- Microsoft 365 E5/A5/G5 電子情報開示と監査
- Office 365E5/A5/G5

Microsoft パートナーが提供するMicrosoft 365 セキュリティ コンプライアンス センターのデータ &amp; コネクタの場合、これらのコネクタを展開する前に、パートナーとのビジネス関係が組織に必要になります。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスはどのようにプロビジョニング/展開されますか?

コネクタは、セキュリティ コンプライアンス &amp; センターおよびコネクタ カタログを使用して構成します。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得したテナントのユーザーにのみ、サービスを適用する方法はありますか。

データ コネクタ サービスはテナント レベルの値です。 このサービスの恩恵を受けるすべてのユーザーは、ライセンスを取得する必要があります。

## <a name="microsoft-graph-apis-for-teams-data-loss-prevention-dlp"></a>マイクロソフト Graph Teams データ損失防止 (DLP) 用の API を提供します。

今年の初めに、[メッセージの Microsoft Graph変更通知 API のパブリック プレビューをTeamsで発表](https://go.microsoft.com/fwlink/?linkid=2143888)しました。 この API を使用すると、開発者は、ほぼリアルタイムでMicrosoft Teams メッセージをリッスンし、顧客と ISV の両方に DLP シナリオの実装を可能にするアプリを構築できます。 さらに、Microsoft Graph パッチ API では、Teams メッセージに DLP アクションを適用できます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーは、このサービスのメリットをどのように得られるでしょうか。

[データ損失防止 (DLP)](/microsoft-365/compliance/dlp-microsoft-teams)機能は、特に組織がリモート作業に移行したため、Microsoft Teamsで広く使用されています。 組織に DLP がある場合、Microsoft Teams チャネルまたはチャット セッションで機密情報を共有できないようにするポリシーを定義できるようになりました。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスはどれですか。

Teams チャットで DLP 保護のサポートを受けるには、次のいずれかのライセンスが必要です。

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5コンプライアンス
- Microsoft 365 E5/A5/G5 情報保護とガバナンス
- Office 365E5/A5/G5 

### <a name="how-is-the-service-provisioneddeployed"></a>サービスはどのようにプロビジョニング/展開されますか?

API アクセスはテナント レベルで構成されます。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得したテナントのユーザーにのみ、サービスを適用する方法はありますか。

dlp Teamsの Microsoft Graph API は、テナント レベルの値です。 このサービスの恩恵を受けるすべてのユーザーは、ライセンスを取得する必要があります。

## <a name="ediscovery"></a>電子情報開示

電子情報開示は、企業内の IT 部門および法務部門が、Microsoft 365 システムからエクスポートする前に調査または訴訟に関連するコンテンツを特定、収集、保存、削減、およびレビューするための調査および電子情報開示ソリューションを提供します。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーは、このサービスのメリットをどのように得られるでしょうか。

ユーザーがケースのデータ管理者 (ドキュメントまたは電子ファイルの管理制御を持つユーザー) として選択されると、ユーザーはAdvanced eDiscoveryの恩恵を受けます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスはどれですか。

Microsoft 365 E5/A5/G5/E3/A3/G3、e5/A5/G5/G3/G3 Office 365 E5/A5/E3/A3/G3は、ユーザーがコア電子情報開示の恩恵を受ける権利を提供します。

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5コンプライアンス、Microsoft 365 E5/A5/G5電子情報開示および監査、Office 365 E5/A5/G5は、ユーザーがAdvanced eDiscoveryの恩恵を受ける権利を提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスはどのようにプロビジョニング/展開されますか?

既定では、管理者がセキュリティ コンプライアンス センターで電子情報開示のアクセス許可を割り当てると、テナント内のすべてのユーザーのテナント レベルでAdvanced eDiscovery機能が有効になります &amp; 。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得したテナントのユーザーにのみ、サービスを適用する方法はありますか。

電子情報開示管理者は、Advanced eDiscoveryの組み込み管理ツールを使用して、特定のユーザーを[Advanced eDiscoveryケース](/microsoft-365/compliance/add-custodians-to-case)のデータ管理担当者として選択できます 。

## <a name="customer-key-for-microsoft-365"></a>Microsoft 365の顧客キー

顧客キーを使用すると、組織の暗号化キーを制御し、そのキーを使用して Microsoft データ センターの保存データを暗号化するようにMicrosoft 365を構成できます。 つまり、顧客キーを使用すると、独自のキーを使用して、自分に属する暗号化の層を追加することができます。 保存データには、Exchange OnlineおよびSkype for Businessのデータが含まれ、SharePoint Online およびOneDrive for Business内のメールボックスおよびファイルに格納されます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーは、このサービスのメリットをどのように得られるでしょうか。

ユーザーは、組織が提供、制御、管理する暗号化キーを使用して、アプリケーション層で保存データを暗号化することで、Customer Key のメリットを享受できます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスはどれですか。

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5コンプライアンス、Microsoft 365 E5/A5/G5情報保護およびガバナンス、およびOffice 365 E5/A5/G5は、ユーザーが顧客キーから利益を得る権利を提供します。 カスタマー キーの特典を最大限に活用するには、Azure Key Vault のサブスクリプションも必要です。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスはどのようにプロビジョニング/展開されますか?

Microsoft 365暗号化キーのユーザー キーは、Exchange OnlineおよびSkype for Businessメールボックスに格納されているすべてのデータ、およびオンライン、OneDrive for Business、およびTeamsファイルSharePoint有効にすることができます。 開始方法を含む顧客キーの詳細については、「 [カスタマーキーによるサービス暗号化](/microsoft-365/compliance/customer-key-overview)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得したテナントのユーザーにのみ、サービスを適用する方法はありますか。

Exchange OnlineおよびSkype for Businessの場合、メールボックスは、顧客キーを使用して暗号化できます。 Microsoft 365に顧客キーを使用する前に、Azure を設定する必要があります。 必要な Azure リソースを作成および構成するために必要な手順、およびMicrosoft 365で[カスタマー キー](/microsoft-365/compliance/customer-key-set-up)を設定する手順については、「カスタマー キーの設定」をご覧ください。 Azure のセットアップが完了したら、組織内のメールボックスとファイルに割り当てるポリシーと、そのキーを決定します。 カスタマーキー、およびExchange Online、Skype for Business、SharePoint オンライン、OneDrive for Business、Teamsのデータに関するコンテンツの詳細については、「[カスタマーキーによるサービス暗号化](/microsoft-365/compliance/customer-key-overview)」を参照してください。

## <a name="office-365-customer-lockbox"></a>Office 365 カスタマー ロックボックス

顧客ロックボックスは、サービス操作に対して明示的なアクセス許可を提供する機能を顧客に提供することで、制御の追加レイヤーを提供します。 明示的なデータ アクセス許可の手順が実施されていることを示すことで、顧客ロックボックスは、HIPAA や FedRAMP などの特定のコンプライアンス義務を組織が満たすのに役立つ場合もあります。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーは、このサービスのメリットをどのように得られるでしょうか。

顧客ロックボックスは、顧客の明示的な承認なしに、Microsoft が顧客コンテンツにアクセスしてサービス操作を実行することを保証します。 顧客ロックボックスは、顧客のコンテンツにアクセスする要求の承認ワークフローに顧客を持ち込みます。 サポート プロセス中に、マイクロソフトのエンジニアが、お客様から報告された問題のトラブルシューティングと修正を行う場合があります。 ほとんどの場合、Microsoft が提供するサービスに関する広範なテレメトリとデバッグ ツールによって問題が修正されます。 ただし、根本的な原因を特定して問題を解決するために、Microsoft エンジニアが顧客のコンテンツにアクセスする必要がある場合があります。 カスタマー ロックボックスでは、承認ワークフローの最終ステップとして、エンジニアが顧客にアクセス要求を行う必要があります。 これにより、組織はこれらの要求を承認または拒否するオプションを提供し、Microsoft エンジニアが組織のエンド ユーザー データにアクセスできるかどうかを直接制御できます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスはどれですか。

Office 365E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5コンプライアンス、Microsoft 365 E5/A5/G5インサイダーリスク管理は、ユーザーがカスタマーロックボックスから利益を得る権利を提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスはどのようにプロビジョニング/展開されますか?

管理者は、Microsoft 365管理センターでカスタマー ロックボックスを有効にすることができます。 詳細については、「 [Office 365 のカスタマー ロックボックス](/microsoft-365/compliance/customer-lockbox-requests)」を参照してください。 お客様のロックボックスを有効にすると、Microsoft は、コンテンツにアクセスする前に組織の承認を得る必要があります。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得したテナントのユーザーにのみ、サービスを適用する方法はありますか。

現在、カスタマーロックボックスサービスを特定のユーザーに制限することはできません。 特典を受ける予定のすべてのユーザーにライセンスを付与する必要があります。

## <a name="privileged-access-management-in-office-365"></a>Office 365 での特権アクセス管理

[特権アクセス管理 (PAM) では](/microsoft-365/compliance/privileged-access-management-configuration)、Office 365の特権管理タスクに対する細かいアクセス制御を提供します。 PAM を有効にした後、昇格された特権的なタスクを完了するには、ユーザーは、スコープが大きく、時間制限の高い承認ワークフローを通じて、ジャスト イン タイム アクセスを要求する必要があります。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーは、このサービスのメリットをどのように得られるでしょうか。

PAM を有効にすると、組織は、ゼロの権限で動作します。 ユーザーは、データへの自由なアクセスを提供する常設管理アクセスから生じる脆弱性に対する防御の追加レイヤーから恩恵を受けます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスはどれですか。 

Office 365E5/A5、Microsoft 365 E5/A5、Microsoft 365 E5/A5コンプライアンス、およびMicrosoft 365 E5/A5情報保護とガバナンスは、ユーザーがPAMの恩恵を受ける権利を提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスはどのようにプロビジョニング/展開されますか?

既定では、PAM 機能はテナント レベルでテナント内のすべてのユーザーに対して有効になっています。 PAM ポリシーの構成については、「 [特権アクセス管理の概要](/microsoft-365/compliance/privileged-access-management-configuration)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得したテナントのユーザーにのみ、サービスを適用する方法はありますか。

お客様は、承認者グループとアクセス ポリシーを使用してユーザーごとに PAM を管理でき、ライセンスを付与されたユーザーに適用できます。 詳細については、「 [Office 365 の特権アクセス管理 」](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751)を参照してください。

## <a name="double-key-encryption-for-microsoft-365"></a>Microsoft 365のダブルキー暗号化 

Microsoft 365の二重キー暗号化を使用すると、機密性の高いデータを保護して特殊な要件を満たし、暗号化キーを完全に制御できます。 ダブルキー暗号化では、2つのキーを使用してデータを保護し、1つのキーをコントロールに、もう1つのキーをMicrosoft Azureによって安全に保存します。 データを表示するには、両方のキーにアクセスできる必要があります。 Microsoft は 1 つのキーにのみアクセスできるため、お客様のキーとデータは Microsoft が利用できないため、お客様はデータのプライバシーとセキュリティを完全に制御できます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーは、このサービスのメリットをどのように得られるでしょうか。

ユーザーは、暗号化されたデータをクラウドに移行できることで、キーがユーザーを制御している限り、サードパーティのアクセスを防止することで、ダブルキー暗号化の恩恵を受けることができます。 ユーザーは、保護された他の機密ラベルのコンテンツと同様に、ダブルキー暗号化されたコンテンツを保護して使用することができます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスはどれですか。

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5コンプライアンス、Microsoft 365 E5/A5/G5情報保護およびガバナンス、Office 365 E5/A5/G5は、ユーザーがダブルキー暗号化の恩恵を受ける権利を提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスはどのようにプロビジョニング/展開されますか?

ダブル キー暗号化では、Windows用のMicrosoft Officeのデスクトップ バージョンがサポートされます。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得したテナントのユーザーにのみ、サービスを適用する方法はありますか。

ライセンスユーザーのOffice 365または Microsoft 365組織内のデータに暗号化キーを割り当てるには、二重キー暗号化の展開手順に従ってください。

## <a name="office-365-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Exchange Online、オンライン、OneDrive for BusinessのSharePointデータ損失防止をOffice 365

Exchange Online SharePoint、オンライン、OneDrive for Business Office 365データ損失防止 (DLP) により、組織はメールやファイル (ファイル リポジトリに保存されているファイルを含む) の機密情報を識別、監視、および自動的に保護Microsoft Teams。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーは、このサービスのメリットをどのように得られるでしょうか。

ユーザーは、組織の DLP ポリシーで構成されている機密情報について電子メールやファイルを検査する場合、Exchange Online、SharePointオンライン、OneDrive for Businessの DLP のメリットを享受できます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスはどれですか。

Microsoft 365 E3/A3/ビジネスプレミアム、Office 365 E3/A3、およびOffice 365データ損失防止は、ユーザーがExchange Online、SharePoint オンライン、およびOneDrive for Businessに対してOffice 365 DLP の恩恵を受ける権利を提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスはどのようにプロビジョニング/展開されますか?

既定では、Exchange Online電子メール、SharePoint サイト、およびOneDrive アカウントは、テナント内のすべてのユーザーに対してこれらの DLP 機能の *有効な場所 (ワークロード)* です。 DLP ポリシーの使用の詳細については、「 [データ損失防止の概要](/microsoft-365/compliance/data-loss-prevention-policies)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得したテナントのユーザーにのみ、サービスを適用する方法はありますか。

管理者は、セキュリティ コンプライアンス センターの場所 (ワークロード)、対象ユーザー、および除外されたユーザーを [ &amp; **データ損失防止**  >  **の場所]** でカスタマイズできます。

## <a name="communication-data-loss-prevention-for-teams"></a>Teamsのための通信データ損失防止

Teams向け通信 DLP を使用すると、組織は、財務情報、個人識別情報、正常性関連情報、その他の機密情報などの機密情報を含むチャットやチャネル メッセージをブロックできます。

### <a name="which-users-benefit-from-the-service"></a>サービスの恩恵を受けるユーザーはどれですか。

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、およびMicrosoft 365 E5/A5/G5情報保護およびガバナンスのライセンスを取得したユーザーは、Teamsのためのコミュニケーション DLP のメリットを享受できます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーは、このサービスのメリットをどのように得られるでしょうか。

送信者は、組織の DLP ポリシーで構成されている機密情報を検査する送信チャットおよびチャネル メッセージに機密情報を含めることで利益を得ます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスはどのようにプロビジョニング/展開されますか?

既定では、Teamsチャットおよびチャネル メッセージは、テナント内のすべてのユーザーに対して、これらの DLP 機能の *有効な場所 (ワークロード) です*。 DLP ポリシーの使用の詳細については、「 [データ損失防止の概要](/office365/securitycompliance/data-loss-prevention-policies)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得したテナントのユーザーにのみ、サービスを適用する方法はありますか。

管理者は、セキュリティ コンプライアンス センターの場所 (ワークロード)、対象ユーザー、および除外されたユーザーを [ &amp; **データ損失防止**  >  **の場所]** でカスタマイズできます。

## <a name="information-barriers"></a>情報バリア

情報バリアは、ユーザーまたはグループが相互に通信するのを防ぐために、管理者が構成できるポリシーです。 これは、たとえば、ある部門が他の部門と共有すべきではない情報を処理している場合や、グループが外部の連絡先との通信を禁止する必要がある場合に便利です。 情報バリア ポリシーでは、ルックアップと検出も防止されます。 つまり、相手と通信してはいけない相手と通信しようとすると、そのユーザーがユーザー選択ウィンドウに表示されません。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーは、このサービスのメリットをどのように得られるでしょうか。

ユーザーは、他のユーザーとの通信が制限されている場合に、情報の障壁の高度なコンプライアンス機能の恩恵を受けます。 情報バリア ポリシーを定義して、特定のユーザー セグメントが各セグメントと通信できないようにしたり、特定のセグメントが他の特定のセグメントとのみ通信できるようにしたりすることができます。 情報バリア ポリシーの定義の詳細については、 [情報バリア ポリシーの定義](/microsoft-365/compliance/information-barriers-policies)を参照してください。 2 つのグループが相互に通信できない場合、両方のグループのユーザーは、サービスの恩恵を受けるためにライセンスを必要とします (以下の例を参照)。<br><br>

| シナリオ | Whoライセンスが必要ですか? |
|:------|:------|
| 2 つのグループ (グループ &nbsp; 1 とグループ &nbsp; 2) は相互に通信できません (つまり、グループ &nbsp; 1 のユーザーはグループ 2 ユーザーとの通信を制限 &nbsp; され、グループ &nbsp; 2 のユーザーはグループ 1 のユーザーとの通信を制限されます &nbsp; )。 | グループ 1 &nbsp; とグループ 2 の両方のユーザー &nbsp; |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスはどれですか。

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5コンプライアンス、Microsoft 365 E5/A5/G5インサイダーリスク管理、およびOffice 365 E5/A5/G5は、ユーザーが情報障壁の恩恵を受ける権利を提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスはどのようにプロビジョニング/展開されますか?

管理者は、セキュリティ コンプライアンス センターで PowerShell コマンドレットを使用して情報バリア ポリシーを作成および管理 &amp; します。 管理者は、情報バリア ポリシーを作成するには、Microsoft 365 Enterpriseグローバル管理者、Office 365グローバル管理者、コンプライアンス管理者の役割を割り当てる必要があります。 既定では、これらのポリシーはテナント内のすべてのユーザーに適用されます。 情報バリアの詳細については[、「Microsoft Teamsの情報バリア](/MicrosoftTeams/information-barriers-in-teams)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得したテナントのユーザーにのみ、サービスを適用する方法はありますか。

管理者は、セキュリティ コンプライアンス センターで場所 (ワークロード)、対象ユーザー、および除外されたユーザーをカスタマイズできます &amp; 。 たとえば、すべてのユーザーが Office 365 E3 のライセンスを取得しており、Office 365 Advanced Compliance/E5 のライセンスを持っていない場合、組織の情報バリア ポリシーを作成する必要はありません。 詳細については、[Microsoft Teams における情報バリア](/MicrosoftTeams/information-barriers-in-teams)に関するページを参照してください。

## <a name="office-365-message-encryption"></a>Office 365 Message Encryption

Office 365 Message Encryption (OME) は、Azure Rights Management (Azure RMS) で構築され、宛先のメール アドレス (Gmail、Yahoo! Mail、Outlook.com など) に関係なく、暗号化された電子メールを組織内外の宛先に送信できるようにするサービスです。

暗号化メッセージを表示するために、受信者は 1 回限りのパスコードを取得するか、Microsoft アカウントでサインインするか、Office 365 に関連付けられている職場または学校のアカウントでサインインできます。 受信者は暗号化された返事を送信することもできます。 暗号化されたメッセージを表示したり、暗号化された返信を送信したりするためにサブスクリプションは必要ありません。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーは、このサービスのメリットをどのように得られるでしょうか。

メッセージの送信者は、Office 365 Message Encryptionが提供する機密性の高いメールに対する追加の制御を利用できます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスはどれですか。

Microsoft 365 E3/A3/G3、Office 365 E3/A3/G3、Azure 情報保護プラン 1 は、ユーザーがOffice 365 Message Encryptionの恩恵を受ける権利を提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスはどのようにプロビジョニング/展開されますか?

管理者は、**メール フロー** ルール の下のExchange管理センターでOffice 365 Message Encryptionポリシーを作成および管理  >  **します**。 既定では、これらのルールはテナント内のすべてのユーザーに適用されます。 新しいOffice 365 Message Encryption機能の設定の詳細については、「[新しいメッセージ暗号化機能の設定](/office365/securitycompliance/set-up-new-message-encryption-capabilities)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得したテナントのユーザーにのみ、サービスを適用する方法はありますか。

管理者は、Office 365 Message Encryptionのメール フロー ルールを、ライセンスを持つユーザーにのみ適用する必要があります。 メール フロー ルールの定義の詳細については、「 [メール メッセージを暗号化するためのメール フロー ルールの定義](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)」を参照してください。

## <a name="office-365-advanced-message-encryption"></a>Office 365 Advanced Message Encryption

Office 365 Advanced Message Encryptionは、外部受信者に対してより柔軟な制御を必要とするコンプライアンス義務と暗号化された電子メールへのアクセスを顧客が満たすのに役立ちます。 高度なメッセージ暗号化を使用すると、管理者は機密情報の種類 (個人識別情報、財務 ID、正常性 ID など) を検出できる自動ポリシーを使用して組織外で共有される機密性の高い電子メールを制御したり、カスタム電子メール テンプレートを適用したり、セキュリティで保護された Web ポータルを介して暗号化された電子メールへのアクセスを期限切れにしたりして、保護を強化するためにキーワードを使用できます。 さらに、管理者は、アクセスをいつでも取り消すことで、安全な Web ポータルを通じて外部からアクセスする暗号化された電子メールをさらに制御できます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーは、このサービスのメリットをどのように得られるでしょうか。

メッセージの送信者は、高度なメッセージ暗号化によって提供される機密性の高い電子メールに対する追加の制御の恩恵を受けます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスはどれですか。

Office 365E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5コンプライアンス、Microsoft 365 E5/A5/G5情報保護およびガバナンスは、高度なメッセージ暗号化の恩恵を受ける権利をユーザーに提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスはどのようにプロビジョニング/展開されますか?

管理者は **、Exchange** の管理センターの [メール フロー ルール] の下で、高度なメッセージ暗号化ポリシーを作成および管理  >  **します**。 既定では、これらのルールはテナント内のすべてのユーザーに適用されます。 新しいメッセージ暗号化機能の設定の詳細については、「[新しいOffice 365 Message Encryption機能の設定](/office365/securitycompliance/set-up-new-message-encryption-capabilities)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得したテナントのユーザーにのみ、サービスを適用する方法はありますか。

管理者は、高度なメッセージ暗号化のメール フロー ルールを、ライセンスを持つユーザーにのみ適用する必要があります。 メール フロー ルールの定義の詳細については[、「Office 365でメール メッセージを暗号化するためのメール フロー ルールの定義](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)」を参照してください。

## <a name="communication-compliance"></a>通信コンプライアンス

Microsoft 365の通信コンプライアンスは、組織内の不適切なメッセージの検出、キャプチャ、修復アクションを実行することで、通信リスクを最小限に抑えるのに役立ちます。 組織内の内部および外部の電子メール、Microsoft Teams、またはサード パーティの通信をキャプチャする特定のポリシーを定義できます。 レビュー担当者は、適切な修復アクションを実行して、組織のメッセージ標準に準拠していることを確認できます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーは、このサービスのメリットをどのように得られるでしょうか。

コンプライアンススペシャリストは、通信コンプライアンスポリシーによって組織のコミュニケーションを監視することで、サービスのメリットを享受します。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスはどれですか。

Office 365E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5コンプライアンス、Microsoft 365 E5/A5/G5インサイダーリスク管理は、ユーザーがコミュニケーションコンプライアンスの恩恵を受ける権利を提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスはどのようにプロビジョニング/展開されますか?

管理者とコンプライアンススペシャリストは、Microsoft 365 コンプライアンス センターでコミュニケーション コンプライアンス ポリシーを作成します。 これらのポリシーは、組織内でレビュー対象となる通信とユーザーを定義し、通信が満たす必要があるカスタム条件を定義し、レビューを実行するユーザーを指定します。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得したテナントのユーザーにのみ、サービスを適用する方法はありますか。

管理者は、通信コンプライアンス ポリシーに含める特定のユーザーまたはグループを選択します。 グループを選択する際、グループ内の特定のユーザーを選択して、通信コンプライアンス ポリシーから除外することもできます。 通信コンプライアンス ポリシーの詳細については、「 [Microsoft 365 での通信コンプライアンスの概要](/microsoft-365/compliance/communication-compliance-configure)」を参照してください。

## <a name="insider-risk-management"></a>インサイダー リスク管理

インサイダー リスク管理は、組織内のリスクの高い活動を検出、調査、およびアクションを実行することで内部リスクを最小限に抑えるのに役立つMicrosoft 365のソリューションです。

カスタム ポリシーを使用すると、組織の悪意のある危険なアクティビティ (必要に応じて、ケースのエスカレートなど) を検出し、そのAdvanced eDiscoveryに対して対処できます。 組織内のリスク アナリストは、適切なアクションを迅速に実行し、ユーザーが組織のコンプライアンス基準に準拠していることを確認できます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーは、このサービスのメリットをどのように得られるでしょうか。

ユーザーは、アクティビティにリスクを監視させることでメリットを得ます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスはどれですか。

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5コンプライアンス、およびMicrosoft 365 E5/A5/G5インサイダーリスク管理は、ユーザーがインサイダーリスク管理の恩恵を受ける権利を提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスはどのようにプロビジョニング/展開されますか?

インサイダー リスク管理ポリシーは、Microsoft 365 コンプライアンス センターで作成し、ユーザーに割り当てる必要があります。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得したテナントのユーザーにのみ、サービスを適用する方法はありますか。

Microsoft 365 コンプライアンス センターでポリシーを作成する場合、[**ユーザーとグループの選択**] ページで[**ユーザーまたはグループを選択** してライセンスを受けたユーザーのみを選択する] を選択するか、すべてのユーザーがライセンスを取得している場合は、[**すべてのユーザーとメールが有効なグループ**] チェック ボックスをオンにします。 詳細については、「 [内部リスク管理の概要](/microsoft-365/compliance/insider-risk-management-configure)」を参照してください。

## <a name="conditional-access-policies"></a>条件付きアクセス ポリシー

条件付きアクセスは、シグナルを集めたり、意思決定を行い、組織のポリシーを適用するためにAzure Active Directoryが使用するツールです。 条件付きアクセスは、アイデンティティ主導の制御の中心です。 条件付きアクセス ポリシーは、最も単純な if-then ステートメントです。 ユーザーがリソースにアクセスする場合は、アクションを完了する必要があります。 例: 給与マネージャーは、給与計算アプリケーションにアクセスする必要があり、それにアクセスするために多要素認証を実行する必要があります。

### <a name="which-users-benefit-from-the-service"></a>サービスの恩恵を受けるユーザーはどれですか。

Enterprise Mobility + Security E3/A3、Microsoft 365 F3/E3/A3/ビジネスプレミアム、Azure Active Directory プレミアムプラン1のライセンスユーザーは、条件付きアクセスポリシーのメリットを享受できます。 Enterprise Mobility + Security E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft E5/G5 セキュリティ、およびAzure Active Directory プレミアムプラン 2 のライセンスユーザーは、ID 保護 (リスクベースの条件付きアクセス ポリシー) のメリットを得ることができます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーは、このサービスのメリットをどのように得られるでしょうか。

セキュリティ運用アナリストやセキュリティ担当者は、組織のポリシーをユーザーに適用する機能を持ち、企業コンテンツへのアクセスを許可する前に特定の基準を満たすことを要求することでメリットを得ます。 エンド ユーザーは、組織の資産を保護しながら、いつでもどこからでも作業にアクセスできることで、メリットを得られます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスはどのようにプロビジョニング/展開されますか?

既定では、テナント内のすべてのユーザーに対して、条件付きアクセス機能がテナント レベルで有効になっています。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得したテナントのユーザーにのみ、サービスを適用する方法はありますか。

特に ID 保護と条件付きアクセスでは、ユーザーをグループに含めるか、条件付きアクセス ポリシーに追加する必要があります。 条件付きアクセス ポリシーでは、ユーザーとグループの条件は必須です。 ポリシーで[ **すべてのユーザー]** または特定のユーザとグループを選択できます。 適切なライセンスを持つユーザーとグループのみを選択してください。 詳細については、「 [条件付きアクセス : 条件](/azure/active-directory/conditional-access/conditions)」を参照してください。

## <a name="advanced-audit"></a>高度な監査

Microsoft 365の高度な監査では、ユーザーおよび管理アクティビティの監査ログを 1 年間保持し、カスタム監査ログ保持ポリシーを作成して、他のMicrosoft 365 サービスの監査ログ保存を管理する機能を提供します。 また、調査やOffice 365管理アクティビティ API への高帯域幅アクセスのための重要なイベントへのアクセスも提供します。 詳細については、「 [Microsoft 365 の高度な監査](/microsoft-365/compliance/advanced-audit)」を参照してください。

アドオン SKU を使用して、10 年間の保存期間を有効にすることもできます。 アドオン SKU は 2021 年の初めから必要になります。

### <a name="which-users-benefit-from-the-service"></a>サービスの恩恵を受けるユーザーはどれですか。

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5コンプライアンス、Microsoft 365 E5/A5/G5電子情報開示および監査のライセンスユーザーは、高度な監査のメリットを享受できます。

高度な監査と 10 年間の監査ログ保持アドオンを持つライセンスユーザーは、10 年間の監査ログ保持の恩恵を受けることができます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーは、このサービスのメリットをどのように得られるでしょうか。

Microsoft 365 サービスのユーザー アクティビティに関連する監査レコードは最長 1 年間保持できるため、高度な監査のメリットがあります。 さらに、ユーザーのメールボックス内のアイテムにアクセスまたは読み取りが行われたときなど、高価値の監査イベントが記録されます。 詳細については、「 [Microsoft 365 の高度な監査](/microsoft-365/compliance/advanced-audit)」を参照してください。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスはどのようにプロビジョニング/展開されますか?

既定では、高度な監査は、Office 365またはMicrosoft 365 E5/A5/G5 サブスクリプションを持つすべての組織のテナント レベルで有効にされ、Azure Active Directory、Exchange、およびSharePointのアクティビティ (適切なライセンスを持つユーザーによって実行される) の監査ログの 1 年間の保持を自動的に提供します。 さらに、組織は監査ログの保持ポリシーを使用して、他のMicrosoft 365 サービスのアクティビティによって生成された監査レコードの保存期間を管理できます。 10 年間の監査ログ保存機能も、同じ保持ポリシーを使用して有効になります。 詳細については、「[監査ログ保持ポリシーを管理する](/microsoft-365/compliance/audit-log-retention-policies)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスを取得したテナントのユーザーにのみ、サービスを適用する方法はありますか。

監査ログの 1 年間の保存期間と重要なイベントの監査は、適切なライセンスを持つユーザーにのみ適用されます。 さらに、管理者は監査ログの保持ポリシーを使用して、特定のユーザーの監査ログの保持期間を短縮できます。

監査ログの 10 年間の保存期間は、適切なアドオン ライセンスを持つユーザーにのみ適用されます。 アドオン SKU は 2021 年の初めから必要になります。