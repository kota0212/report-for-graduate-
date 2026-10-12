# 先行研究の横断レビュー：生成AI学習支援の設計要件

更新：2026-10-12。本人が今回提示したテーマを基準にした**スコーピングと批判的なナラティブレビュー**。指導教員による承認や実証研究方法の決定を代行しない。[文献一覧](../references/index.md)／[検索ログ](../references/search-log-2026-10-12.md)／[台帳](../references/literature-matrix.md)。

## 範囲と根拠の扱い

14件（研究12、政策2）の目的抽出。2022～2026年を優先し、フィードバック理論のみ2007年を含む。Google Scholarの検索ページ取得は失敗したため、一般Web検索から出版社・著者公開稿・学術登録機関へ辿った。Google Scholarの直接検索を完了したとは扱わない。網羅的検索、PRISMA準拠の本卒論のシステマティックレビュー、メタ分析ではない。全ヒット数は取得していない。

根拠は「対象内の短期因果効果」「限定された実践上の観察」「理論」「政策要件」「抄録段階」に分ける。信頼性の高低と卒論への関連度は別。A8件は使用候補であり、研究7件＋政策1件の本文確認範囲を記録したもの。B5件の詳細結果は確定根拠にしない。C1件は撤回による不採用で、関連度は高いまま保持する。

## 本文確認済みの評価表

| 文献 | 対象・介入 | デザイン／評価指標 | 判断できること | 限界・信頼性 |
|---|---|---|---|---|
| [L-001](../sources/usable/L-001-bastani-guardrails.md) | トルコ高校数学、通常型／教師ヒント型AI | クラスRCT、支援中練習と自力試験 | 通常型は自力試験で低下、設計型は害を軽減 | 短期・単一校、設計成分が混在。対象内の因果証拠は強い |
| [L-004](../sources/usable/L-004-tutor-copilot.md) | 米国小中学校、指導者向けAI | 指導者RCT、確認問題・対話・年度末試験 | 短期合格率向上、年度末は非有意 | プレプリント、対象層・人数段階に注意。中 |
| [L-005](../sources/usable/L-005-worden-feedback-rct.md) | 米国中学7年数学、検証済み誤答FB | 生徒×問題RCT、次問を支援なしで解答 | 低知識群の次問に利益の示唆、教師FB比較は非有意 | ORと正答率の区別、事後群分け、人数表記。中 |
| [L-007](../sources/usable/L-007-nachi-critical-thinking.md) | 日本高校3年20人、誤答教材 | 対照なし前後比較、誤り修正・態度 | 授業後の改善を観察 | 因果効果は限定、統計表記に要確認。中～低 |
| [L-008](../sources/usable/L-008-kestin-ai-tutoring.md) | 大学物理194人、設計済みチューター | クロスオーバーRCT、直後のテスト | 特定条件で教室ALより高い成績 | 大学生、複合介入、長期不明。短期は強い |
| [L-010](../sources/usable/L-010-alfarwan-k12-review.md) | 学校等30研究 | 記述的レビュー | 対象・方法・指標の偏りを整理 | 英語限定、教員養成を含む、検索過程要監査。中 |
| [L-011](../sources/usable/L-011-hattie-feedback.md) | フィードバック一般 | 理論・既存研究統合 | 目標／現在地／次の行動と水準の区別 | GenAIの効果ではない。概念的根拠 |
| [L-012](../sources/usable/L-012-mext-guideline.md) | 日本の学校 | 公的ガイドライン | 教師判断・情報活用能力等の政策条件 | 効果量・因果効果を示す資料ではない |

## ① 既に明らかなこと（対象と条件を限定）

1. **AIを使って正答できることと、AIなしで解けるようになることは異なる。** 高校数学のRCTはこれを直接区別した。設計型が通常型の害を軽減した一方、対照群より自力成績を有意に上げたとまでは言えない。[L-001](../sources/usable/L-001-bastani-guardrails.md)（強い、短期・対象内）
2. **教育的に設計したAIの利益は実在するが、全場面に共通する効果ではない。** 大学物理での直後成績、人間の指導者を介した小中学生の短期成績、誤答FB後の次問は別の成果である。[L-008](../sources/usable/L-008-kestin-ai-tutoring.md)、[L-004](../sources/usable/L-004-tutor-copilot.md)、[L-005](../sources/usable/L-005-worden-feedback-rct.md)（RCTを含むが対象・版・指標限定）
3. **教師の知見は、教材作成・品質確認・介入の判断に異なる形で組み込める。** 教師作成の問題情報、人間による提案編集、事前生成FBの検証がそれぞれ確認できる。いずれも人間の役割が完全に不要になった実験ではない。[L-001](../sources/usable/L-001-bastani-guardrails.md)、[L-004](../sources/usable/L-004-tutor-copilot.md)、[L-005](../sources/usable/L-005-worden-feedback-rct.md)（実装の事実）
4. **日本の学校では教師判断と情報活用能力を伴う利用が政策上の条件となる。** 誤り教材は利用例に含まれ、評価をAI出力だけで決めることは不適切例にある。[L-012](../sources/usable/L-012-mext-guideline.md)（政策根拠）。国内の小標本実践も誤り検証の授業化を示すが、普遍的な能力改善は証明しない。[L-007](../sources/usable/L-007-nachi-critical-thinking.md)（限定的な観察）

