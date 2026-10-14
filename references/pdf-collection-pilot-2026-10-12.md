# 英語実証研究PDF収集：5件の試行（2026-10-12）

指定ブランチ `research/genai-literature-2026-10-12` の707a4ac、origin/mainの8180cca、README・AGENTS・AI_CONTEXT・正本文献台帳・既存検索ログを確認。指定ブランチ14件と、ローカル旧台帳10件の題名・DOIを重複照合。Bastani／Kestinは既存として除外し、Pardosの2023試行版は2024掲載研究と重複登録しない。ローカル旧台帳と新台帳にはL-001等のID衝突があるため、旧ファイルは変更せず、新規は指定ブランチに従ってL-015–019を付与。旧台帳のID統合は今回未実施。

MacのComputer UseでFinderのiCloud Drive/ゼミ/卒論にアクセス。既存PDF10件と「使える」「使えない」を確認し、「未評価」を作成。既存資料の変更・移動・上書きなし。4件を排他的な新規ファイル作成で保存し、元データとのSHA-256一致・PDFページ読込を検証。iCloud上のローカル実体への保存は成功。Apple側の同期完了は別途未確認。

Google Scholarの検索 `generative AI learning randomized controlled trial hints` は通常アクセス成功、CAPTCHAや自動アクセス制限は表示されなかった。追加探索は一般Web検索、出版社、arXiv、著者大学公開稿。Scholar迂回は未実施。

検索語：`ChatGPT hints learning gains Pardos Bhandari 2024 randomized`、`generative AI unassisted post test learning Kazemitabaar 2023 2024`、`generative AI learning cognitive ease Stadler experiment 2024 Darvishi Fan self regulated learning`、`Lee 2024 guidance based ChatGPT learning higher order thinking self regulation chatbot`。全ヒット数・網羅性は記録せず。

## 取得と制約

- L-015：ChromeのPLOS Download PDFから取得。
- L-016：ChromeのSpringer Nature Download PDFから取得。
- L-017：arXivブラウザPDF取得はタイムアウト。正規の著者大学公開URLから通常HTTPS取得成功。認証制限回避ではない。
- L-018：PHBern大学サイトの公開PDFを通常HTTPS取得。巻年2025と保存PDFの2024 online-first表記を区別。
- L-019：Augsburg大学リポジトリ接続タイムアウト（ブラウザ／通常HTTPS）、ドイツ国立図書館経路は証明書検証エラー、ScienceDirect HTMLは403。証明書検証を無効化せず、未取得で記録。必要なら本人が[大学ページ](https://opus.bibliothek.uni-augsburg.de/opus4/frontdoor/index/index/docId/114673)の114673.pdfを通常ブラウザで手動取得し、`L-019_Stadler_2024_CognitiveEase.pdf`として未評価に保存する。安全警告が出る場合は越えない。

## 個別記録

- [L-015 — ChatGPT-generated help produces learning gains equivalent to human tutor-authored help on mathematics skills](../sources/usable/L-015-pardos-math-help.md)
- [L-016 — Empowering ChatGPT with guidance mechanism in blended learning: effect of self-regulated learning, higher-order thinking skills, and knowledge construction](../sources/usable/L-016-lee-guidance-chatgpt.md)
- [L-017 — Studying the effect of AI Code Generators on Supporting Novice Learners in Introductory Programming](../sources/usable/L-017-kazemitabaar-code-novices.md)
- [L-018 — Beware of metacognitive laziness: Effects of generative artificial intelligence on learning motivation, processes, and performance](../sources/usable/L-018-fan-metacognitive-laziness.md)
- [L-019 — Cognitive ease at a cost: LLMs reduce mental effort but compromise depth in student scientific inquiry](../sources/usable/L-019-stadler-cognitive-ease.md)

PDF原本、抽出全文、本文画像は公開GitHubへコミットしない。本文部分確認を精読・採用と扱わない。AIなしテストは明記確認／未確認を区別する。5件の試行で終了し、横断分析・研究結論・「使える」「使えない」への分類は未実施。

## 後続評価へのリンク（2026-10-14）

本文評価は[今回の原典監査](full-text-audit-2026-10-14.md)で補完。上記は取得試行当時の状態。現在の分類・確認件数は[台帳](literature-matrix.md)を参照し、原本の移動履歴とは区別する。
