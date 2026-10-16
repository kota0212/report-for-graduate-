# 構造化文献比較分析の方法案（未正式承認）

## 査読後の方法補足（2026-10-16）

評価AI条件は単語検索でなく、本文・図・測定手続を合わせて判定する。S0明示、S1手続分離、S2支援前イベント、SU不明、SA支援中を[運用方法](step2-selection-comparison-method-2026-10-16.md)に追加した。S1/S2を補助・感度分析へ含め、全面禁止と混同しない。知識・SRL・支援中成果は別行。方法の正式承認・全件の再抽出は未完了。[査読後監査](../references/gemini-source-audit-2026-10-16.md)を参照。

2026-10-16。現行暫定RQを対象にした実行可能な方法案。今回の実施記録は[検索ログ](../references/search-log-2026-10-16.md)、結果は[根拠比較](evidence-synthesis-2026-10-16.md)。以下は今後の再現手順を含み、未実施の操作を実施済みにしない。

## 検索・選定

1. 2026-10-16を今回の検索截止日とする。直接GenAIは2022年以降、学年6–12相当を中心に、年齢・学校制度を別欄で確認。10–17歳等の混合標本は中等サブセットが分離できるか記録。基礎理論は年を制限しない。
2. 少なくとも対象・支援内容・比較・成果測定の分かる一次介入研究を中核とする。本文未確認は候補、撤回は効果根拠除外。質の低さだけで負の研究を除外せず、信頼性を分けて残す。
3. 主検索式案：("generative AI" OR ChatGPT OR "large language model" OR "AI tutor") AND ("secondary school" OR "middle school" OR "high school" OR adolescent) AND (unassisted OR posttest OR "delayed test" OR retention OR transfer)。支援語（hint/scaffold/feedback/Socratic/mastery/fading）とSRL語（"self-regulated learning"/metacognition/"help seeking"/overreliance/"cognitive offloading"）を別検索して、すべてを一式に詰め込み過ぎない。
4. 日本語は「生成AI 中学生 高校生 学習効果 自力解答」「生成AI 段階的ヒント 自己調整学習」等。Scholar、ERIC、CiNii Research、J-STAGE、出版社・大学、Crossrefを使う。今回の直接DB操作と外部検索のsite指定は区別する。次回は各DBのURL・検索フィールド・件数・対象期間・ページ境界を保存。
5. DOI正規化、タイトル・著者・年・版で重複排除。WP→掲載版を研究単位で統合、異版の結果差は保持。レビューと収録一次研究を独立証拠に加算しない。
6. タイトル抄録→全文の二段階。理由コード：E1対象外（大学・成人／小学生は間接層へ）、E2介入効果を測らない（背景・政策へ）、E3本文未確認、E4同一研究、E5撤回、E6AI利用制限不明（独立評価の主比較から外す）、E7測定条件不十分。E6/E7でも他の問いに使える範囲は残す。

## 抽出する列（1研究×比較×成果×時点が1行）

`study_id, report_id, DOI, title, authors, year, venue, peer_review, retraction_check_date, source_version, Drive_status, country, school_level, grade, age, subject, recruitment, N_assigned, N_analyzed, allocation_unit, randomization, baseline, attrition, comparator, AI_model_version, scaffolding_components, learner_required_action, teacher_role, exposure_minutes, outcome_construct, instrument, reliability, assessment_support, timing_days, same_or_new_items, retention_or_transfer_definition, mean_SD_by_group, effect_metric, estimate, SE_CI, p_value, multiplicity, model_adjustments, subgroup_prespecified, source_locator, author_interpretation, analyst_inference, limitations, Q1_Q2_Q3, requirement_id, quality, applicability`。

数値不明はNA＋理由。割付人数・完遂人数・学生×学期・誤答イベント数を別列にし、分母を統一しない。AI禁止は「明示」「手続から推定」「不明」を別コードにする。新版・補足資料で更新したら旧値と理由を残す。

## 比較と信頼性

- Q1：支援中／独立直後／新問近転移／遠転移／遅延保持の成果層。AIなしの明文がある主比較と、手続推定・不明の感度層を分ける。
- Q2：同一研究内支援比較を最優先、次に事前指定交互作用、観察過程、研究間の条件差、基礎理論。各推論段階を表の列で明示。
- 方法品質は割付、クラスタ調整、基線差、欠測、採点・測定妥当性、選択報告、介入忠実度、実装、独立評価の支援条件、利益相反で記述。点数の合計だけで採否を決めない。
- 適用可能性は中学/高校、教科、年齢、言語、学校内/外、教師の役割、日本の制度との距離を別軸で評価。大学の良質RCTが学校へ直接根拠になるわけではない。
- 異質な尺度を無理に平均化しない。p値の有意票数ではなく推定値・CI・対照・時点を並べる。CI未報告は勝手に作らない。複数効果量の依存や少数研究を考え、今回はメタ分析を第一候補にしない。
- Q3：問題→結果→要因→要件→根拠分類→反証→実装指標・追加検証。強い研究でも介入成分の独立効果が分からなければB/C。

## 監査・再現性

今回は1名相当のAI支援選別・抽出で、独立二重選別なし。最終引用前に本人が中核研究の比較条件・数値・根拠頁を再点検し、判断不一致を記録する提案。全件を二重監査したとは書かない。参考文献からの追跡も採用ごとに起点ID・方向・採否を記録。検索限界とアクセス制限を方法章へ記述する。

## 独自調査の選択

**第一候補は文献比較と要件導出**。20,000字規模で、成果層・介入条件・反証・要件の追跡という独自分析に集中する。現時点で教師アンケート・未成年実験は開始しない。

- 教師調査は「効果の証明」ではなく、要件の理解可能性、必要工数、学校内の責任分担・実行可能性を補う場合に価値がある。協力先・研究同意・大学倫理要件・匿名化・公開範囲・期間を確認し、本人承認後に小規模面接等を検討。便宜標本・自己報告・賛同バイアスを限界にする。
- 二次データはL-029の公開データ/コードが候補。欠測感度や尺度と行動の区別には価値があるが、匿名性・ライセンス・事前登録との整合、分析技能と時間を先に確認する。データを取得・再分析したとは記録しない。公開Repoに個票を置かない。
- 今回の締切見通しでは、独自調査を卒論成立の必須条件にする根拠はない。指導教員が一次調査を要求する場合は、RQと期限を再検討する。

## 本文構成と分量の見通し（相談用・未採択）

既存研究計画の構成を、1序論2,000字、2概念・理論3,000字、3先行研究と比較枠組み3,500字、4方法2,500字、5比較分析5,000字、6考察・要件4,500字、7結論1,500字へ具体化すると本文約22,000字。参考文献・付録を除いた仮配分であり、正式な算入規程は未確認。章・小見出しは本人・指導教員の相談後に決める。本文の本格作成・Word作成は今回実施しない。

材料の対応：2はL-011/030と概念定義、3は旧19件＋新規5件、5はQ1/Q2表と反例、6はDR-01〜12と適用限界。研究条件が確認できない文献で文字数を水増ししない。