## ② 一致している知見

**短期成果と持続的な習得を別に見る必要がある。** 通常型の練習と試験の乖離、CoPilotの短期合格と年度末非有意、Wordenの交差曝露による長期推定の制約が整合する。これは「長期効果はない」という一致ではなく、短期の利益から長期効果を推論できないという一致である。[L-001](../sources/usable/L-001-bastani-guardrails.md)、[L-004](../sources/usable/L-004-tutor-copilot.md)、[L-005](../sources/usable/L-005-worden-feedback-rct.md)（中～強）

**支援内容と学習目標・誤概念を結びつける設計に共通点がある。** 教師ヒント、説明を促す提案、典型誤答FBは単なる完成答案の提供と区別される。フィードバック理論とも対応する。ただし、その各成分の独立した因果効果は未確立。[L-001](../sources/usable/L-001-bastani-guardrails.md)、[L-004](../sources/usable/L-004-tutor-copilot.md)、[L-005](../sources/usable/L-005-worden-feedback-rct.md)、[L-011](../sources/usable/L-011-hattie-feedback.md)（整合的な示唆）

**主観評価だけでは不十分。** 自己評価と実測のずれが見られ、学校領域レビューも自己報告への偏りを指摘する。満足度は補助指標にし、技能を直接測る必要がある。[L-001](../sources/usable/L-001-bastani-guardrails.md)、[L-010](../sources/usable/L-010-alfarwan-k12-review.md)（中～強）

## ③ 相違点と考えられる説明

| 比較 | 違い | 説明候補／留保 |
|---|---|---|
| [L-001](../sources/usable/L-001-bastani-guardrails.md) vs [L-008](../sources/usable/L-008-kestin-ai-tutoring.md) | 高校の通常型で害、大学の設計型で正の成績 | 復習vs新規学習、教科書vs教室AL、教師入力・動画・自己ペース等が異なる。AI一般への矛盾とはしない |
| [L-001](../sources/usable/L-001-bastani-guardrails.md) vs [L-005](../sources/usable/L-005-worden-feedback-rct.md) | 異質性の支持は限定的、低知識群で次問の利益 | 自由対話vs誤答FB、指標・事前知識測定が異なる。Wordenの事後群分け・交互作用p=.058に注意 |
| [L-007](../sources/usable/L-007-nachi-critical-thinking.md) vs [L-001](../sources/usable/L-001-bastani-guardrails.md) | 誤情報を教材にする／誤情報を減らす | 検証済みの誤答を教師が教材化することと、誤答を正解として渡すことは別。学習目的と監督の違い |
| [L-003](../sources/pending/L-003-lin-tan-k12.md) vs [L-010](../sources/usable/L-010-alfarwan-k12-review.md) | 抄録84研究／本文30研究 | 対象・検索日・リテラシー包含・教員養成の扱いが違い得る。L-003本文未確認のため厳密な対比は保留 |
| [L-006](../sources/pending/L-006-huang-integrated-feedback.md) vs [L-009](../sources/pending/L-009-meyer-writing-feedback.md) | 教師・ピアに追加／無FBと比較 | AIの追加利益とFB自体の利益を区別。双方本文未確認で効果量を比較しない |

「ソクラテス式」という呼称だけで効果を判断しない。問いの内容・タイミング・既有知識・応答品質を抽出し、ヒントや教師支援を含む複合介入を単一技法の証拠へ変換しない。[L-001](../sources/usable/L-001-bastani-guardrails.md)、[L-004](../sources/usable/L-004-tutor-copilot.md)、[L-008](../sources/usable/L-008-kestin-ai-tutoring.md)（方法上の解釈）

## ④ 十分に検証されていない論点

