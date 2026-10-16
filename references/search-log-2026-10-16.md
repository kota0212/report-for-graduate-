# 重点追加検索ログ（2026-10-16 JST）

網羅的レビューではない。検索サービスの全ヒット数は不安定・未取得のため記録しない。以下の候補数は**この作業で名前を明記して判定したもの**で、検索全体の母数ではない。DB検索UIと外部web検索のsite指定を区別する。全文未確認を採用実証へ昇格させない。

## 先行する資料監査

指定9ファイル、docs/overview.md、関連個別メモを確認。[不足分析](gap-audit-2026-10-16.md)を作成してから検索開始。GitHub現行をclone、旧ローカルの未コミット変更を維持。Drive29件の抽出テキストを取得・書誌を照合（[一覧](drive-audit-2026-10-16.md)）。全文取得は全頁精読を意味しない。旧文献の分析を継承し、L-003の数値と新候補を優先監査。

## 実行した検索と処理

|経路・実検索式／URL|確認した候補・判定|アクセス・範囲|
|---|---|---|
|Chrome Computer Use、Google Scholar：`"generative AI" "secondary" "unassisted"`|初頁10結果を表示確認。Nakamura理論、Bastani旧版、Contractor大学、Giray枠組み、Sari論説、Chen multitasking、Mekkaeo言語、Wu/Ouyangメタ分析、Yajee枠組み、Alam学位論文を候補境界として確認|BastaniはL-001同一研究、Nakamuraは公式ページを補助閲覧・未採用、大学/論説/本文未監査等は主比較に不採用。初頁以降・全件exportなし。Scholarを使えたと報告できる範囲はこの1検索|
|web：`"Making AI Tutoring Productive" "35621"`、`"Making AI Tutoring Productive" site.edworkingpapers.com`（実際には最初の検索後、`site.edworkingpapers.com`を含む検索も送信）|N-001 1研究を同定、NBER/EdWorkingPaperは異版候補|NBER本文ページweb403、Chrome公式ページ読取成功、公式PDFはcurl200で72頁取得|
|web：`"Enhancing School Students" "10133"`、`"Enhancing School Students’ Self-Regulated Learning" Fütterer`|L-029 1研究、出版社・大学・ERIC派生書誌|Springer掲載HTML/PDF確認、Crossref公式API照合、Drive保存確認|
|web：`"The impact of GenAI on learning outcomes" Han Peng Liu`、DOI/ScienceDirect原典open|L-002既登録1件|抄録・書誌確認、詳細取得403。全文未確認を維持。メタ分析統合値を確定根拠に採らない|
|web：`"Effects of integrating generative AI, teacher, and peer feedback"`、Chromeで出版社DOI fullへ|L-006既登録1件|web403、ChromeはGet Access。著者・2026-01-09・抄録・データ非公開を確認。本文/図表はアクセス不可、購入や著者への連絡なし|
|web：`site:eric.ed.gov generative AI secondary delayed learning`、ERIC query URL open|この検索から新たな採用0件。後に理論検索でERIC Kapur2010を確認|ERIC直接検索openはアクセス不能。ERIC全件検索を実施済みとはしない|
|web：`site:jstage.jst.go.jp 生成AI 高校 自己調整 学習`|藤原prompt支援（専門学校）、中学技術科活用報告、他の抄録等を発見、追加採用0|専門学校は直接対象外、中学実践は全文方法・独立評価未監査で候補。J-STAGE内の全件直接検索なし|
|web：`"The Effects of Prompt Scaffolding on Learning to Write Arguments" site:repository.isls.org`|L-027 1件|公式ISLSのDOI・著者・年・短報pp.1502–1505を照合。新たな公式PDFcurlは500、既存Drive本文で方法結果確認|
|web：`"Enhancing students’ authentic mathematical" Lin 20 34`|L-020 1件|出版社・大学書誌を照合。小5なので間接。本文全体群間非有意と抄録不一致を保持|
|web：`site:cir.nii.ac.jp 生成AI 高校 数学 名知`|図書、大学数学FB、教員志望意識、高校探究の問い/FB等を発見。新規採用0|学校効果比較との適合・独立成果未確認で保留。CiNii直接全件検索なし|
|web：`site:mext.go.jp 生成AI ガイドライン Ver.2.0 2026`|L-012既登録の公式案内を再確認|確認した案内は2024-12-26 Ver2.0。未確認の新通知やサービス規約が存在しないとは断定しない|
|web：`"productive failure" Kapur 2008 study secondary mathematics`|Kapur2008、追跡先ERIC EJ901889（2010数学）2候補|出版社/ERIC抄録のみ、原典方法未監査・保存未実施。本文数に加えない|
|web：`"retrieval practice" Karpicke Blunt 2011 science learning`|Karpicke & Blunt2011 1候補|PubMed・大学PDF案内確認、個人利用限定表記。全文実験未監査で保存・採用保留|
|web：`"pretesting" "middle school" learning Pan 2020`、`"pretesting" Pan Carpenter 2023 review site:link.springer.com`|L-030（Pan/Carpenter2023）、Pan/Rivers2023（候補）|L-030掲載PDF40頁の関連節確認・CC BY原本保存。後者は本文未監査|
|web：`"worked examples" "fading" Renkl Atkinson 2003`|Renkl/Atkinson2003、Atkinson/Renkl/Merrill2003ほか|原典・理論の候補追跡。二次説明だけから効果採用しない。fading直接GenAI効果未確立|
|web：`"One Click Away" "Khanmigo" Oreopoulos Low`|N-002 1研究|公式EdWorkingPaper・NBER PDF53頁方法結果を確認、公開フォルダへの保存保留|
|web：`"generative AI alone may not be enough" Chen 2509.16778`|Chen et al.2025 1研究候補|arXiv原典抄録確認。大学の間接根拠、本文未監査、登録・保存なし|

