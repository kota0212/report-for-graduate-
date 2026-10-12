# 検索・検証ログ：2026-10-12

## 検索の位置づけ

- 目的：学校教育での生成AI学習支援の促進／阻害条件を抽出する。
- 対象：原則2022～2026年、英語・日本語、学習実証・レビュー・必要な理論と政策。
- 上限20件、実際に登録14件。検索で出た全資料を登録したわけではない。全ヒット数・全候補の重複除去母数は取得せず、PRISMA件数を生成しない。
- Google Scholar：`https://scholar.google.com/scholar?q=generative+AI+school+learning+guardrails` の取得を試したが、このツールではアクセス不可。直接検索結果は未取得。以後は一般Web検索で学術候補を探し、原典サイト・Crossref・著者公開稿を照合。
- 既存台帳0件、sourcesは分類READMEのみ。DOI・題名・著者・年を照合し同一論文の版は1IDに統合。BastaniのSSRN版、Kestinの旧題版を追加IDにはしない。
- 研究承認：README、AGENTS、AI_CONTEXT、research-planで未確認。本人の今回提示を作業基準にしたが正式承認に昇格しない。

## 実行した主要検索式（一般Web検索）

検索日はいずれも2026-10-12。ヒット総数は取得不可。複数検索エンジンを使い、原典による照合を優先した。

| 検索式 | 目的・結果 |
|---|---|
| Bastani 2025 Generative AI without guardrails can harm learning PNAS | L-001の掲載版・訂正を確認 |
| Han 2025 impact GenAI learning outcomes | L-002、書誌はCrossref、本文未取得 |
| Lin Tan 2025 systematic review K–12 | L-003、Crossref抄録と書誌を確認 |
| Tutor CoPilot Human-AI scaling expertise paper authors 2025 | L-004、arXiv初版2024・改訂2025を区別 |
| Tutor CoPilot site:openreview.net | 採択版を確認できず。査読済みとしない |
| A Large Scale Randomized Control Trial Showing LLM Generated Feedback authors | L-005、ACMと著者公開稿 |
| 2026 middle school LLM feedback randomized trial teacher peer feedback | L-005／006を照合 |
| 那知 田中 2025 高校 数学 生成AI 誤答 | 著者候補の表記に誤り、正しくは名知 |
| 誤りを含む生成AIの回答 那知 | J-STAGEでL-007を特定、著者名訂正 |
| generative AI tutoring randomized trial learning Kestin 2025 scientific reports | L-008原典 |
| generative AI secondary students text revision motivation positive emotions feedback | L-009、所属研究機関抄録 |
| A Systematic Review of Generative AI in K–12 Abstract | L-003、L-010の候補を照合 |
| The effect of ChatGPT learning performance higher-order thinking 2025 Wang Fan | L-014撤回を発見、根拠から除外 |
| site:mext.go.jp 初等中等教育 生成AI ガイドライン Ver.2.0 2024 | L-012公式PDF |
| site:unesco.org guidance generative AI education research 2023 Miao Holmes | L-013公式情報 |
| The Power of Feedback Hattie Timperley 2007 77 81 112 | L-011出版社書誌、大学公開PDF |

## 取得経路と制限

| ID | 確認経路 | 取得制限／注意 |
|---|---|---|
| L-001 | PNAS掲載HTML、著者公開PDF、Crossref、PNAS訂正情報 | PMCはreCAPTCHA、正規のPNAS原典で確認。公開PDFはScratchで参照のみ |
| L-002 | 出版社検索抜粋、Crossref API（著者・巻48・100714・2025） | ScienceDirect本文403。API再取得429もあり。最初の成功応答で書誌照合 |
| L-003 | Crossref APIの書誌と登録抄録、MDPI検索情報 | MDPI本文429／403。抄録まで |
| L-004 | arXiv abs、v1/v2 HTML。分析対象v2 | 初版2024／改訂2025。査読採択は未確認 |
| L-005 | ACM DOI、公式Full Research Papers一覧、Crossref、著者のFoL26ページから公開Drive採択稿 | ACM本文403。公開Driveの通常ダウンロードで12ページ本文取得。姓名・人数表記要確認 |
| L-006 | 出版社書誌、Crossref、HKMUの著者研究情報抄録 | Taylor & Francis本文403。巻号／最終ページ未照合 |
| L-007 | J-STAGE書誌・6ページPDF、p.74画像照合、著者大学情報 | Crossref404でもJ-STAGE公式DOIを優先。査読方式・統計表記要確認 |
| L-008 | Scientific Reports HTML、Crossref | 固定ページなし、節で引用 |
| L-009 | Leibniz IPN著者機関の抄録・書誌、Crossref | ScienceDirect本文未取得。Liebenow/Steinbachのミドルネームは機関情報で照合 |
| L-010 | Frontiers掲載HTMLとCrossref | 英語限定レビュー、検索式・選別件数要監査 |
| L-011 | SAGE検索書誌、大学公開の掲載PDF | SAGE本文は取得失敗、大学公開版を読む |
| L-012 | 文部科学省公式33ページPDF | 政策資料、実験論文として数えない |
| L-013 | UNESCO publication紹介とUNESDOC書誌ページ | 冊子本文未取得、公式紹介だけ |
| L-014 | Crossrefの撤回済み書誌、出版社の撤回通知（2026-04-22、7月2日更新） | 原論文本文を確認済みとしない |

アクセス制限の解除、CAPTCHA回避、学内認証の代理取得は実施していない。著作権PDF・HTML全文・個人情報・調査回答はGitHubへ保存しない。保存するのは書誌と日本語による分析。

## DOI・URL検証の範囲

原典サイトまたはCrossrefのDOI登録で、題名・著者・掲載情報の一致を照合した。本文URLが403になる場合、DOIが誤っているとは決めつけない。全DOIのリダイレクト先へのHTTP成功を保証したわけではない。L-005の姓名とL-006の最終巻号ページは保留し正式APA一覧から除いた。DOI未確認の政策資料へ架空のDOIを付与しない。

## 追加検索キーワード（次回実行用、未実行）

- `(generative AI OR large language model) AND (secondary school OR K-12) AND (unassisted test OR retention OR transfer)`
- `(Socratic tutoring OR graduated hints OR scaffolding) AND LLM AND (randomized OR experiment)`
- `AI tutoring AND (prior knowledge OR adaptive feedback OR help seeking OR self regulated learning)`
- `generative AI AND (cognitive offloading OR overreliance) AND school students`
- `teacher AI copilot AND (workload OR feedback verification OR educational equity)`
- `生成AI 学習支援 中学生 高校生 自力解答 遅延テスト`
- `生成AI 数学 ヒント 段階的支援 誤概念 批判的思考`
- `生成AI 教師 フィードバック 理解度 自己調整学習 依存`
- CiNii／J-STAGE／ERICで上記語を直接検索し、日本語実践・学校段階・2026年の追加研究を補う。

## 次の監査

本文未取得5件、L-005の正式姓名、L-006最終書誌、L-007統計表記、L-010検索過程を優先。撤回研究がレビューに含まれるか確認する。新規文献はL-015以降、DOI重複を確認し同じ原典の改訂版は既存IDを更新する。
