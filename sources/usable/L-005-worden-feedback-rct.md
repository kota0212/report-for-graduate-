# L-005：A Large Scale Randomized Control Trial Showing LLM Generated Feedback Helps Low-Knowledge Middle School Math Students with Short-Term Learning

[文献総合ページへ戻る](../../references/index.md) · [台帳](../../references/literature-matrix.md) · [APA一覧](../../references/apa-reference-list.md)

## 1. 基本書誌情報

- 文献ID：L-005
- 正式タイトル：A Large Scale Randomized Control Trial Showing LLM Generated Feedback Helps Low-Knowledge Middle School Math Students with Short-Term Learning
- 全著者（確認表記）：Eamon Worden; Luca Dang; Wen-Chiang Ivan Lim; Sarah Miller; Jiayi Zhang; Aaron Haim; Adam Sales; Ashish Gurung; Neil Heffernan
- 発行年：2026
- 掲載誌・媒体：Proceedings of the Thirteenth ACM Conference on Learning @ Scale, pp. 361–372
- DOI：https://doi.org/10.1145/3774398.3811594
- 原典URL：https://doi.org/10.1145/3774398.3811594
- 査読状況：ACM L@S公式のFull Research Papers採択一覧・著者公開採択稿を確認（会議査読）。
- 原本：公開原典を参照。PDF本文はこのリポジトリに保存しない。iCloud資料を読んだ／移動したことを意味しない。
- 採用判定：A：使用候補／使える（2026-10-12）
- 研究への関連度：高
- エビデンス信頼性：中（RCT、人数表記等に要確認）

### APA第7版

**書誌情報要確認：次の表記は確認前の候補で、正式コピー一覧には未収録。**

Worden, E., Dang, L., Lim, W.-C. I., Miller, S., Zhang, J., Haim, A., Sales, A., Gurung, A., & Heffernan, N. (2026). A large scale randomized control trial showing LLM generated feedback helps low-knowledge middle school math students with short-term learning. In *Proceedings of the Thirteenth ACM Conference on Learning @ Scale* (pp. 361–372). Association for Computing Machinery. https://doi.org/10.1145/3774398.3811594

本文内引用例：要約は「(Worden et al., 2026)」。文章中では著者名を主語にして年を括弧に置く。3人以上は最初から第一著者＋et al.、2人は両著者を示す。直接引用には確認済みページまたは節・段落を追加する。未確認のページは付けない。日本語文献は日本語の姓名表記を維持する。

## 2. 研究概要

### 背景・目的・研究課題

AIフィードバックの無説明群に対する効果、教師作成との比較、事前正答水準による異質性。

### 対象・方法・分析

米国ASSISTments、2025学年、7年生。生徒×問題ごとの割付。事前5問成績と交互作用、個人／問題／クラスのランダム切片を含む混合効果ロジスティック回帰。表2は20,706ユニーク生徒・87,270観測、表8は12,950観測（抄録は同数をstudentsと表記）。全体21,478人／572問という抄録表記は重複込み内訳の再確認が必要。

## 3. 結果と成立条件（原典の記述）

Table 5：低知識群（過去5問中0～1正解）の支援なし次問、OR=1.07、95%CI [1.02,1.13]、p=.010。事後サブ群分析。Table 10：教師FBとの次問比較OR=.98、CI [.87,1.09]、p=.667。有意差なしは同等性の証明ではない。回答修正と次問転移を区別する。

著者の解釈を含む部分は上記に明記した範囲に限定する。以下の設計案はAIによる考察であり、原典がすべてを直接検証したものではない。

## 4. 卒論での利用方法（AIによる考察・候補）

理解度で支援を変える仮説、典型誤答への事前生成・品質確認、次問を支援なしで測る評価設計。低群だけに必ず効果があるという一般則にはしない。

- 章・節候補：背景・理論／先行研究／設計要件の考察（既存章立ての暫定案への対応。採用を決定しない）。
- 対応する論点：理解度・フィードバック・RCT
- 引用箇所候補：採択稿 §3.1–3.6、§4–7、Tables 2/5/8/10。PDFは12ページ、印刷掲載ページとの対応は未照合なので節・表で指定。
- 他研究との一致・相違：L-001と転移指標が共通。こちらは自由対話ではなく事前生成FB。L-011の課題・過程FBを運用化。

## 5. 批判的評価

§7：問題ごとの交差曝露で長期追跡困難、画像問題を除外、単一教材・プラットフォーム。本文に観測数をstudentsと呼ぶ箇所があり、人数を単純加算しない。全体交互作用p=.058と事後低群の有意差から、群間差が確立したとは断定しない。

- 一般化：学校段階、教科、言語、比較群、使用モデル、評価時点が一致するか点検する。政策・理論は学習効果の因果根拠として扱わない。
- 卒論で補う余地：原典の条件を設計要件と評価指標へ対応づける。文献整理だけで実証的な空白を埋めたとは主張しない。

## 6. 確認状況・追加調査

- 確認状況：本文確認済み（著者公開採択稿）
- 確認した範囲：採択稿 §3.1–3.6、§4–7、Tables 2/5/8/10。PDFは12ページ、印刷掲載ページとの対応は未照合なので節・表で指定。
- 確認日：2026-10-12（日本時間）
- 未確認事項：Crossrefの姓Ivan Lim／採択稿のWen-Chiang Ivan Lim／著者サイトのLimが不一致。正式APAの姓名分割、最終版人数と表記を照合する。
- 次の作業：未確認事項の原典照合。Bは本文確認後に再分類。Aも最終引用前に書誌・訂正と引用箇所を再照合する。
- 再判定条件：本文の追加取得、正式研究範囲の変更、訂正・撤回、研究方法の問題の確認。
- 記録者：AIによる収集・原典照合・日本語要約。ユーザー／指導教員による採用決定ではない。

確認経路と取得制限は[検索・検証ログ](../../references/search-log-2026-10-12.md)を参照。
