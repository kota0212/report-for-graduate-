# 文献総合ページ

更新：2026-10-12。**登録総数19件：A使用候補8／B要確認10／C不採用1**。うちL-001～014の初回調査は研究論文等12件＋政策資料2件、旧来の本文確認8件（研究7＋政策1）。L-015～019の5件は追加登録・未評価。今回添付PDFの現物監査と従来の本文確認済み判定は別軸で管理する。L-014は撤回済みのため効果根拠から除外。

検索・評価の基準は、本人が2026-10-12に提示した「学校教育における生成AI学習支援の設計要件」。**指導教員等の正式承認は既存資料で確認できない**。Aは使用候補であり正式採用ではない。

判定と確認範囲は[台帳](literature-matrix.md)、詳細は各MD、コピー用書誌は[APA一覧](apa-reference-list.md)、論点比較は[横断レビュー](../docs/literature-review.md)。再利用の手順は[管理ルール](README.md)。

## 2026-10-12の添付PDFを用いた分析

本人が今回提供したPDF**12ファイル（重複を除く11資料）**を照合し、**10資料を暫定分析**した。撤回済みL-014は研究の効果根拠から除外。**L-002、L-006、L-011、L-015～019の8件は今回PDF未添付・この回の本文未確認**であり、以前の検証履歴は維持する。

**[現物確認の一覧・学習成果比較・設計要件候補・政策上の限界を読む](../docs/uploaded-pdf-evidence-review-2026-10-12.md)**

## 2レビューからの原著候補抽出（2026-10-13）

Lin & Tan（84研究）、Alfarwan（30研究）を起点として、**参考文献リスト**を抽出・照合。Lin側154件、Alfarwan側64件、参考文献の重複13件、**引用文献候補205件**。本文の収録研究84件＋30件全体を同定・重複除去したという意味ではない（レビュー本文に全件対応表がなく、Alfarwanの年別集計・列挙にも不一致）。

- [抽出範囲・限界・読むべき原著30件のランキング](../docs/review-reference-priority-2026-10-13.md)
- [205件の重複除外済み参考文献候補CSV](review-citation-screening-2026-10-13.csv)

原著の本文確認前の候補であり、既存文献台帳の「採用・本文確認済み」とは区別する。

## 研究領域から探す

| 領域 | 関連文献 |
|---|---|
| 学習効果と依存 | L-001, L-002, L-008 |
| ヒント・問いかけ・FB | L-001, L-004, L-005, L-009, L-011 |
| 理解度に応じた支援 | L-005, L-008, L-011 |
| 教師・AI・ピアの役割 | L-003, L-004, L-006, L-012 |
| K–12全体の研究地図 | L-003, L-010 |
| 誤情報・リテラシー・日本適用 | L-007, L-012, L-013 |
| 教育格差・公平性 | L-004, L-012, L-013（格差縮小の確立とはしない） |
| 撤回の監視 | L-014（効果根拠から除外） |

領域内のIDは下の判定別一覧から各原典と詳細へ進める。

## A：使用候補

### L-001：Generative AI without guardrails can harm learning: Evidence from high school mathematics