- 数か月～年単位の保持、別単元への転移、AIなしでの自己調整・援助要請。短期指標と実験設計の制約からの課題。[L-001](../sources/usable/L-001-bastani-guardrails.md)、[L-004](../sources/usable/L-004-tutor-copilot.md)、[L-005](../sources/usable/L-005-worden-feedback-rct.md)
- ヒントの段階数、答え開示の条件、問いかけと直接説明を切り替える閾値。設計成分が一括介入されている。[L-001](../sources/usable/L-001-bastani-guardrails.md)、[L-008](../sources/usable/L-008-kestin-ai-tutoring.md)
- 理解度の診断誤りが不適切な支援に結びつく頻度。事前5問代理指標や学年不適合提案を踏まえた問い。[L-005](../sources/usable/L-005-worden-feedback-rct.md)、[L-004](../sources/usable/L-004-tutor-copilot.md)
- 教師のレビュー工数、過信、授業規模での運用可能性。教師作成・検証を必要とする実装の条件から生じる課題。[L-001](../sources/usable/L-001-bastani-guardrails.md)、[L-005](../sources/usable/L-005-worden-feedback-rct.md)、[L-012](../sources/usable/L-012-mext-guideline.md)
- 日本の多様な学校・教科・学力・言語環境での再現。国内の小標本事例と海外・大学研究だけでは一般化できない。[L-007](../sources/usable/L-007-nachi-critical-thinking.md)、[L-008](../sources/usable/L-008-kestin-ai-tutoring.md)、[L-010](../sources/usable/L-010-alfarwan-k12-review.md)
- 教育格差：利用可能性、端末、言語、教師の専門性による効果差。特定の不利層を含むRCTはあるが、格差が長期に縮まる因果的結論はない。[L-004](../sources/usable/L-004-tutor-copilot.md)、[L-012](../sources/usable/L-012-mext-guideline.md)、[L-013](../sources/pending/L-013-unesco-guidance.md)（最後は公式紹介段階）

以上は**今回の検索・確認範囲で十分な根拠が得られなかった課題**。世界に研究が存在しないという主張ではない。検索上限、Google Scholar不可、英日中心、取得不可の5件が限界。

## ⑤ 日本の学校への適用

対象学年・教科のカリキュラムと語彙を明示し、教師が例題・正解・典型誤りを検証する。米国オンライン指導と日本の学級授業を同一視しない。[L-004](../sources/usable/L-004-tutor-copilot.md)、[L-005](../sources/usable/L-005-worden-feedback-rct.md)、[L-007](../sources/usable/L-007-nachi-critical-thinking.md)、[L-012](../sources/usable/L-012-mext-guideline.md)

AI利用前の自己解答、出力の検証、修正理由、教師への相談という学習過程を残す。年齢・学校方針・情報保護・学習評価での教師責任を検証する。評価時は「AIを使いこなす力」と「自力の教科学力」のテスト目的を分ける。[L-001](../sources/usable/L-001-bastani-guardrails.md)、[L-007](../sources/usable/L-007-nachi-critical-thinking.md)、[L-012](../sources/usable/L-012-mext-guideline.md)

制度資料は効果の証拠と別に扱い、導入の最新通知と倫理・同意を確認する。今回の研究テーマの正式承認、学校へのアクセス、倫理手続きは未確認である。[L-012](../sources/usable/L-012-mext-guideline.md)（政策上の注意と本Repoの状態）

## ⑥ 設計要件候補と検証方法（AIによる提案）

| 要件候補 | 根拠・強さ | 評価する指標／条件 | 未確立の点 |
|---|---|---|---|
| 自力試行後に段階的ヒント、丸ごとの答えを初期応答にしない | [L-001](../sources/usable/L-001-bastani-guardrails.md)、[L-004](../sources/usable/L-004-tutor-copilot.md)：複合介入の支持 | 独立解答、試行・説明・ヒント履歴、別問テスト | 最適な開示時点や段階数 |
| 教材・正解・誤概念に基づくFB、教師の品質確認 | [L-001](../sources/usable/L-001-bastani-guardrails.md)、[L-005](../sources/usable/L-005-worden-feedback-rct.md)：実装と短期RCT | 数学的誤り率、学年適合、教師修正工数 | 生徒直接生成と事前生成の比較 |
| 事前知識を診断し、支援量を調整 | [L-005](../sources/usable/L-005-worden-feedback-rct.md)、[L-011](../sources/usable/L-011-hattie-feedback.md)：仮説を支持 | 低・中・高群の事前指定、診断誤差、群×介入 | 自動適応そのものの因果効果 |
| 生徒に証拠・修正・理由を言語化させる | [L-007](../sources/usable/L-007-nachi-critical-thinking.md)、[L-004](../sources/usable/L-004-tutor-copilot.md)：限定実践・機序示唆 | 誤り検出、理由ルーブリック、別課題への転移 | 長期能力、AI単独成分 |
| 教師の提案承認・編集・停止・相談への移行 | [L-004](../sources/usable/L-004-tutor-copilot.md)、[L-012](../sources/usable/L-012-mext-guideline.md)：RCT＋政策 | 提案修正・不適合率、相談回数、介入負担 | 大人数教室での実行可能性 |
| 使用中成果と自力・遅延・転移テストを分ける | [L-001](../sources/usable/L-001-bastani-guardrails.md)、[L-004](../sources/usable/L-004-tutor-copilot.md)、[L-005](../sources/usable/L-005-worden-feedback-rct.md)：強い評価上の根拠 | 直後／一定期間後のAIなしテスト、事前知識調整 | 適切な遅延期間・教科差 |
| AIの限界を教え、利用と出典を透明化し入力を最小化 | [L-012](../sources/usable/L-012-mext-guideline.md)、[L-007](../sources/usable/L-007-nachi-critical-thinking.md)：政策＋実践 | 理解テスト、検証行動、情報入力、説明可能性 | 教育効果と保護の両立 |

