# Awesome ISO 27001 ISMS Tools

[English](README.md) | 日本語

**ISO/IEC 27001 に基づく ISMS（情報セキュリティマネジメントシステム）**の導入・運用に役立つ、OSS ツール・テンプレート・AI 連携のキュレーションリストです。

> **重要:** ISO/IEC 27001 の規格本文（要求事項と附属書A）は著作権で保護され、ISO や各国の規格団体が有償で提供しています（日本では日本規格協会の JIS Q 27001）。GitHub では正規には入手できません。このリストに載せているのは、規格の導入を助けるツール、テンプレート、ツールキットです。購入した規格本文を公開リポジトリにコミットしないでください。
>
> 説明は各リポジトリの GitHub 上の説明文に基づきます。内容とライセンスは未検証です。テンプレートを再利用する前にライセンスを確認してください。

## 目次

- [GRCプラットフォーム（複数フレームワーク対応）](#grcプラットフォーム複数フレームワーク対応)
- [ISMS専用ツール](#isms専用ツール)
- [テンプレートとツールキット](#テンプレートとツールキット)
- [コンプライアンス・アズ・コード / OSCAL](#コンプライアンスアズコード--oscal)
- [AI・LLM・MCP](#aillmmcp)
- [マッピングデータ](#マッピングデータ)
- [関連リスト](#関連リスト)
- [補足](#補足)

## GRCプラットフォーム（複数フレームワーク対応）

- [intuitem/ciso-assistant-community](https://github.com/intuitem/ciso-assistant-community) ![stars](https://img.shields.io/github/stars/intuitem/ciso-assistant-community?style=flat-square) - リスク管理、コンプライアンス、監査のGRCプラットフォーム。ISO 27001 を含む200以上のフレームワークと管理策マッピングに対応。MCP対応。
- [trycompai/comp](https://github.com/trycompai/comp) ![stars](https://img.shields.io/github/stars/trycompai/comp?style=flat-square) - AIネイティブなコンプライアンスプラットフォーム（Vanta / Drata の代替）。SOC 2、ISO 27001、GDPR。
- [getprobo/probo](https://github.com/getprobo/probo) ![stars](https://img.shields.io/github/stars/getprobo/probo?style=flat-square) - SOC 2、GDPR、ISO 27001 向けのOSSソリューション。
- [bmarsh9/gapps](https://github.com/bmarsh9/gapps) ![stars](https://img.shields.io/github/stars/bmarsh9/gapps?style=flat-square) - セキュリティコンプライアンスプラットフォーム。SOC 2、CMMC、ASVS、ISO 27001、HIPAA、NIST CSF など。
- [theopenlane/core](https://github.com/theopenlane/core) ![stars](https://img.shields.io/github/stars/theopenlane/core?style=flat-square) - SOC 2、GDPR、ISO 27001、NIST 800-53 向けのOSSコンプライアンス自動化。
- [LeeMangold/OpenGRC](https://github.com/LeeMangold/OpenGRC) ![stars](https://img.shields.io/github/stars/LeeMangold/OpenGRC?style=flat-square) - 中小規模のセキュリティチーム向け自社ホストGRC。リスク、管理策、監査、ベンダーリスク、インシデント対応。
- [UnicisTech/unicis-platform-ce](https://github.com/UnicisTech/unicis-platform-ce) ![stars](https://img.shields.io/github/stars/UnicisTech/unicis-platform-ce?style=flat-square) - OSSのGRCプラットフォーム（Vanta / Drata の代替）。ISO 27k、GDPR、SOC 2、NIST。
- [strongdm/comply](https://github.com/strongdm/comply) ![stars](https://img.shields.io/github/stars/strongdm/comply?style=flat-square) - SOC 2 中心のコンプライアンス自動化フレームワーク（テンプレート、PDF生成）。トピックに ISO 27001 を含む。

## ISMS専用ツール

- [coolstartnow/isms-builder](https://github.com/coolstartnow/isms-builder) ![stars](https://img.shields.io/github/stars/coolstartnow/isms-builder?style=flat-square) - 自社ホストのISMS。ISO 27001、NIS2、GDPR、BSI IT-Grundschutz。
- [moag1000/Little-ISMS-Helper](https://github.com/moag1000/Little-ISMS-Helper) ![stars](https://img.shields.io/github/stars/moag1000/Little-ISMS-Helper?style=flat-square) - 複数フレームワーク（ISO 27001:2022、BSI、NIS-2、DORA、GDPR、TISAX）対応のOSS ISMS。93の附属書A管理策、リスクエンジン、改ざん検知できる監査証跡。

## テンプレートとツールキット

- [PehanIn/ISO-27001-2022-Toolkit](https://github.com/PehanIn/ISO-27001-2022-Toolkit) ![stars](https://img.shields.io/github/stars/PehanIn/ISO-27001-2022-Toolkit?style=flat-square) - ISO 27001:2022 のツールキット。テンプレート、チェックリスト、ポリシー。
- [PeterGeelen/ISO27001](https://github.com/PeterGeelen/ISO27001) ![stars](https://img.shields.io/github/stars/PeterGeelen/ISO27001?style=flat-square) - ISMS導入用のテンプレートと作業文書（Excel、PowerPoint、Visio）。
- [sayu-gtss/ISO-27001-2022-Toolkit](https://github.com/sayu-gtss/ISO-27001-2022-Toolkit) ![stars](https://img.shields.io/github/stars/sayu-gtss/ISO-27001-2022-Toolkit?style=flat-square) - ポリシーテンプレート、リスク評価マトリクス、適用宣言書（SoA）、インシデント対応計画、監査チェックリスト。
- [Ankit-Uniyal/iso-27001-isms-toolkit](https://github.com/Ankit-Uniyal/iso-27001-isms-toolkit) ![stars](https://img.shields.io/github/stars/Ankit-Uniyal/iso-27001-isms-toolkit?style=flat-square) - ギャップ評価、リスク登録簿テンプレート、全93管理策のSoA、導入ロードマップ。
- [easy-standart/iso-27001-guide](https://github.com/easy-standart/iso-27001-guide) ![stars](https://img.shields.io/github/stars/easy-standart/iso-27001-guide?style=flat-square) - 実践ガイド。要求事項、附属書A管理策、チェックリスト、ISMSテンプレート。
- [ciphermichael/isms](https://github.com/ciphermichael/isms) ![stars](https://img.shields.io/github/stars/ciphermichael/isms?style=flat-square) - 文書テンプレート付きのISO 27001導入ガイド。
- [cwu2021/ISMS](https://github.com/cwu2021/ISMS) ![stars](https://img.shields.io/github/stars/cwu2021/ISMS?style=flat-square) - ISO 27001 関連のリソース。
- [umarmusman/ISO27K1-Compliance_Documents](https://github.com/umarmusman/ISO27K1-Compliance_Documents) ![stars](https://img.shields.io/github/stars/umarmusman/ISO27K1-Compliance_Documents?style=flat-square) - 架空のフィンテック企業向けのISO 27001:2022文書例。
- [mr-r3b00t/iso27001-sample](https://github.com/mr-r3b00t/iso27001-sample) ![stars](https://img.shields.io/github/stars/mr-r3b00t/iso27001-sample?style=flat-square) - 架空の組織向けのISMS例（Claudeで作成）。

## コンプライアンス・アズ・コード / OSCAL

- [oscal-compass/compliance-trestle](https://github.com/oscal-compass/compliance-trestle) ![stars](https://img.shields.io/github/stars/oscal-compass/compliance-trestle?style=flat-square) - CIとNISTのOSCAL標準を使ったコンプライアンス・アズ・コード。
- [grcwarlock/compliance-as-code](https://github.com/grcwarlock/compliance-as-code) ![stars](https://img.shields.io/github/stars/grcwarlock/compliance-as-code?style=flat-square) - コンプライアンスエンジニア向けのエージェントスキル、エージェント、参照コネクタ。SOC 2、ISO 27001、NIST 800-53。
- [sw30labs/oscal-cac-playgd](https://github.com/sw30labs/oscal-cac-playgd) ![stars](https://img.shields.io/github/stars/sw30labs/oscal-cac-playgd?style=flat-square) - OSCALをコンプライアンス・アズ・コードとして扱うCLI。ファイルの説明、修正案、LLMによる差分レビュー。

## AI・LLM・MCP

- [Sushegaad/Claude-Skills-Governance-Risk-and-Compliance](https://github.com/Sushegaad/Claude-Skills-Governance-Risk-and-Compliance) ![stars](https://img.shields.io/github/stars/Sushegaad/Claude-Skills-Governance-Risk-and-Compliance?style=flat-square) - GRC向けClaudeスキル。ISO 27001、SOC 2、GDPR、NIST CSF、ISO 42001 など。
- [GRCEngClub/claude-grc-engineering](https://github.com/GRCEngClub/claude-grc-engineering) ![stars](https://img.shields.io/github/stars/GRCEngClub/claude-grc-engineering?style=flat-square) - 証跡収集、SCFクロスウォーク、複数フレームワークのギャップレポート、OSCALワークフロー用のClaude Codeプラグイン。
- [kriss-b/llm-iso27001](https://github.com/kriss-b/llm-iso27001) ![stars](https://img.shields.io/github/stars/kriss-b/llm-iso27001?style=flat-square) - LLMエージェントが運用する前提で設計された ISO 27001（+ 42001 + NIS2）のISMSフレームワーク。
- [Sushegaad/MCP-Server-for-ISO27001](https://github.com/Sushegaad/MCP-Server-for-ISO27001) ![stars](https://img.shields.io/github/stars/Sushegaad/MCP-Server-for-ISO27001?style=flat-square) - ClaudeにISO 27001:2022のISMSを持たせるMCPサーバー。ギャップ評価、リスク、ポリシー、証跡、監査。ローカルの暗号化SQLiteを使用。
- [verifywise-ai/verifywise](https://github.com/verifywise-ai/verifywise) ![stars](https://img.shields.io/github/stars/verifywise-ai/verifywise?style=flat-square) - AIガバナンスとLLM評価のプラットフォーム（EU AI Act、ISO 42001、NIST AI RMF）。

## マッピングデータ

- [microsoft/data-protection-mapping-project](https://github.com/microsoft/data-protection-mapping-project) ![stars](https://img.shields.io/github/stars/microsoft/data-protection-mapping-project?style=flat-square) - データ保護・プライバシー規制のマッピング（GDPR、ISO 27001/27002/27701 など）。**アーカイブ済み。**

## 関連リスト

- [theopenlane/awesome-compliance](https://github.com/theopenlane/awesome-compliance) ![stars](https://img.shields.io/github/stars/theopenlane/awesome-compliance?style=flat-square) - コンプライアンス関連のリソース、ライブラリ、ツール集。
- [awesome-requirements-system-ai](https://github.com/shvyac/awesome-requirements-system-ai) - StrictDoc、Doorstop、AIで要求ツリー（規格の条項を要求として管理するなど）を扱う。

## 補足

- 日本語のISMSテンプレートやJIS Q 27001関連のリソースは、GitHubの検索では見つかりませんでした（2026年10月時点）。
- AI関連の多くは新しいプロジェクトです。利用前に成熟度を確認してください。

## コントリビュート

プルリクエスト歓迎です。1行に1エントリ、短い説明を付けて追加してください。