- 著者・年：Hamsa Bastani; Osbert Bastani; Alp Sungu; Haosen Ge; Özge Kabakcı; Rei Mariman（2025）
- 領域：学習効果・依存・ヒント
- 概要：トルコの高校数学で、通常型AIと教師が作成したヒント等を組み込んだAIを比較した研究。AI使用中の成績向上と、使用後に自力で解く成績を区別する。通常型では自力成績が低下し、支援設計によってその害が軽減されたが、設計型の自力成績の上昇までは確認されない。
- 卒論との関係：学習効果・依存・ヒントを検討する根拠候補。原典の対象・条件に限定して利用する。
- 判定・確認：A／本文確認済み
- [詳細分析](../sources/usable/L-001-bastani-guardrails.md) · [原典](https://www.pnas.org/doi/10.1073/pnas.2422633122)

### L-004：Tutor CoPilot: A Human-AI Approach for Scaling Real-Time Expertise

- 著者・年：Rose E. Wang; Ana T. Ribeiro; Carly D. Robinson; Susanna Loeb; Dora Demszky（2024）
- 領域：教師・AI協働・問いかけ
- 概要：米国のオンライン個別指導で、AIが生徒に直接答える代わりに人間の指導者へ提案するシステムを評価した研究。短期の確認問題の合格率と対話方略が改善した一方、年度末試験の有意な改善は確認されない。教師が提案を選択・修正する設計の根拠候補となる。
- 卒論との関係：教師・AI協働・問いかけを検討する根拠候補。原典の対象・条件に限定して利用する。
- 判定・確認：A／本文確認済み（v2）
- [詳細分析](../sources/usable/L-004-tutor-copilot.md) · [原典](https://arxiv.org/abs/2410.03017)

### L-005：A Large Scale Randomized Control Trial Showing LLM Generated Feedback Helps Low-Knowledge Middle School Math Students with Short-Term Learning

- 著者・年：Eamon Worden; Luca Dang; Wen-Chiang Ivan Lim; Sarah Miller; Jiayi Zhang; Aaron Haim; Adam Sales; Ashish Gurung; Neil Heffernan（2026）
- 領域：理解度・フィードバック・RCT
- 概要：中学7年生の数学で、典型誤答に対する検証済みAIフィードバックを、正誤情報のみ／教師作成フィードバックと比較する2つのRCT。次の問題を支援なしで解く指標を用い、事前知識が低い群に利益が見られる。オッズ比を正答率の増加と混同しないことが重要である。
- 卒論との関係：理解度・フィードバック・RCTを検討する根拠候補。原典の対象・条件に限定して利用する。
- 判定・確認：A／本文確認済み（著者公開採択稿）
- [詳細分析](../sources/usable/L-005-worden-feedback-rct.md) · [原典](https://doi.org/10.1145/3774398.3811594)

### L-007：誤りを含む生成AIの回答に批判的思考を働かせる教材を用いた高校数学の実践と評価

- 著者・年：名知 秀斗; 田中 博之（2025）
- 領域：日本の高校・誤情報・批判的思考
- 概要：日本の高校3年生20人に、AIの誤答を選別した数学教材で正誤判断・証拠・修正・理由づけを学ばせる実践。パフォーマンスと批判的思考態度の一部に事前事後の改善を報告する。生徒がAIと自由対話した試験ではなく、教師・仲間・教材を組み合わせた授業である。
- 卒論との関係：日本の高校・誤情報・批判的思考を検討する根拠候補。原典の対象・条件に限定して利用する。
- 判定・確認：A／本文確認済み
- [詳細分析](../sources/usable/L-007-nachi-critical-thinking.md) · [原典](https://www.jstage.jst.go.jp/article/konpyutariyoukyouiku/59/0/59_70/_article/-char/ja)

### L-008：AI tutoring outperforms in-class active learning: an RCT introducing a novel research-based design in an authentic educational setting

- 著者・年：Greg Kestin; Kelly Miller; Anna Klales; Timothy Milbourne; Gregorio Ponti（2025）
- 領域：学習効果・足場かけ
- 概要：大学物理で研究知見を組み込んだAIチューターと教室のアクティブラーニングを比較したRCT。直後の学習成績はAI群で高く、学習時間も短い。特定の大学・内容・教材の比較であり、高校生への一般化や教師を置き換える結論、長期保持の証明には使えない。
- 卒論との関係：学習効果・足場かけを検討する根拠候補。原典の対象・条件に限定して利用する。
- 判定・確認：A／本文確認済み
- [詳細分析](../sources/usable/L-008-kestin-ai-tutoring.md) · [原典](https://www.nature.com/articles/s41598-025-97652-6)

### L-010：Generative AI use in K-12 education: a systematic review

- 著者・年：Abdullah Alfarwan（2025）
- 領域：K–12レビュー・研究方法
- 概要：K–12の生成AI利用を30論文から整理するレビュー。高校段階と教員養成、STEM、準実験、心理指標が中心と述べる。対象範囲には職業教育や教員養成が含まれ、純粋な児童生徒研究だけではない。学校段階と測定指標を分けた卒論レビューの必要性を示す。
- 卒論との関係：K–12レビュー・研究方法を検討する根拠候補。原典の対象・条件に限定して利用する。
- 判定・確認：A／本文確認済み
- [詳細分析](../sources/usable/L-010-alfarwan-k12-review.md) · [原典](https://www.frontiersin.org/journals/education/articles/10.3389/feduc.2025.1647573/full)

### L-011：The Power of Feedback

- 著者・年：John Hattie; Helen Timperley（2007）
- 領域：基礎理論・フィードバック
- 概要：フィードバックを目標との差を埋める情報として捉え、目標・現在地・次の行動の3つの問いと、課題・過程・自己調整・人格の水準を整理する基礎研究。生成AI以前の研究であり、AIによる支援の効果を直接証明しないが、返答の設計と評価を分類する基盤になる。
- 卒論との関係：基礎理論・フィードバックを検討する根拠候補。原典の対象・条件に限定して利用する。
- 判定・確認：A／本文確認済み（大学公開の掲載PDF）
- [詳細分析](../sources/usable/L-011-hattie-feedback.md) · [原典](https://journals.sagepub.com/doi/10.3102/003465430298487)

### L-012：初等中等教育段階における生成AIの利活用に関するガイドライン（Ver. 2.0）

- 著者・年：文部科学省 初等中等教育局（2024）
- 領域：日本の制度・教師責任・リテラシー
- 概要：日本の初等中等教育での生成AI利用について、人間中心の利用、情報活用能力、教師の判断、年齢・個人情報・公平性等の留意点を示す公的資料。学習活動の適否を教育目的から判断することを求める。政策上の設計条件と学習効果の実証根拠を分けて利用する。
- 卒論との関係：日本の制度・教師責任・リテラシーを検討する根拠候補。原典の対象・条件に限定して利用する。
- 判定・確認：A／本文確認済み
- [詳細分析](../sources/usable/L-012-mext-guideline.md) · [原典](https://www.mext.go.jp/content/20241226-mxt_shuukyo02-000030823_001.pdf)

## B：要確認

### L-002：The impact of GenAI on learning outcomes: A systematic review and meta-analysis of experimental studies

- 著者・年：Xiaoli Han; Hongchao Peng; Mingzhuo Liu（2025）
- 領域：学習効果・メタ分析
- 概要：生成AIの学習成果への影響を実験研究のシステマティックレビューとメタ分析で検討する文献。著者、年、媒体、論文番号、DOIはCrossrefで照合できた。学校段階別の結果、AIなし評価の割合、効果量や出版バイアスは本文未確認で、現時点では結論の根拠に採用しない。
- 卒論との関係：学習効果・メタ分析を検討する根拠候補。本文取得・監査まで保留。
- 判定・確認：B／書誌情報のみ確認（出版社検索抜粋も取得）
- [詳細分析](../sources/pending/L-002-han-meta-analysis.md) · [原典](https://www.sciencedirect.com/science/article/pii/S1747938X2500051X)

### L-003：A Systematic Review of Generative AI in K–12: Mapping Goals, Activities, Roles, and Outcomes via the 3P Model

- 著者・年：Xiaoling Lin; Hao Tan（2025）
- 領域：K–12レビュー・役割・設計
- 概要：3～18歳を対象とした84件の査読付き実証研究を、学習目標、活動、AIの役割、成果の関係から整理するレビュー。抄録は3PモデルとCIMO、MMATによる評価を述べる。今回添付PDFの要約・方法・限界の一部を確認した。84件の質評価・抽出表の全面監査は未了のため採用保留。
- 卒論との関係：K–12レビュー・役割・設計を検討する根拠候補。本文取得・監査まで保留。
- 判定・確認：B／今回添付PDFの要約・方法・限界の一部を確認（全監査未了）
- [詳細分析](../sources/pending/L-003-lin-tan-k12.md) · [原典](https://www.mdpi.com/2079-8954/13/10/840)

### L-006：Effects of integrating generative AI, teacher, and peer feedback on Middle school students’ attitudes, writing proficiency, and peer-assessment scoring ability: a quasi-experimental study

- 著者・年：Biyun Huang; Shiyi Xie; Timothy Khe Foon Hew（2026）
- 領域：教師・ピア・AI統合
- 概要：中学生66人・6週間で、教師とピアのフィードバックにAIを追加する群と、教師とピアのみの群を比較する準実験。抄録では両群に改善がありAI追加群の伸びが大きいとされる。AI単独の優位性や長期効果は示せず、割付・採点・交絡の本文確認が必要である。
- 卒論との関係：教師・ピア・AI統合を検討する根拠候補。本文取得・監査まで保留。
- 判定・確認：B／抄録のみ確認
- [詳細分析](../sources/pending/L-006-huang-integrated-feedback.md) · [原典](https://www.tandfonline.com/doi/full/10.1080/01443410.2025.2611980)

### L-009：Using LLMs to bring evidence-based feedback into the classroom: AI-generated feedback increases secondary students’ text revision, motivation, and positive emotions

- 著者・年：Jennifer Meyer; Thorben Jansen; Ronja Schiller; Lucas Wilhelm Liebenow; Marlene Hanna Steinbach; Andrea Horbach; Johanna Fleckenstein（2024）
- 領域：高校・文章フィードバック
- 概要：高校段階の英語学習者459人が論証文を修正する際、GPT-3.5-turboのフィードバックを受ける条件と無フィードバック条件を比較する研究。抄録は修正成績と動機・感情への利益を報告する。今回添付PDFのTable 1では同じ文章の修正成績が改善（p=.042）した一方、新規作文課題の群間差は有意でない（p=.259）。両アウトカムは区別する。
- 卒論との関係：高校・文章フィードバックを検討する根拠候補。本文取得・監査まで保留。
- 判定・確認：B／今回添付PDFの方法・Table 1を確認（追加監査待ち）
- [詳細分析](../sources/pending/L-009-meyer-writing-feedback.md) · [原典](https://www.sciencedirect.com/science/article/pii/S2666920X23000784)

### L-013：Guidance for generative AI in education and research

- 著者・年：Fengchun Miao; Wayne Holmes（2023）
- 領域：政策・人間中心・公平性
- 概要：UNESCOが教育と研究での生成AI利用を人間中心に設計するために示した指針。公式紹介ではデータ保護、年齢に配慮した利用、倫理と教育的妥当性の検証を重視する。今回の添付PDFで冊子の冒頭と政策原則およびDOIを確認した。全条項と日本法との詳細対比は引き続き保留。
- 卒論との関係：政策・人間中心・公平性を検討する根拠候補。本文取得・監査まで保留。
- 判定・確認：B／今回添付の公式冊子の冒頭・政策原則を確認（全章精査未了）
- [詳細分析](../sources/pending/L-013-unesco-guidance.md) · [原典](https://unesdoc.unesco.org/ark:/48223/pf0000386693)

## C：不採用

### L-014：The effect of ChatGPT on students’ learning performance, learning perception, and higher-order thinking: insights from a meta-analysis

- 著者・年：Jin Wang; Wenxiang Fan（2025）
- 領域：メタ分析・撤回管理
- 概要：ChatGPTの学習成果に関するメタ分析だが、出版社は2026年4月に撤回を通知している。題名上の関連性は高いものの、分析と結論の信頼性を失っており、学習効果の根拠としては採用しない。検索で再発見した際の誤採用防止のため除外記録として管理する。
- 卒論との関係：メタ分析・撤回管理を検討する根拠候補。撤回により根拠として不採用。関連性自体は高い。
- 判定・確認：C／原論文は書誌のみ／撤回通知本文確認済み
- [詳細分析](../sources/not-usable/L-014-wang-fan-retracted.md) · [原典](https://www.nature.com/articles/s41599-025-04787-y)

## PDF収集試行（2026-10-12）

新規5件を保留登録（L-015–019）。4件保存、1件未取得。採否は未確定。[取得記録・保存先](pdf-collection-pilot-2026-10-12.md)。
