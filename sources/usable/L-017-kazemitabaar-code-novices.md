# L-017：Studying the effect of AI Code Generators on Supporting Novice Learners in Introductory Programming

[台帳](../../references/literature-matrix.md) · [横断レビュー](../../docs/literature-review.md) · [確認ログ](../../references/full-text-audit-2026-10-14.md)

## 1. 書誌と確認状態

- 著者：Majeed Kazemitabaar; Justin Chow; Carl Ka To Ma; Barbara J. Ericson; David Weintrop; Tovi Grossman
- 年・掲載：2023。Proceedings of the 2023 CHI Conference on Human Factors in Computing Systems（23頁の大学公開稿。論文番号は今回未照合）
- DOI：https://doi.org/10.1145/3544548.3580919
- [確認原典](https://terpconnect.umd.edu/~weintrop/papers/Kazemitabaar_et_al_CHI_2023.pdf)
- 判定：A／暫定使用候補（2026-10-14）。関連度：高（L-016／018／019は大学、L-015は成人から学校への間接的根拠）。
- 信頼性：中（ペア内無作為化、AIなし評価明示。ただし脱落・評価課題選別）。査読付き学術誌／L-017はCHI会議論文。使用候補は正式採用を意味しない。
- 本文確認済み：大学公開稿23頁。§4.1.3–4.2.1（PDF p.6）、§5.1–5.3（pp.8–11）、§6–7（pp.12–15）。原文の二段組を踏まえ節で引用。 補足資料全監査・全引用追跡の完了ではない。
- 原本PDF・抽出本文はGitに保存しない。2026-10-12の部分確認／未評価を今回の評価で更新。iCloud原本の分類移動は行っていない。

## 2. 目的・対象・方法

初学者のPython課題遂行・AIなしの技能・1週間後保持に対するコード生成の影響を調べる。

北米2都市のキャンプから10–17歳。90人開始、69人完遂のみ分析（Codex33／Baseline36）、21人脱落。Scratch事前能力でペア化しペア内無作為割付。自然言語コード生成は作成課題で許可、その後手動修正・選択問題。両群に人間の採点・徐々に直接的になるヒント。直後（訓練翌日）・1週後はAI、Python文書、提出後FBを禁止。t検定・効果量、トピック比較α=.01（Bonferroni）。

## 3. 著者が報告する結果

§5.1：訓練課題完遂90.9%対79.0%、p=.006、d=.68。§5.2：AIなし直後作成61.3%対62.9%、p=.838。保持作成59.1%対49.8%、p=.262、修正47.5%対34.8%、p=.092、いずれも全体で非有意。保持時の作成エラー増も報告し、未着手率差が関わる可能性。§5.3は高Scratch群の利益を探索的に示唆。

## 4. 限界と批判的評価（分析者の判断）

完遂者分析で脱落バイアス、キャンプ参加者・男子多め・端末保有者。到達50%未満トピックの評価課題を除外しており介入後の到達差に依存する選別。多数の比較・小標本・探索的下位群。修正／人間FBが共通のため、無支援コード生成だけの試験ではない。評価は訓練内容範囲で遠転移なし。

## 5. 横断比較・用途（設計候補、AIによる解釈）

生成後に手動で修正・説明する課題と支援なし評価を組み合わせる候補。完成コードの提供が常に学習を阻害するという一般則への留保。 [7観点比較・要件と強さ](../../docs/literature-review.md)に統合。主観尺度、成果物、自力技能、保持・転移を別指標として抽出する。

## 6. プレテストの扱い

Scratch事前テストは割付調整と下位群分類用。Pythonの同一問題前後差ではなく、プレテストによる学習効果の操作もない。L-005の数学低知識群と尺度・対象が異なる。

## 7. APA第7版候補

Kazemitabaar, M., Chow, J., Ma, C. K. T., Ericson, B. J., Weintrop, D., & Grossman, T. (2023). Studying the effect of AI code generators on supporting novice learners in introductory programming. In *Proceedings of the 2023 CHI Conference on Human Factors in Computing Systems*. Association for Computing Machinery. https://doi.org/10.1145/3544548.3580919

巻号・論文番号の未確認は上記に残す。正式提出時は原典の最終書誌と照合する。

## 8. 残課題・再判定

上記の未確認条件・統計表記・評価時AI制約を優先確認。学校・教科が確定したら適用範囲を再評価する。訂正／撤回／最終版変更時に再判定。確認日2026-10-14、日本時間。著者の結果と設計解釈を混同しない。