要件は機能の候補であり、全てを必須とする仕様決定ではない。根拠の強さに応じて「短期実証に支えられた条件」「理論・政策に基づく条件」「検証すべき仮説」を区別する。

## ⑦ 卒論で独自に検討する価値があるRQ候補

1. **自力解答を維持する支援には、いつ・どの程度のヒントを出す条件が必要か。** 学年・教科を限定し、支援の段階と評価時点を先行研究から比較する。[L-001](../sources/usable/L-001-bastani-guardrails.md)、[L-005](../sources/usable/L-005-worden-feedback-rct.md)、[L-011](../sources/usable/L-011-hattie-feedback.md)
2. **事前知識別に支援量を変える要件を、既存研究はどこまで支持するか。** 群内の有意差と群間差を区別し、診断・閾値・停止条件を抽出する。[L-005](../sources/usable/L-005-worden-feedback-rct.md)、[L-004](../sources/usable/L-004-tutor-copilot.md)
3. **日本の教師が品質と主体性を維持するための役割は、どの設計機能で支えられるか。** 公的方針と国内実践を海外RCTの運用条件に対応づけ、要件ごとの根拠・限界を明示する。[L-012](../sources/usable/L-012-mext-guideline.md)、[L-007](../sources/usable/L-007-nachi-critical-thinking.md)、[L-004](../sources/usable/L-004-tutor-copilot.md)

文献ベースの設計要件提案なら、対象・包含基準・コード表・根拠評価を明示し、論文抽出を試行して再現可能なレビューに進める。人を対象とする調査やシステム実装は、指導教員との方法決定後に検討する。根拠評価の必要性は[L-010](../sources/usable/L-010-alfarwan-k12-review.md)、複合設計の切り分けは[L-001](../sources/usable/L-001-bastani-guardrails.md)、[L-008](../sources/usable/L-008-kestin-ai-tutoring.md)から導く。現在の研究計画をここで変更していない。

## 優先して読む5件

1. [L-001](../sources/usable/L-001-bastani-guardrails.md)：学習阻害とガードレールを同じ実験で比較し、卒論の中心命題に直結。
2. [L-005](../sources/usable/L-005-worden-feedback-rct.md)：中学生、事前知識、典型誤答、支援なし次問という設計・評価条件が具体的。
3. [L-004](../sources/usable/L-004-tutor-copilot.md)：教師・指導者が介在するAIの役割設計を実験で検討。
4. [L-007](../sources/usable/L-007-nachi-critical-thinking.md)：日本の高校数学で出力を批判的に検証する授業の具体例。
5. [L-011](../sources/usable/L-011-hattie-feedback.md)：ヒントやFBを分類・評価する理論基盤。GenAIの実証研究とは別枠。

## 現時点の結論

生成AIの有無だけでは適切な学習支援を説明できない。**支援の内容、教師の関与、学習者の事前知識、そして評価時にAIを使えるかを組み合わせて要件を提案する**ことが、本テーマでは妥当な方向である。ただしソクラテス式の単独優位、長期依存の予防、教育格差の縮小まで確立したとは言えない。[L-001](../sources/usable/L-001-bastani-guardrails.md)、[L-004](../sources/usable/L-004-tutor-copilot.md)、[L-005](../sources/usable/L-005-worden-feedback-rct.md)、[L-008](../sources/usable/L-008-kestin-ai-tutoring.md)、[L-011](../sources/usable/L-011-hattie-feedback.md)、[L-012](../sources/usable/L-012-mext-guideline.md)（研究横断からのAIによる解釈）
