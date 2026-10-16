# 本文確認済み・原本保存保留のワーキングペーパー

確認日2026-10-16。以下2研究は既存19件・開始時Drive29件と異なる。掲載原本の主要方法・結果・限界を確認したが、指定Driveがanyone/writerで、PDFのAll rights reserved表記に対する再配布条件を確定できないため保存保留。保存先を別の正本に変更せず、一時作業ファイルのみ使用。正式L-ID・登録24件・A/B/C件数には含めない。重要な比較資料として分析に明示的に参照するが、最終採用は保存条件・版・訂正確認後。NBER版とEdWorkingPaper版を別研究として加算しない。

## N-001：NUMI（優先候補1）

Oreopoulos, P., Liut, M., Sungu, A., & Low, N. (2026). *Making AI tutoring productive: Evidence from a mastery-based math practice experiment* (NBER Working Paper No. 35621). National Bureau of Economic Research. https://doi.org/10.3386/w35621

- 2026年8月、非査読WP、確認版72PDF頁（先頭2頁を含む）。公式 https://www.nber.org/papers/w35621 、PDF https://www.nber.org/system/files/working_papers/w35621/w35621.pdf 。EdWorkingPaper 26-1552 https://edworkingpapers.com/ai26-1552 は同一研究候補、版バイト同一は未確認。
- 米国Tennessee/Hamilton County、20校Grades6–8。Table 1は6,997登録、Table 5遅延6,327、Table 9習熟条件の遅延3,209で、6,000超という要約だけで同じ分母にしない。3月23–27日約50分、3月30–4月3日15–20分の約1週遅延（§3, PDF pp.10–15）。
- 個人単純無作為2×2×2：AI/CALのみ、習熟/非習熟、2topic。CAL対照にも共通動画・問題・誤答後の完成解法がある。AIは最初の一歩の二択理由ヒント、誤答後walkthrough、step説明。習熟条件は動画1分＋3問連続正解、非習熟は§3.4では3問後移動可（導入部の1問記述と不一致）。成分RCTではない。
- 1週後4問は練習topic2問／非練習topic2問。同型新問。非練習は別topicなので、それ自体を遠転移尺度とみなさない。§3の教師への内容支援禁止・筆記指示を確認したが、外部AI禁止・試験UIからのAI除去の明文は未確定。厳密なAIなし条件としての最終引用前に要追加照合。
- AIは練習進行と到達問題数を減らし、到達条件付き正答は高い（§4–5）。誤答をした人／後半に到達した人に条件づけると割付後選択が入る。Table 8の次試行正答+8.5pp、回復まで−.96試行、+2.88分は**機序を示唆する条件付き比較**であり、媒介の因果証明にしない（PDF pp.19–21,41）。
- 習熟規則のみで遅延成績の明瞭な改善なし（Table 5/§4.3）。Table 9は練習Ex1 CAL=.370／AI=.402、差.032(SE .017)、3,209人（PDF p.42、画像確認）。本文§5.5は3.1pp,p=.065と表記。丸めの差を併記し、p<.05の確定効果へ昇格させない。練習Ex2差.013(SE .017)、非練習Ex1差.002(.017)、練習計.044(.028)、練習−非練習差.026(.034)も保持。
- 主解析ITT、Table 9は遅延受検者に限定。無回答項目は誤答とする一方、欠測受検者を誤答に含めていない。実装lag・後半への到達・追跡欠測、複数比較、著者が開発に関与する点を留保。事前登録AEARCTR-0018678は表紙記載確認、登録内容との一致監査は未実施。
- 自律性・依存・SRL尺度なし。Q1の遅延評価、Q2の誤答後支援×進行ルール、Q3のDR-01/02/05/11に重要。方法品質中、直接性高、ただし独立評価のAI条件と保存が未解決。習熟基準・誤答支援・滞在時間の最適値、因果媒介、長期依存予防は導けない。

## N-002：Khanmigo（追加追跡候補）

Oreopoulos, P., & Low, N. (2026). *One click away: AI tutoring with Khanmigo in a two-year school experiment* (NBER Working Paper No. 35620). National Bureau of Economic Research. https://doi.org/10.3386/w35620

- 2026年8月、非査読、53PDF頁のNBER版。公式PDF https://www.nber.org/system/files/working_papers/w35620/w35620.pdf 、EdWorkingPaper26-1551 https://edworkingpapers.com/ai26-1551 （DOI 10.26300/kner-hv33）は別研究として数えない。
- 18中学校、Grades6–8、53学校内学年クラスタ（処置28/対照25、Year2は51）。6,902は**学生×学期観測**、固有学生数ではない。5学期2024–26、前後MAP両方のある観測を主対象（§2, PDF pp.8–17）。
- 処置はKhan Academyの習熟・MAP適応＋Khanmigo＋既存補習枠、対照は通常補習（CALありも多数）。**同じCALにAIだけを追加したRCTではない**。Khanmigoは答えを出さずヒント・問い、教師dashboard。年度内にUI変更あり。割付後学力改善で補習を退出した者も観測に残すonce-in方針、学校除外と欠測・汚染を記録。
- 既存MAPテストを前後測定、尺度は全国percentile・RIT・複数SD基準。Table 5/§4.1（PDF pp.23–24）：基線調整ITT +1.264 NPR、SE .60、1学期あたり、約.040学校母集団SD／.050対照SD。0.14SDは参加量で換算した別の推定でITTと混ぜない。AIを外して実験課題の保持を測った研究ではない。AI禁止の厳密な測定手続、全感度結果は追加監査を要する。
- メッセージ分析はactivated/matchedなYear2処置563人・16校で記述的。96%一度利用、個人中央値は練習日の33%、誤答session17%にメッセージ（§3.2）。理由・質問14.5%はメッセージ構成比で学生割合ではない。短い回答が浅い認知の証明とも言えないという著者の留保も保持。
- 学習効果をAI単独に帰属せず、他研究のCAL効果との似た大きさを「AIの追加効果ゼロ」の直接比較に変換しない。SRL・自律性・依存尺度なし。直接性高、方法品質中（クラスタRCT、事前登録・感度、複合介入・欠測・除外）。Q2/3の実質的関与・導入負担の補助資料、長期支援除去の効果としては不適合。

## 保存判断

公開閲覧可能であることと、一般公開編集可能な保管先へ複製できることを分ける。共有設定を本人が変更するか、再配布可能な著者版・ライセンスを確認してから指定Driveへ保存する。共有変更は実施していない。