web検索で出たWikipedia・reddit・ブログ・商用要約は根拠に使用しない。研究を知る入口と原典での確認を分ける。上記はツール送信式を残すもので、絞り込みをすべて各DBで実行したという記録ではない。

## 選定結果（研究・文献・ファイルを別集計）

- 既存台帳19件を記録監査。開始時Drive29PDFは28異なる資料に対応（Tutor CoPilot2ファイルを研究単位で1件）。うち15既登録＋13未登録。開始時既登録4件の対応原本なし。
- 未登録13件のうち3一次研究をL-020/024/027として追加。残10件は高等教育背景・政策・枠組み等で、今回の中核比較へ新規登録しない。
- 外部から今回新たに本文を確認した実証はL-029、N-001、N-002の3研究。うちL-029のみ原本保存まで完了し正式登録。N-001/002は保存条件未解決で候補記録。前回Driveファイル数を新規研究数に含めない。
- L-030は理論レビュー1件を登録、一次研究数に含めない。したがって登録19→24（一次研究4追加＋理論レビュー1追加）、Drive29→31（新規PDF2）。既存から継承した本文確認16＋新規5＝登録文献中の分析本文確認21。今回Driveで撤回原論文のテキストが取得できても、L-014を研究精読済みの計数には加えない。
- 文献分類はA20/B3/C1。Aは限定使用候補を含む管理区分であり「強い直接証拠20件」ではない。N-001/002は別枠。

## 残す制限

検索の網羅性・飽和未達、DB別の全ヒット母数なし、独立二重選定なし。全原典の最新訂正・撤回網羅確認、L-002/006本文、fading・援助要請・認知負荷の理論原典、主要研究のAI禁止条件、旧iCloudと全階層の原本照合、保存保留2WPが残る。書込拒否・安全性チェック拒否は発生していない。アクセス制約・git取得失敗を安全性拒否と混同しない。

## GitHub送信時の認証エラー

27ファイルのローカルコミット `ca2be5c` 後、git pushは全変更ファイルを対象に失敗した。返却エラー：`remote: Permission to kota0212/report-for-graduate-.git denied to vexum-kota.` および `fatal: unable to access 'https://github.com/kota0212/report-for-graduate-.git/': The requested URL returned error: 403`。ファイル内容・安全性審査による拒否ではなく、仕事用Git資格情報の認証先相違。元のユーザー変更・共有権限は変更せず、接続済みの個人GitHubアカウントを明示選択した正規コネクタで指定リポジトリへのブランチ作成が成功した。以後のcommit/tree反映とPRの結果は終了報告を参照。権限拡張や安全性チェックの迂回はしていない。
