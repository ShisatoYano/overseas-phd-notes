# 候補大学 横断リスト

調査日: 2026-09-22

## 目的と見方

必須2条件「**リモート可**」×「**在職可(パートタイム/External)**」を満たす大学の母集団を作る。各校は以下3点だけ浅く確認し、深掘りは個別ファイル(`labs/<大学名>.md`)に分ける。

1. リモート制度の有無
2. パートタイム/在職の可否、および**リモートとの組み合わせ可否**
3. 自律移動・制御・マルチエージェント系の受け皿の有無

判定: ◎=条件を公式に満たす / ○=満たす見込み(要確認) / △=条件付き・限定的 / ×=不成立

## 一覧

| 大学 | 国 | リモート | 在職(PT) | 組合せ | 分野の受け皿 | 総合 |
|---|---|---|---|---|---|---|
| **York** | 英 | Distance PhD | PT 6年(72か月) | **◎ 出願ページに明記** | **◎ CfAA(自動運転を明示的に扱う)** | **◎ 総合1位**(詳細: `labs/york.md`) |
| **Swansea** (CS) | 英 | Distance PhD | PT 6年 | **◎ 明記** | △ 受け皿なし(要翻訳) | ○ |
| **UOW** | 豪 | Distance HDR | PT可 | **◎ 肯定形で明記(唯一)** | △ 自律移動の拠点なし。DSL が唯一の接続先 | ○(詳細: `labs/uow.md`) |
| **UTS** | 豪 | PhD by distance | PT 最長8年 | ○ 推定 | **◎ Robotics Institute** | ○ |
| **TU Delft** | 蘭 | External PhD(在職・現居住地維持を公式に明記) | ◎ | **○ ただし地理的範囲が不明** | **◎ Autonomous Multi-robots Lab 他(全候補中トップ)** | ○ 不確実性大(詳細: `labs/tudelft.md`) |
| **Imperial** | 英 | なし(PRI / Split PhD のみ) | PT 5-6年 | △ 日本拠点は PRI(勤務先を拠点)か Split が前提 | **◎ Control and Power 他** | △(詳細: `labs/imperial.md`) |
| Reading | 英 | PhD by Distance | PT 4-6年 | △ 条件付き | ? 未確認 | △ → ○ 要確認(2026-09-28 条件緩和で再評価) |
| Wolverhampton | 英 | FT distance 4年 | PT 8年 | ? 未確認 | ? Computing and Mathematics | ? |
| UNE | 豪 | External/Offshore HDR | ? | ? | △ 薄いと推定 | △ |
| CQUniversity | 豪 | PhD (Offshore) | ? | ? | ? 未調査 | ? |
| Twente / Eindhoven | 蘭 | ? | External PhD | ? | ○ 制御・ロボティクス | ? 未調査 |
| West London / Hertfordshire | 英 | 有 | 有 | ? | ? | 優先度低 |

---

## 横断的に分かったこと

### ビザ論法が英国でも確認された

`misc/remote-phd-feasibility.md` に記録した「リモートなら学生ビザ要件から外れる」という論法が、UTS(豪)に続き**英国でも公式文面で確認できた**。

- York: 「**You cannot study a part-time course at the University of York if you require a Student Visa.**」
- UOW: 「International candidates based overseas **do not need an Australian study visa so are eligible to undertake HDR studies part-time**, an option not available for onshore students.」
- UTS: 「to obtain a student visa..., international students must enrol full time and on campus, which means distance study may not be available to international students requiring a visa」

→ **「国際学生はフルタイムのみ」という記載を見ても即座に脱落とさず、それがビザ起因かを確認する**。ビザ不要のフルリモートなら制約は適用されない。UOW は「ビザ不要だからパートタイム可」を**肯定形で明記した唯一の例**で、照会時の論拠として引用できる。

### 学費レンジ(国際学生)

| 大学 | 学費 | 想定総額 |
|---|---|---|
| **TU Delft**(External) | 授業料 €11,000(1回)+ bench fee €10,000/**年** | 4年 約€51,000 / **6年 約€71,000** |
| **Swansea** (CS) | PT £11,800/年 | 6年 約£70,800 |
| **York** (CS) | FT £32,030/年(2027/28、STEMバンド)。**PT額は未掲載** | 6年 約£96,000(半額と仮定した試算) |
| **UTS** | course fee A$198,543(CS)/ A$215,274(Eng)。年額か総額か要確認。PTは年額×0.5 | 要確認 |

→ 【**訂正**】初版で「蘭の External PhD は桁違いに安い可能性」と書いたが、**bench fee が年額であることを見落としていた**。6年で約€71,000となり Swansea(約£70,800)とほぼ同水準。費用面の特別な優位性はない。

---

## 個別メモ

### York(英国) — 新規・最有力

- **リモート×在職**: PhD in Computer Science は「3 years full-time / **6 years part-time**」で、**distance learning は両モードで利用可能**。英国内・国外どちらに居住してもよい
- **分野の受け皿(ここが Swansea との決定的な差)**:
  - **Centre for Assuring Autonomy**: Lloyd's Register Foundation と York の £12m 出資。ロボティクス・自律システム(RAS)の安全性に関する研究・訓練・標準化をリード
  - **Institute for Safe Autonomy**: £45m の施設、100名超の研究者。地上・水中・空中の自律システムが対象。UKRI Trustworthy Autonomous Systems Hub の Resilience Node を運営
  - **High Integrity Systems Engineering** グループ
  - **Real-Time and Distributed Systems** グループ: 組込み、IoT、**ロボティクス、自動車システム**、大規模プロセス制御、航空電子など
- **入学要件**: CS または関連分野の honours 2:1 以上。非標準の経歴も、CSの知識と経験を示せれば考慮される(**自身のOSSが効く可能性**)
- **出願**: 開始は2月と9月。**事前に指導教員候補を特定すること**が前提。国際出願者の面接は Zoom
- **懸念**: Institute for Safe Autonomy は実験施設を持つ「living lab」。ただしCS側の検証・保証(assurance)研究は理論主体で、リモート適性は高いとみられる
- **テーマとの接続**: `research-theme/candidates.md` の「安全性の形式検証」候補に直結。加えて Real-Time and Distributed Systems は自動車システムを扱うため、経路計画・制御側からの接続も考えられる
- 出典: [PhD Computer Science](https://www.york.ac.uk/computer-science/study/postgraduate-research/phd-computer-science/) / [Research Groups](https://www.york.ac.uk/computer-science/research/groups/) / [Institute for Safe Autonomy](https://www.york.ac.uk/safe-autonomy/) / [国際学費](https://www.york.ac.uk/study/postgraduate-research/fees/international/)
- **調査済み → `labs/york.md`**。出願ページに「Part-time: Distance Learning (72 months)」が明示されていることを確認。最有力の指導教員候補は **Prof Radu Calinescu**(形式手法によるコントローラ合成、純ソフトウェアでリモート適性が極めて高い)

### UOW - University of Wollongong(豪州) — 制度面が最もクリーン

- **在職可否が肯定形で明記されている唯一の例**(上記引用)
- 対象は「**コースワークを含まない研究学位のみ**」(PhD または MPhil)。指導はバーチャル。居住地は豪州内外を問わない
- **「Suitable only for research projects that do not require physical access to facilities based at UOW campuses」** → 自分のシミュレーション中心方針と要件が一致
- キャンパス出席は不要。在学中のオンキャンパス学生からの転換も申請可
- **調査済み → `labs/uow.md`**。**受け皿は弱い**。UTS Robotics Institute / TU Delft CoR / York CfAA に相当する自律移動の研究拠点はない
  - UOWのロボティクス(CIMR = ハプティクス・リハビリ・車両制御、FIF = 産業ロボット6台)は**実機・臨床・製造主体**で、「キャンパス施設への物理アクセスを要しない研究のみ」という distance HDR の要件と**構造的にぶつかる**
  - 唯一の接続先は **Decision Systems Lab**。マルチエージェント自律システム・自律無人ビークルを**明示的にアルゴリズム/シミュレーション主体**で扱う。ただし制御理論的な経路計画ではなくAI・意思決定・最適化の系統で、**Swansea と同種の「翻訳」が必要**
  - ほかに SMART Infrastructure Facility(交通シミュレーション、Nam Huynh)があるが、交通ネットワーク・都市レベルで車両単体の制御とは階層が違う
- 出典: [Higher Degrees by Research (UOW)](https://www.uow.edu.au/research/graduate-research/future-students/higher-degrees-by-research/)

### TU Delft(オランダ) — 調査済み → `labs/tudelft.md`

- **在職・現居住地維持が公式に明記されている**: 「keep your current job and/or stay where you live and work on your project part-time as an external PhD candidate」— これまで調べたどの大学よりも直接的に今回の条件を記述している
- **テーマ適合度は全候補中トップクラス**: Cognitive Robotics 学部の **Autonomous Multi-robots Lab**(モーションプランニング、マルチロボット、インテリジェント交通)、**Learning and Autonomous Control**(マルチロボット制御、リアルタイム協調)。**Assoc Prof Javier Alonso-Mora** は経路計画・制御・マルチロボット協調の3領域すべてに重なる
- **だが不確実性が最大**: (1)「stay where you live」に日本(EU域外)が含まれるか不明 (2) 学部ごとに方針が大きく異なり、**A+BE は2025年から自己資金PhDの受け入れを停止**、IDE は**オランダでの生活費**カバーを要求 (3) パートタイム外部PhDの資金モデルが「雇用主のスポンサーシップ」前提 (4) 3mE / EEMCS の方針は未確認
- 費用は6年で約€71,000(訂正済み)。ただし bench fee は「作業スペースと実験室利用」の対価で想定利用量に応じて決まり、**学部に免除の裁量がある**ため、完全リモートでの減免余地は照会する価値あり

### Reading(英国) — 完全リモートではない

- PhD by Distance。FT 3-4年 / **PT 4-6年**(フルタイムの50-60%の負担)
- **条件が重い**: 初月のキャンパス滞在を強く推奨、初学期の induction 出席、以降も Confirmation of Registration 等の節目で出席が期待される。オフキャンパスは「登録期間の**2/3以上**」でよいとされ、裏を返せば**最大1/3はキャンパス滞在を想定**している
- 「これはオンライン学習プログラムではない」と明記。参加しないスクールもある
- → 在職フルリモートという条件とは相性が悪い。**優先度低**
- 出典: [PhD by Distance (Reading)](https://www.reading.ac.uk/doctoral-researcher-college/doctoral-opportunities/phd-distance)

### その他(未調査・優先度低)

- **Wolverhampton**: PhD Computing and Mathematics が PT 8年 / FT distance 4年。**PT と distance の組み合わせ可否が不明**
- **UNE**(豪): external/offshore HDR に **25%の学費減額**。ただし「オンキャンパス設備や専門インフラを必要としない選択された分野」限定で、ロボティクス系の受け皿は薄いと推定
- **CQUniversity**(豪): PhD (Offshore)
- **Twente / Eindhoven**(蘭): External PhD ルートあり。制御・ロボティクスは強い。未調査

---

## 【2026-09-28 追加】ランキング上位校の横断調査

必須条件を「研究拠点を日本に置ける(**現地滞在は在籍期間の合計12か月程度まで**)× 在職可」に緩和した(`misc/remote-phd-feasibility.md` 追記5)。これを受けて、QS World University Rankings 2026 の上位校から、来校を伴えば日本拠点・在職のまま取れる道があるかを洗い出した。

A = 日本拠点で研究可(現地滞在合計12か月以内) / B = パートタイム・在職可 / C = 分野の受け皿

**調査の確度**: 一次調査(サブエージェントによる公式ページ確認)。Oxford・UCL の公式PDFは本文を取得できず、検索スニペットからの引用。QS順位は二次集計サイトの表からで、一部のみ公式発表と照合済み。学費の「?」は数字を取得できなかったもの。

### 英国

| 大学 | QS2026 | A | B | C | 総合 | 要点 |
|---|---|---|---|---|---|---|
| Oxford | 4 | △ | ○ | ◎ | △〜○ | PT は年52日以上 Oxford で活動。6〜8年で合計10〜14か月と上限ぎりぎり。Visitor で来校し英国外に拠点を置く形を大学が想定 |
| **Cambridge** | 6 | ○ | ○ | ◎ | **○** | PT に正式な居住要件なし、年約45日の来校が目安。PT 学生の Visitor ルートを大学が明示 |
| Imperial | 2 | △ | ○ | ◎ | △ | `labs/imperial.md` |
| UCL | 9 | △ | ○ | ○ | △ | Non-Resident PhD は他機関に所属する人向け(独立性と衝突) |
| KCL | 31 | △ | ○ | ○ | △ | 英国外拠点は例外扱い。6か月以上の来校と日本側の受入機関が要る |
| Edinburgh | 34 | × | △ | ◎ | × | IPAB・Engineering は on-campus のみ |
| Manchester | 35 | × | △ | ○ | × | 英国外拠点は split-site(機関間協定)のみ |
| **Bristol** | 51 | ○ | ◎ | ○ | **○** | 全学の遠隔PhD方針あり。来校は初年度2週 + 以降1週〜毎年2週。**学科ごとに提供するか決める** |
| **Warwick (WMG)** | 74 | ◎ | ◎ | ◎ | **◎** | 海外拠点の研究学生向けガイドラインあり。来校は年4週が目安、受入機関は不要。PT 5〜7年 |
| Birmingham | 76 | ○ | ○ | △〜○ | △〜○ | Split Location 制度あり。ただし工学系の講座ページは「In person」表記 |
| Glasgow | 79 | × | △ | ○ | × | 遠隔は企業が社員を選ぶ Partnership PhD のみ |
| Leeds | 86 | △ | ○ | △〜○ | △ | 遠隔PhDは ITS(交通研究所)など一部のみ |
| **Southampton** | 87 | ◎〜○ | ○ | ○ | **◎〜○** | 全学の PhD by Distance Learning ポリシーあり。海外在住可、原則来校不要、PT 可 |
| Sheffield | 92 | △ | △ | ◎ | △ | Remote Location は海外の機関で研究することが前提 |
| Durham | 94 | × | △ | ○ | × | split-site はフルタイム限定 |
| Nottingham | 97 | ○ | ○ | △ | ○ | 入学後に study away を申請(自宅も可) |
| St Andrews | 113 | ◎ | ○ | △ | ○ | 全課程オンライン可(2026年8月規定化)。工学部なし |

### 英国以外

| 大学 | 国 | QS2026 | A | B | C | 総合 | 要点 |
|---|---|---|---|---|---|---|---|
| ETH Zurich | 瑞 | 7 | △ | × | ◎ | × | 学外研究には受入機関の確約が要る |
| NUS / NTU | 星 | 8 / 12 | × | × | ◎ | × | PT はシンガポールの就労パスが前提 |
| HKU / HKUST | 港 | 11 / 44 | × | △ / × | ◎ | × | HKU の PT でも香港外は年6か月まで |
| Melbourne / UNSW | 豪 | 19 / 20 | × | × | ◎ | × | 「PhDs cannot be studied online」/ 豪州への移住が前提 |
| EPFL | 瑞 | 22 | △ | × | ◎ | × | 勤務時間の50%を博士研究に充てる雇用主の文書が要る |
| Sydney | 豪 | 25 | △ | △ | ◎ | △ | 国際学生の遠隔在籍について公式記載なし |
| McGill / UBC | 加 | 27 / 40 | × | × | ○ | × | residence 要件あり |
| Toronto | 加 | 29 | △ | △ | ◎ | △〜× | Flex-time PhD は雇用主の関与が要件 |
| **ANU** | 豪 | 32 | ○ | △ | ◎ | **○** | 海外からの external 在籍を規程に明記。来校は off-campus 12か月ごとに4週 |
| Monash / UQ / UWA / Adelaide | 豪 | 36 / 42 / 77 / 82 | △ | △ | ○〜◎ | △ | 国際学生のPT不可はビザ起因。遠隔の条件が不明、または短期扱い |
| KTH / Chalmers | 瑞典 | 78 / 165 | △ / × | × | ◎ / ○ | × | 博士学生は大学雇用か産業博士(雇用主協定)が基本 |
| DTU | 丁 | 107 | △ | △ | ○ | △〜× | Industrial PhD はデンマーク企業向け |
| **Aalto** | 芬 | 114 | ○(推測) | ◎ | ○ | **○〜◎** | 資金なしの PT を明記、**学費ゼロ**。ただし「一部期間フィンランド居住」の条件 |
| Waterloo | 加 | 119 | △ | △ | ◎ | △ | 修士卒は4学期以上のフルタイム residence |
| **TU/e** | 蘭 | 140 | ○(推測) | ◎ | ◎ | **◎〜○** | 自費の外部PhDを明記、年€7,000 |
| **Twente** | 蘭 | 203 | ○(推測) | ◎ | ○ | **○** | 非雇用博士候補者は年€3,000。対象に「本業の傍ら自分の時間で研究する会社員」を明記 |
| NTNU | 諾 | 267 | △ | △ | ◎ | △ | 合計1年以上 NTNU に滞在(短縮可)、全期間の資金証明が要る |
| Auckland | 新 | 65 | × | × | ○ | × | PT は NZ 国内学生のみ |

米国の上位校には、在職のまま遠隔で取れる PhD は見当たらなかった。

### 有望校の詳細

#### Warwick (WMG) — 条件・分野とも最も整っている

- 学外拠点の研究学生向けガイドラインの対象に「students based overseas … not intending to visit the University on a regular basis」とある。来校は**年4週**が目安(PT 6年で合計約6か月)。現地指導者は任意で、受入機関は不要
- 学費(2026-27, Overseas): FT £33,110 / **PT £19,866(FTの60%)** → 6年で約£119,000
- 分野: **WMG Safe Autonomy**(Siddartha Khastgir、シミュレーションによる自動運転の安全性検証)
- 出典: [Research students based away from the University](https://warwick.ac.uk/services/dc/policy/pgraway/) / [PGR fees](https://warwick.ac.uk/services/finance/studentfinance/fees/pgr/)

#### Southampton — 制度の文面が最も明確

- 「main place of residence is outside of Southampton, either in the UK or overseas」「would not normally be expected to attend … campus in-person」。PT 可
- 設備は雇用先などが提供するか「available locally」であること → 個人の計算環境で満たせる見込み(推測)
- **ATAS が要るテーマは遠隔不可**とあるが、**日本国籍は ATAS 免除**なので該当しない見込み(推測。Imperial の ATAS ページで免除国に Japan を確認済み)
- 学費(ECS, 2026/27): FT £27,300 / **PT £13,650** → 6年で約£82,000
- 分野: ECS の Agents, Interaction and Complexity(マルチエージェント)、Vision, Learning and Control
- 出典: [PhD by Distance Learning Policy](https://www.southampton.ac.uk/~assets/doc/quality-handbook/PhD%20by%20Distance%20Learning%20Policy.pdf)

#### Bristol — 最低来校が極小

- 最低来校は「a two-week visit within the first year of study, plus a further visit in a later year of study of at least one week」。FT・PT とも可、PT 最長8年
- 雇用先の施設・データに依存しなければパートナー協定は不要
- ただし「**Schools must decide whether they wish to offer**」。CS・Aerospace の講座ページは On-Campus 表記のみ → 学科が提供するか要確認
- 学費: International FT £28,300(PT は約£14,150と推測)
- 分野: Arthur Richards(MPC・マルチエージェント)、Sabine Hauert(スウォーム)
- 出典: [Distance learning (Code of Practice)](https://www.bristol.ac.uk/academic-quality/pg/code-of-practice/information/distance-learning/)

#### Cambridge — 最上位で成立しうる

- 「there are no formal residence requirements for part-time programmes … we would expect you be in attendance in Cambridge for around 45 days per year」。PT は 60% / 75% を選択、60%で提出期限は最長7年 → 合計7.5〜10か月
- Visitor: 「Students on part-time postgraduate courses who spend most of their study time outside the UK … can do so using Visitor immigration permission」(ただし頻繁な連続訪問は想定外との注意書きあり)
- CST(計算機科学科)の追加条件: 年45泊以上、**雇用主の休暇許可レター**(休暇の許可のみで共同研究は求められない)、「must live close enough … or be able to spend enough time in Cambridge during the first two years」→ 1〜2年目は来校が多くなりそう(推測)
- 分野: **Amanda Prorok**(CST、マルチロボット)、工学部の制御グループ
- 出典: [Part-time graduate study](https://www.postgraduate.study.cam.ac.uk/download/part-time-graduate-study-information-prospective-students) / [Visa study](https://www.internationalstudents.cam.ac.uk/visa-study) / [CST part-time PhD](https://www.cst.cam.ac.uk/admissions/phd/part-time-phd-degree)

#### TU/e(オランダ)— 分野の受け皿が最も強い

- 自費の外部PhDを明記: 「finance their trajectory themselves」。要件は「A research proposal and agreement from a TU/e supervisor」
- 学費: 「€7,000 annually (standard rate)」(高価な設備を使う場合は €32,000/年)→ 6年で約€42,000
- 最低滞在期間の記載なし。滞在は promotor との合意次第(推測)。雇用主の関与は不要
- 分野: **Nathan van de Wouw**(自動運転・CACC)、**Mircea Lazar**(MPC・マルチエージェント制御)
- 出典: [How to become a PhD candidate](https://www.tue.nl/en/education/graduate-school/phd-at-tue/how-to-become-a-phd-candidate)

#### Aalto(フィンランド)— 学費ゼロ

- 「it is possible to start pursuing doctoral studies without funding (part-time doctoral studies)」「Aalto University doctoral studies are free of tuition fees」。修了目安4〜8年
- PT 生の定義は「main occupation outside the School of Engineering which occupation does not include scientific research for a doctoral thesis」。雇用主の書類は FT 生のみ
- **懸念**: 「you need to reside in Finland at least part of the study time」。期間の記載なし → 要確認
- 分野: Kari Tammi(自動運転車両・シミュレーション)、Ville Kyrki(Intelligent Robotics)、Dominik Baumann(マルチエージェント学習制御)
- 出典: [Aalto Doctoral Programme in Electrical Engineering](https://www.aalto.fi/en/study-options/aalto-doctoral-programme-in-electrical-engineering)

#### ANU(豪州)

- 「An international candidate may be studying onshore or from an offshore location」「must attend the ANU campus for 4 weeks in every 12 months of study off-campus」(変更申請可)
- PT は「International applicants on a student visa are expected to study full-time」→ ビザ起因。ビザ不要の海外在住者が PT を選べるかは要確認
- 学費: 未取得(公式ページが403)
- 分野: Rob Mahony / Jochen Trumpf(状態推定・オブザーバ)、Iman Shames(マルチエージェント最適化)
- 出典: [ANUP_012809](https://policies.anu.edu.au/ppl/document/ANUP_012809) / [ANUP_7869072](https://policies.anu.edu.au/ppl/document/ANUP_7869072) / [External Status 申請書](https://www.anu.edu.au/files/2024-03/Application%20for%20External%20Status%202024.pdf)

#### Twente(オランダ)

- 2026年4月施行の fee policy で、非雇用の博士候補者は「an annual tuition fee of € 3,000」。対象に「an employee of a company who conducts doctoral research on their own time on top of their regular job」を明記 → **自分の状況にほぼそのまま当てはまる**
- 居住地の制限は記載なし。任意で bench fee が加わる可能性あり
- 分野: Robotics & Mechatronics(Stramigioli)、Antonio Franchi(複数機の協調制御)。TU/e より受け皿は薄い
- 出典: [UT fee policy for non-employed doctoral candidates](https://www.utwente.nl/en/service-portal/resources/faculties/tgs/ut-fee-policy-for-non-employed-doctoral-candidates.pdf)

### 横断的に分かったこと

- **研究拠点を学外に置く制度は3つの型に分かれる。** 自分に使えるのは (1) だけ
  1. 本人が単独で学外にいてよい型(Warwick、Southampton、Bristol、ANU、オランダの外部PhD)
  2. 学外の受入機関・雇用主が要る型(Imperial PRI、UCL Non-Resident、KCL、Sheffield、Glasgow Partnership、北欧の産業博士)→ 独立性の条件と衝突
  3. 学外拠点の制度はなく、来校日数だけで管理する型(Oxford、Cambridge)→ 合計日数が上限内なら成立
- ビザ論法は今回も多数の大学で当てはまった(Oxford、Cambridge、UCL、Warwick、豪州各校)
- **学費はオランダが桁違いに安い**(Twente €3,000/年、TU/e €7,000/年)。Delft の bench fee €10,000/年と比べても安い

## 【2026-10-01 追加】正規 PhD の費用比較

`misc/funding.md` の結論(学費をまとめて出す給付型の制度は実質ない)を受けて、自費で払う総額で候補を比べ直した。

### 6年の総費用(大学に払う分)

換算は £1 ≒ €1.15 で概算。渡航費と滞在費は含まない(NTNU だけは滞在が必須なので、生活費の目安を併記した)。

| 大学 | 6年の総額 | € 換算 | 必須の来校・滞在 | 分野の受け皿 | 在職・日本拠点 |
|---|---|---|---|---|---|
| **Twente** | €12,000〜18,000 | €12k〜18k | qualifier(6〜9か月目)と defence。対面が前提と読める(推測) | △〜○ | ○ |
| **TU/e** | €0〜42,000(減免しだい) | €0〜42k | defence はキャンパスで対面(オンラインは「highly exceptional cases」のみ) | **◎** | ○ |
| **NTNU** | 学費ゼロ + 1年の滞在費(約€16,000、推測) | 約€16k | 合計1年(分割可) | **◎ 船舶の自律システム**(Fossen、Breivik、Johansen、Lekkas) | △ 時間要件と勤務先の合意書(勤務先との相談しだい) |
| Reading | £67,800(PT £11,300/年) | 約€78k | 条件付き(要確認) | ? | ○ |
| TU Delft | 約€71,000 | €71k | 不明 | ◎ | ○ 地理的範囲が不明 |
| Swansea | 約£70,800 | 約€81k | なし | △ | ◎ |
| Southampton | 約£82,000 | 約€94k | 原則不要 | ? | ◎〜○ |
| York | 約£96,000(PT は半額と仮定) | 約€110k | なし | ◎ | ◎ |
| Imperial | 約£97,000 | 約€112k | PRI / Split が前提 | ◎ | △ |
| Warwick | 約£119,000 | 約€137k | 年4週 | ◎ | ○ |

### 分かったこと

- **TU/e は分野の適合と費用を両立する唯一の候補。** 減免がなくても€42,000で、英国の distance PhD の半分以下になる
  - Dynamics & Control の Nathan van de Wouw は「cooperative and autonomous driving」が研究分野で、自動運転の motion planning の PhD 論文が続けて出ている(2024・2026)
  - EE の Control Systems には Roland Tóth(自律車両の運動制御と CPS の形式検証)、Mircea Lazar(MPC)、Autonomous Motion Control Lab がある
- **Twente は最安。** 本人の形が規程の「category 4」そのもの(会社員が本業の傍ら自分の時間で研究する)
  - 自動運転の経路計画・制御の教授は TU/e より少ない
  - 30 EC の教育要件があり、必須の2科目にはオンライン回がある
- **NTNU は分野が最も合う。** Engineering Cybernetics は船舶の誘導・航法・制御の世界的な拠点で、本人の専門に近い。学費もゼロ。課題は制度で、次の2点が要る
  - 時間要件: 研究に勤務時間の50%以上を充て、通常1年は80%以上をフルタイム研究に割り当てる
  - 3者間の doctoral agreement(本人・NTNU・勤務先): 雇用されているだけで必須(規程 §7-2)。勤務先が時間の確保・知財・公開の条項に署名する
  - → 今の勤務先との取り決め(関与しない)とはぶつかるが、**取り決めは進学先が具体的になった段階で改めて相談する**ので、これだけで外さない。勤務時間外に自費で研究する人にも同じ契約を求めるかは NTNU に照会する
- オランダ2校のビザ: 日本国籍は90日/180日まで査証なしで滞在できる。短期の訪問だけなら居住許可は要らない見込み(推測。大学の明文はない)

### 照会で確かめること

- TU/e: 減免の実例と額、パートタイムの最大年限と学費の按分、Go/No-Go 審査の有無、日本在住の外部PhDの前例
- Twente: フルタイム勤務の外部PhDをどの在籍率で登録するか(67%なら年€2,000×6年)、qualifier と年次面談をオンラインで受けられるか
- NTNU: 勤務時間外に自費で研究する候補者に、時間要件と doctoral agreement をどう適用するか。滞在1年を短縮できるか

### 出典

- Twente: [Fee policy](https://www.utwente.nl/en/service-portal/resources/faculties/tgs/ut-fee-policy-for-non-employed-doctoral-candidates.pdf) / [PhD Charter 2026](https://www.utwente.nl/en/education/tgs/currentcandidates/phd/downloads/phd-charter-english.pdf) / [Doctoral Regulations 2026](https://www.utwente.nl/en/education/tgs/currentcandidates/phd/downloads/ut-doctoral-regulations.pdf) / [Introductory Workshop](https://www.utwente.nl/en/courses/1827587/1a.-phd-engd-introductory-workshop-incl-academic-integrity/)
- TU/e: [How to become a PhD candidate](https://www.tue.nl/en/education/graduate-school/phd-at-tue/how-to-become-a-phd-candidate) / [Doctoral Regulations Nov 2025](https://assets.w3.tue.nl/w/fileadmin/content/Our_University/Werken%20bij/TUe%20Doctoral%20regulations%202025%20-%20incl%20DMP.pdf) / [Nathan van de Wouw](https://www.tue.nl/en/research/researchers/nathan-van-de-wouw) / [Control Systems](https://www.tue.nl/en/research/research-groups/control-systems)
- NTNU: [PhD regulations 2026-02-03](https://www.ntnu.edu/documents/1283270912/0/NTNU+PhD-regulations+updated+20260203.pdf) / [Engineering Cybernetics 出願](https://www.ntnu.edu/studies/phtk/apply-and-admission) / [UDI](https://www.udi.no/en/want-to-apply/work-immigration/vocational-training-and-research/)

## 【2026-10-01 追加】3軸(分野・学費・滞在)での全候補の再評価

前提の変更:
- 分野は自律移動・自動運転なら船舶・自動車・ロボットのどれでもよい
- 勤務先との取り決めは進学先が決まってから相談し直すので、それだけを理由に外さない(次のアクション10)
- 評判(ランキング・分野での知名度)も参考に加える

円換算は仮定のレート(£1≈200円、€1≈170円、A$1≈100円、CA$1≈110円)。学費は単価×年数で、在籍中の値上げは含めない。

### Tier S: 分野が合い、学費が安く(6年で約700万円以下)、滞在も収まる

| 大学 | 国 | 分野 | 6年の学費 | 合計滞在 | 条件・懸念 | 評判(QS2026 / THE Eng 2026) |
|---|---|---|---|---|---|---|
| **TU/e** | 蘭 | ◎ 自動運転・MPC | €0〜42k(0〜約710万円) | defence のみ(+α) | 減免は学科長の裁量 | 140 / 84。QS分野: EEE 65・Mech 60。Automotive Campus と TNO の連携 |
| **Twente** | 蘭 | ○ ロボット・ドローン | €12〜18k(約200〜310万円) | qualifier と defence | 自動運転の教員は少ない。2025年に S&T 学部で8研究グループ閉鎖 | 203 / 126–150。QS分野: Mech 142 |
| **Plymouth** | 英 | ◎ 海洋自律(CMAST、National Centre for Marine Autonomy) | £29.0k(約580万円、海外研究 PT £4,830×6)。日本の消費税が上乗せされる可能性 | 年6週以上(2017年版規程。現行は未確認)→ 6年で約8か月 | **日本側の現地指導者(local supervisor)が要る**。資格要件は非公開 | QS分野: 工学・CS は圏外、Earth & Marine 101–150。2025年に351人削減(芸術系中心) |
| **MUN**(Memorial) | 加 | ◎ 海洋自律(AOSCENT:UUV・USV・航法) | CA$26.8k(約300万円) | 原則3学期(約12か月)。Dean の承認があれば学外で満たせる | 学外で満たすには承認が要る | QS分野: 工学・CS は圏外、Earth & Marine 201–275。2025年に赤字で20人解雇 |
| **NTNU** | 諾 | ◎ 船舶の GNC(Fossen ら) | 0 + 1年の滞在費(約270万円) | 合計1年(分割・短縮可) | 時間要件(勤務時間の50%以上)と3者間の合意書 | 267 / =97。QS分野: EEE 99・Mech 79。自律船では世界の中心 |
| **USN** | 諾 | ○ 自律船(MASS、遠隔運航センター) | 0 + 滞在費 | 原則1年(2回に分割・短縮可)。規程 §3-6 で確認 | **自費で入れるのは PhD in Technology のみ**(Nautical Operations は自費不可)。全期間の資金証明と3者間の合意書 | QS分野: いずれも圏外。2028年までに72FTE以上の削減 |
| **Aalto** | 芬 | ○〜◎ 自動運転車・ロボット・自律船の安全 | 0 | 「一部期間フィンランドに居住」(月数は公式に記載なし) | 居住期間を要確認 | 114 / 101–125。QS分野: EEE 135・CS 142 |
| LJMU | 英 | △〜○ 海事の安全・リスク(制御・知覚は弱め) | £26.6k(約530万円、総額固定) | ほぼ0(viva はオンライン可) | 規程に国際学生向けの distance PhD を明記 | QS分野: CS 751–850 のみ。2024〜26年の削減報道なし |

### Tier A: 分野が合い、学費は中程度(約1,200〜1,700万円)

| 大学 | 国 | 分野 | 6年の学費 | 合計滞在 | 条件・懸念 | 評判 |
|---|---|---|---|---|---|---|
| **TU Delft** | 蘭 | ◎ マルチロボット・自律船(Negenborn) | 約€71k(約1,200万円)。減免は学部の裁量 | 不明 | 3mE が海外在住の外部PhDを受け入れるか。**2028年までに大学予算の PhD ポスト148以上減、機械工学127FTE減** | 47 / **16**。QS分野: EEE 14・Mech 9 |
| Sheffield(Remote Location) | 英 | ○ | £72〜81k(約1,440〜1,620万円) | 規定なし | 海外の受入機関が要る。企業でもよいかは不明 | 92 / =97 |
| Southampton | 英 | ○(海洋ロボットは◎だが、工学系の distance PhD は未確認) | 約£82k(約1,640万円) | 原則なし | 工学系の学科が受け入れるか | 87 / 101–125 |
| **Flinders** | 豪 | ◎ 自律海洋機(Sammut) | 約A$134k(約1,340万円、年 A$44,800 の PT 50% と仮定) | 0(Online 在籍、来校不要と規程に定義) | 海外の留学生の PT はアーカイブの公式 FAQ で可。最低滞在の規定は見つからず。2025年に海洋科学を含むリストラ案 | QS分野: いずれも圏外 |
| UTAS(AMC) | 豪 | ○ | 約A$136k(約1,360万円、推測) | 不明 | 海外在住の PT が可能か不明 | 未調査 |

### Tier B: 分野・評判は強いが、学費が高い(約1,900万円以上)

| 大学 | 6年の学費 | 合計滞在 | 条件・懸念 | 評判 |
|---|---|---|---|---|
| York | £96〜104k(推定) | 入学時の5日 + 最終試験 | 国際学生の PT 料金は非公表 | 169 / 251–300。安全性保証に特化 |
| Bristol | £85〜104k | 約3週 | 学科が distance を提供するか | 51 / 100。Bristol Robotics Lab |
| Strathclyde | 約£96〜98k(2026-27 FT £31,900〜32,800 の PT 50% と仮定。PT の工学 PhD 料金は非公表) | 未確認 | 海外在住の PT が可能か不明。distance PhD の制度はない | QS分野: EEE 139・Mech 124。自律船(MSRC)。£35m の資金不足で76ポスト削減 |
| Imperial(PRI) | £97〜104k | 合計12か月(年2か月以上) | 勤務先を研究拠点として承認してもらう | 2 / 12。CSRankings Robotics で英国1位 |
| Newcastle | 約£100k | 規定なし | 学部長の承認、産業スポンサーがあると有利 | 未調査 |
| KCL | 約£104k | 6か月以上 | 勤務先側の指導者 | 31 / 126–150 |
| Oxford | 約£109k | 約10か月(年52日) | 上限ぎりぎり | 4 / 2。Oxford Robotics Institute |
| Warwick(WMG) | 約£119k | 約6か月 | - | 74 / 176–200。自動運転の安全性 |
| Cambridge | 約£128k(PT でも総額はフルタイムと同じ) | 約9か月(年45泊以上) | 勤務先の休暇許可レター | 6 / 5 |
| UTS | A$148〜198k | 0 | 2025年に約400職の削減と約150コースの募集停止(報道) | 96 / 101–125 |
| ANU | A$168〜224k | 約5.5か月(年4週) | dual-use の審査で external が不可になる可能性(推測) | 32 / 101–125 |

### Tier C: 分野が弱い、または制約が大きい

- Swansea: 分野△(£71k、滞在なし)
- UOW: 分野△。PT 学生は「should not undertake more than 30 hours a week of paid work」→ **フルタイム勤務とぶつかる可能性**
- Cranfield: 分野△(自律は航空・防衛)、正式な distance 制度なし
- Heriot-Watt: 分野◎(水中ロボット、Ocean Systems Lab)。規程に Off Campus の在籍があり、最低来校の規定なし、勤務先に副指導者を置ける。ただし off-campus の学費・bench fee は非公表(FT 国際 £27,080)。2024-25年はスコットランド最大の赤字

### 外れたもの(滞在または制度が合わない)

- EPFL: 学外研究は例外の承認制で、雇用主が勤務時間の50%以上を博士研究に充てると文書で約束する必要がある
- Toronto Flex-time: 最初の4年はフルタイム登録で対面
- KTH / Chalmers: 産業博士は学内で過ごすことが前提
- Reading: 在籍期間の最大1/3は来校が想定されている
- Dalhousie: フルタイムのみ
- HVL: 自費は原則不可
- PhD in Nautical Operations(ノルウェーの共同プログラム): 自費不可で、12か月の在籍が必須
- その他、2026-09-28 の節で × とした大学

### 分かったこと

- **候補は約30校で、学費・滞在・分野の3つが揃うのは Tier S の8校**(TU/e・Twente・Plymouth・MUN・NTNU・USN・Aalto・LJMU)
- **船舶に広げたことで、安い候補が増えた。** Plymouth(約590万円)と MUN(約300万円)は分野も◎
- 英国・豪州の評判の高い大学は、6年で約1,900〜2,500万円かかる。オランダ・北欧・カナダの3〜4倍
- 評判の指標の注意
  - CSRankings は CS 系の学科の教員しか数えないので、機械系・海洋系が強い大学(TU Delft、NTNU、WMG)は実力より低く出る。自動運転・自律船の評価には向かない
  - THE の工学部門では TU Delft(16位)が Imperial(12位)と並ぶ
- 英国の PhD 学生の満足度調査(PRES 2025)は全国値のみで、総合満足度83%。「コミュニティの一員と感じる」は61%と低く、遠隔・PT では孤立感に注意が要る

### 未確認(WebSearch の上限で止まったもの)

→ 2026-10-02 に補完した(次の節)。

### 出典(今回追加分)

- 評判: [THE 2026 JSON](https://www.timeshighereducation.com/json/ranking_tables/world_university_rankings/2026) / [THE Engineering 2026](https://www.timeshighereducation.com/json/ranking_tables/engineering_technology_rankings/2026) / [CSRankings データ](https://raw.githubusercontent.com/emeryberger/CSrankings/gh-pages/generated-author-info.csv) / [PRES 2025](https://advance-he.org/knowledge-hub/postgraduate-research-experience-survey-2025/) / [UTS の削減(Guardian)](https://www.theguardian.com/australia-news/2025/sep/03/uts-job-cuts-paused-safework-nsw-warning)
- Plymouth: [PhD Mechanical Engineering](https://www.plymouth.ac.uk/courses/postgraduate/phd-mechanical-engineering) / [PGR fees 2026-27](https://www.plymouth.ac.uk/study/fees/tuition-fees-for-postgraduate-research-students-2026-27) / [Marine autonomy](https://www.plymouth.ac.uk/research/marine-autonomy)
- MUN: [Calendar 4.3](https://www.mun.ca/university-calendar/school-of-graduate-studies/school-of-graduate-studies/4/3/) / [Graduate tuition](https://www.mun.ca/finance/graduate-student-tuition-and-fees/)
- LJMU: [Fee information](https://www.ljmu.ac.uk/the-doctoral-academy/pgr-project-timeline/fee-information) / [Research degrees regulations](https://www.ljmu.ac.uk/-/media/staff-intranet/research/doctoral-academy-new/research-degrees-framework-documents/research-degrees-regulations.docx)
- USN: [PhD regulations](https://www.usn.no/getfile.php/13425926-1768900904/usn.no/en/About%20USN/Rules%20and%20regulations/Regulations%20for%20the%20degree%20of%20philosophiae%20doctor%20%28PhD%29%20at%20USN.pdf)
- Newcastle: [PhD by Distance 規程](https://www.ncl.ac.uk/mediav8/university-regulations/files/2026-27/2627%2013%20XIII%20Specific%20Progress%20Regs%20Doctor%20Master%20of%20Phil%20Distance%20Progress.pdf)
- Heriot-Watt: [PGR Code of Practice](https://www.hw.ac.uk/document-library/professional-services/registry-services/academic-registry/cop-pgr.pdf)
- Flinders: [HDR Policy](https://www.flinders.edu.au/content/dam/documents/staff/policies/academic-students/higher-degrees-research-policy.pdf)
- Cambridge: [Fees API](https://2027.gaobase.admin.cam.ac.uk/api/courses/EGEGPDPEG/financial_tracker.html?fee_status=O&part_time=on) / Oxford: [DPhil Engineering Science](https://www.ox.ac.uk/admissions/graduate/courses/dphil-engineering-science) / Bristol: [PGR overseas fees](https://www.bristol.ac.uk/students/support/finances/tuition-fees/pgr/overseas/) / ANU: [9715XPHD](https://programsandcourses.anu.edu.au/2026/program/9715xphd) / UTS: [Course fees](https://cis.uts.edu.au/fees/course-fees.cfm) / UOW: [HDR Award Rules](https://policies.uow.edu.au/document/view-current.php?id=3) / Sheffield: [Study away](https://sheffield.ac.uk/postgraduate/away) / KCL: [Academic Regulations](https://www.kcl.ac.uk/assets/arqs/academic-manual/current-year/academic-regulations.pdf) / Imperial: [Regulations 2025-26](https://www.imperial.ac.uk/media/imperial-college/administration-and-support-services/registry/academic-governance/public/regulations/2025-26/MPhil_PhD_Regulations_2025_26-v3.1.pdf)

## 【2026-10-02 追加】評判・制度の補完調査

2026-10-01 に WebSearch の上限で止まった項目を埋めた。Tier の表には要点だけを反映した。

### 分かったこと

- **Tier S の先頭は TU/e のままでよい。** 工学の QS 分野別順位が Tier S で最も高く(EEE 65・Mech 60)、解雇の報道もない
- **船舶系の Tier S(Plymouth・MUN・USN)は、工学ランキングでは圏外。** 分野の適合は◎でも、工学での名前の通りは弱い。QS には海洋工学の分野がなく、理学系の Earth & Marine Sciences にだけ入る
- **Plymouth は滞在の見通しが立った。** 海外研究の料金は PT で年£4,830(Band 2)。2017年版の規程では「海外拠点の学生は年6週以上の来校が必須」で、6年なら約8か月。現行の規程はログインが要るので照会で確認する
- **USN は自費だと PhD in Technology の1択。** 同じ USN でも PhD in Nautical Operations は「Admission is not granted for self-financed PhD students」
- **Flinders は Tier A で最も遠隔に向く。** 規程に「Online — … No in person attendance is required」の在籍形態があり、2025年4月時点の公式 FAQ では海外の留学生も PT で在籍できる。フルタイム勤務なら勤務先の確認書を求められることがある
- **TU Delft はさらに厳しくなった。** 予算削減で大学予算の PhD ポストを減らし、PhD 候補者の教育負担を増やしている。外部 PhD の受け入れに余裕があるかは疑わしい
- **UCL Non-Resident は2026/27に廃止。** 「Distance Learning Off-Campus status」に置き換わり、学費は通常の100%。規程の例外扱いとして、学科が個別に申請する形
- 財政難・人員削減の報道は22校中20校にある(ないのは LJMU と Aalto)。英国・豪州・オランダ・ノルウェーのどこでも起きているので、それだけで候補を外すのではなく、**分野の学部・研究グループが直接対象か**で見る

### 評判: QS World University Rankings by Subject 2026

QS 公式サイトは403で読めず、QS 2026 の表を転載したサイトで確認した。「—」は転載サイトの表に見つからないという意味で、圏外と確定したわけではない(表から行が抜けている可能性がある)。

| 大学 | EEE | Mech/Aero/Mfg | CS & IS | Earth & Marine |
|---|---|---|---|---|
| TU/e | 65 | 60= | 111= | — |
| Twente | 201-250 | 142= | 351-400 | 101-150 |
| Plymouth | — | — | — | 101-150 |
| MUN | — | — | — | 201-275 |
| NTNU | 99= | 79= | 201-250 | 101-150 |
| USN | — | — | — | — |
| Aalto | 135 | 151-200 | 142 | — |
| LJMU | — | — | 751-850 | — |
| TU Delft | 14 | 9= | 50 | 21 |
| Sheffield | 119= | 63 | 169= | 201-275 |
| Southampton | 87= | 81= | 178= | 40 |
| Flinders | — | — | — | — |
| UTAS | — | — | — | 51-100 |
| York | 251-300 | — | 201-250 | — |
| Bristol | 151-200 | 66= | 111= | 18 |
| Strathclyde | 139= | 124 | 301-350 | — |
| Imperial | 9 | 9= | 12 | 15 |
| Newcastle | 151-200 | 201-250 | 180= | 101-150 |
| KCL | 95= | 151-200 | 46 | 201-275 |
| Oxford | 7 | 7= | 4= | 2 |
| Warwick | 139= | 125= | 84 | — |
| Cambridge | 6 | 4 | 8 | 3 |
| UTS | 64 | 118= | 55 | 151-200 |
| ANU | 67 | 125= | 48 | 20 |
| Heriot-Watt | 151-200 | 251-300 | 301-350 | 201-275 |
| Swansea | 301-350 | 151-200 | 201-250 | — |
| UOW | 201-250 | 151-200 | 351-400 | 151-200 |
| Cranfield | 301-350 | 55 | 501-550 | — |

### 評判: 財政難・人員削減の報道(2024〜2026年)

分野(工学・CS・海洋)の部門が直接対象になっているかを重視して要約する。

| 大学 | 要点 | 分野の部門への影響 |
|---|---|---|
| TU/e | 政府の削減で成長計画を停止、全学科に削減を指示。地域投資(Beethoven)で最悪は免れた。解雇の報道なし | 小 |
| Twente | Faculty of Science & Technology を再編。63人が対象、46人を解雇、8研究グループを閉鎖(2025-02) | **あり** |
| TU Delft | 2028年から年€79mの削減、学部ごとに10%。大学予算の PhD ポスト148以上減、機械工学127FTE減 | **あり** |
| オランダ全体 | 高等教育・研究の予算を年€500m超削減 | - |
| Plymouth | 収入が10%減り、351人を削減(主に希望退職)。学生側の報道では芸術・デザイン・建築が中心 | 報道なし |
| MUN | 2025-26年度に$6.7mの赤字、$20mの支出削減、20人の解雇 | 報道なし |
| NTNU | 2025年末に前年比294FTE減。医学・教員養成が中心 | 報道なし |
| USN | 2023年以降73FTE減、5プログラム閉鎖。2028年までに NOK 140m・72FTE以上の削減が必要 | 不明 |
| Aalto | 大学単位の報道なし。フィンランド全体で高等教育予算を削減 | - |
| LJMU | 2024〜26年の報道なし | - |
| Flinders | 134FTE・164コースのリストラ案。海洋科学者6人を含む | **あり**(海洋科学) |
| UTAS | $10.8m の赤字。人文系の再編 | 報道なし |
| Strathclyde | £35m の資金不足で76ポスト削減(教育学中心)、ストライキ | 報道なし |
| Newcastle | 約300FTE削減。工学を含む SAgE 学部から£1.7m | **あり** |
| Heriot-Watt | 2024-25年の赤字£7.9mはスコットランドで最大。51ポストが対象(語学など) | 報道なし |
| York | £30m の削減に加えて£34m。2025-07に90%以上達成 | 報道なし |
| Swansea | £30m の削減、約400人が退職。2026-01に理工学部(CS・工学)も対象。学科の閉鎖はしないとしている | **あり** |
| UOW | 留学生が50%減、合計約276ポストの削減 | 不明 |
| Sheffield | £23m の人件費削減、化学科が危機 | 報道なし |
| Southampton | 最大75の教員ポストを削減(2024) | 不明 |
| Bristol | 632の削減を発表(2025-03)、のちに半減と報道 | 報道なし |
| Cranfield | 第1段階で約150人、第2段階で195ポスト(2025-08) | **あり**(大学全体が工学系) |
| ANU | 「Renew ANU」で年$250mの削減。工学・計算機の学部の統合案 | **あり** |

### 評判: 遠隔・PT・外部 PhD の口コミ

Reddit はツールから取得できず、GradCafe の投稿も見つからなかった。大学ごとの遠隔 PhD の体験談はほとんど見つからない。個人名は書かず、要旨のみ記録する。

- **英国の遠隔・PT PhD 全般**: 孤立、学科の動きが見えないこと、指導教員との距離、長年のモチベーション維持が主な苦労。対策として、指導を仕事のプロジェクトのように回す(定例会議・議題・議事録・締切)ことが挙がる。学位記に「distance」とは書かれないので、認定された大学なら雇用主には通るという声が多い
- **フルタイム勤務と PhD の両立**: 5〜7年かかり、夜と週末をすべて充てるという声が多い。本業に支障が出たという声もある
- **オランダの外部 PhD**: 全 PhD 候補者の約半数が外部。外部 PhD は満足度が最も低いグループで、遅れを見込み、研究室に溶け込めず、指導への評価も低い。学費・設備・指導の手厚さは大学ごとに大きく違う
- **ノルウェーの産業 PhD**: 公的評価で、成功の鍵は「大学の研究環境に溶け込むこと」とされる。フルリモートでは不利になりうる
- **Aalto**: 大学の2025年調査で、博士課程の約21%が PT、294人が産業・学外の共同研究先で研究し、85%が「指導教員と十分に会えている」と回答

→ 遠隔では「研究室に属している実感」を作れるかが成否を分ける。照会では、指導教員との面談頻度と、遠隔の学生がオンラインで参加できるグループの行事(定例ミーティングなど)を確認する。

### 制度・学費: 英国(Plymouth・Heriot-Watt・UCL・Strathclyde)

- **Plymouth**
  - 2026-27年の海外研究の料金(Robotics・Computing・Mechanical・EEE は Band 2): FT 年£9,655、**PT 年£4,830**。通常の国際料金は FT £19,315 / PT £9,655
  - 2024-08-01以降に入学する PT は、writing-up に入るまで最低6年の在籍が要る
  - bench fee は個別に設定し、オファーレターに書かれる
  - 「If you are studying from outside the UK, … may be required to add an applicable sales tax at your country of residence's local rate」→ 日本の消費税が上乗せされる可能性がある
  - 来校: 2017年版 Code of Practice §6.11(e)「for candidates conducting their research mainly based overseas, it is compulsory to spend at least 6 weeks a year at University of Plymouth」。現行の Handbook はログインが要り、確認できない
  - 現地指導者: Mechanical Engineering のページに「Remote supervision of overseas students is possible subject to identification of a supervisor local to the candidate」。博士号が要るか、勤務先の社員でもよいかは公開資料に書かれていない
- **Heriot-Watt**
  - PGR Code of Practice(2024-08)§2.2 に「Off Campus Research Degree Candidate」(distance learning とも呼ぶ)が定義され、Code は全面的に適用される。最低来校の規定はない
  - §2.7: 副指導者は「at the Research Degree Candidate's place of employment」でもよい
  - §5.1.3.5: 遠隔指導の追加費用は「usually covered by a bench fee」。金額は非公表
  - Institute of Sensors, Signals and Systems(Ocean Systems Lab を含む)の国際 FT 学費は£27,080(年度の表記なし)。ページの在籍形態は FT のみ
- **UCL**
  - Non-Resident は2026/27に廃止され、「Distance Learning Off-Campus status」に置き換わった。学科が規程の例外として研究科委員会に申請する
  - 学費は「charged at 100% of your usual fee」。以前の£1,500の減額はなくなった
  - 新制度の最低来校、企業を研究拠点にできるかは書かれていない。旧制度は「overseas institution … of international standing」が前提だった
- **Strathclyde**
  - 2026-27年の国際 FT 学費: EEE・Mech & Aero £32,800、NAOME(船舶・海洋工学)£31,900
  - PT は「normally calculated pro-rata」で、PT の定義は50%の負荷。ただし工学 PhD の PT 料金は書かれていない
  - EEE と NAOME に PhD part-time の入学日はある。海外在住の PT を認めるかは書かれていない(Business School の例では年10日以上の来校が必要)

### 制度・学費: Flinders・USN・HVL・Dalhousie(前回の未検証分)

- **Flinders**
  - HDR Admission and Enrolment Procedures §3: 「Online — … No in person attendance is required. [Note: this mode of delivery was previously termed 'external' …]」。§6.2.1 で海外の留学生のカテゴリとして扱われている
  - 学生ビザで豪州にいる留学生の PT は例外扱い(§6.1 c)。海外在住者には当てはまらない
  - 2025-04時点の公式 FAQ(ウェブアーカイブ): 「it is possible to undertake a HDR on a part-time basis for domestic or external international students」「expected to study for 18–20 hours per week」「If you are also working full-time, you may be asked for confirmation from your employer that study release will be made available to you」。学外で研究するには指導教員が「HDR Application for External Status」を出す
  - 学費(2026年、国際の入学者): PhD (Engineering) 年 A$44,800
  - 指導教員候補
    - Karl Sammut: Maritime Engineering & Robotics の Head。自律海洋機のミッション計画・航法・誘導・制御
    - Andrew Lammas: 状態推定・制御・経路計画
    - Thomas Chaffre: 適応制御・機械学習・コンピュータビジョン(自律移動体への応用)
- **USN**
  - 規程(FOR-2017-12-14-2411、2025-08改正)§3-6: 「PhD candidates will normally spend a minimum of one year at the institution」「may be split into two periods and may be reduced if …」→ 前回のメモどおり
  - §2-4(4) c: 「funding has not been secured for the entire period」なら不合格になりうる。§2-6(2): 外部の資金・雇用がある場合は3者間の合意書が必須
  - 最長は原則6年
  - PhD in Technology: EEE・CS・機械など。「Teaching model: Out of campus and Campus」
  - PhD in Nautical Operations: 「Admission is not granted for self-financed PhD students」「a minimum of 12-month residency」→ **自費では使えない**
  - Autonomy グループ(センサフュージョン、遠隔・ロボット航法、MASS・ROC): Christian Hovden(グループリーダー)、Fabio Augusto de Alcantara Andrade(教授)ら
- **HVL**: 「Self-financing is not normally accepted as the basis for admission」→ 前回のメモどおり外れたまま。滞在は「Dekan kan fastsette krav om residensplikt」(学部長が決める)
- **Dalhousie**: 工学の PhD は「Enrollment Options: Full-time」のみ。最初の2年で4学期の来校が原則で、資金の裏付けがないと入学できない → 外れたまま。なお PhD は留学生向けの学費がかからず、工学で年約 CA$11k

### Tier の変更

- Flinders を Tier A の中で優先度を上げる(遠隔の在籍形態が規程にあり、分野も◎)
- USN は Tier S に残すが、PhD in Technology で、滞在は約1年が前提
- TU Delft は Tier A に残すが、受け入れの見込みは下げる
- Heriot-Watt は学費が分かるまで Tier C のまま(制度は合っている)

### 照会で確認すること(追加分)

- Plymouth(doctoralcollege@plymouth.ac.uk): 年6週の来校が現行規程でも必須か。現地指導者の資格要件(博士号の要否、勤務先の社員でもよいか)。日本からの在籍で消費税が上乗せされるか
- Flinders(Office of Graduate Research): 海外在住の PT で External Status を取れるか(現行の制度)、最低来校の有無、PT の学費
- Heriot-Watt(pgr.eps@hw.ac.uk): off-campus の学費が FT と同額か、bench fee の目安、国際学生の PT 料金
- Strathclyde(EEE の PGR 事務): 海外在住の PT を認めるか、工学 PhD の PT 料金

### 出典

- QS(転載サイト): [EEE](https://xuanxiao.org/en/rankings/qs/subject/electrical-electronic-engineering) / [Mech](https://xuanxiao.org/en/rankings/qs/subject/mechanical-aeronautical-manufacturing-engineering) / [CS](https://xuanxiao.org/en/rankings/qs/subject/computer-science-information-systems) / [Earth & Marine](https://xuanxiao.org/en/rankings/qs/subject/earth-marine-sciences)
- 財政報道: [Plymouth(THE)](https://www.timeshighereducation.com/news/plymouth-says-200-roles-risk-newcastle-cuts-further-38-jobs) / [MUN(CBC)](https://www.cbc.ca/news/canada/newfoundland-labrador/mun-cuts-layoffs-1.7593368) / [USN(Khrono)](https://www.khrono.no/ma-ned-minst-72-arsverk/855419) / [NTNU(Universitetsavisa)](https://www.universitetsavisa.no/avsetninger-budsjettkutt-ntnu/ntnu-planen-mindre-penger-mindre-aktivitet/445863) / [オランダ全体(NL Times)](https://nltimes.nl/2025/02/17/dutch-universities-start-laying-workers-govt-budget-cuts-set) / [TU/e(Cursor)](https://www.cursor.tue.nl/en/news/2024/juli/week-2/cutbacks-by-incoming-government-force-tu-e-to-abandon-growth-plans/) / [Twente・Delft(Erasmus Magazine)](https://www.erasmusmagazine.nl/en/2025/02/14/university-of-twente-dismisses-dozens-of-staff-delft-also-cuts-back/) / [TU Delft(Delta)](https://delta.tudelft.nl/en/article/fewer-phd-positions-and-more-teaching-duties-for-phd-candidates) / [Flinders(ABC)](https://www.abc.net.au/news/2025-09-23/sa-flinders-uni-jobs-restructure/105795002) / [UTAS(ABC)](https://www.abc.net.au/news/2025-07-03/university-of-tasmania-confirms-job-cuts/105492096) / [Strathclyde(UCU)](https://www.ucu.org.uk/article/14403/Strikes-likely-at-Strathclyde-University-as-staff-vote-for-industrial-action) / [Newcastle(THE)](https://www.timeshighereducation.com/news/newcastle-set-axe-around-300-jobs-ps20-million-staffing-cuts) / [Heriot-Watt 財務諸表](https://www.hw.ac.uk/document-library/annual-report-financial-statements-2025.pdf) / [York](https://www.york.ac.uk/students/university-finances/what-may-change/) / [Swansea(ITV)](https://www.itv.com/news/wales/2026-01-29/plans-for-job-cuts-announced-for-one-of-wales-main-universities) / [UOW(ABC)](https://www.abc.net.au/news/2025-03-25/wollongong-university-more-staff-cut-declining-overseas-students/105092278) / [Sheffield(THE)](https://www.timeshighereducation.com/news/union-fears-400-jobs-set-go-sheffield-ps23-million-cuts) / [Southampton(THE)](https://www.timeshighereducation.com/news/university-southampton-cut-75-academic-jobs) / [Bristol(Epigram)](https://epigram.org.uk/university-of-bristol-voluntary-severance-humanities-langauges/) / [Cranfield](https://www.cranfield.ac.uk/press/news-2025/safeguarding-cranfields-future) / [ANU(ABC)](https://www.abc.net.au/news/2025-07-31/anu-job-cuts-academic-portfolio-renew-save-millions/105596738) / [Finland(University World News)](https://www.universityworldnews.com/post.php?story=20250911094637872) / [英国の削減一覧(THE)](https://www.timeshighereducation.com/news/uk-university-redundancies-latest-updates)
- 口コミ: [The Student Room](https://www.thestudentroom.co.uk/showthread.php?t=7286907) / [Pat Thomson のブログ](https://patthomson.net/2017/05/18/a-part-time-and-distance-phd/) / [PNN: external PhD candidates](https://www.hetpnn.nl/knowledge-base/external-phd-candidates) / [NIFU: 産業 PhD の評価](https://www.nifu.no/en/prosjekter/evaluering-av-naerings-ph-d/) / [Aalto 2025年調査](https://www.aalto.fi/en/news/results-of-the-doctoral-student-yearly-follow-up-2025)
- Plymouth: [PGR fees 2026-27](https://www.plymouth.ac.uk/study/fees/tuition-fees-for-postgraduate-research-students-2026-27) / [PhD Mechanical Engineering](https://www.plymouth.ac.uk/courses/postgraduate/phd-mechanical-engineering) / [2017年版 Code of Practice(第三者のミラー)](https://www.neugalu.ch/pdf/research_degrees_handbook_2017_uop.pdf) / [Regulations](https://www.plymouth.ac.uk/student-life/your-studies/essential-information/regulations)
- Heriot-Watt: [PGR Code of Practice](https://www.hw.ac.uk/uk/services/docs/academic-registry/cop-pgr.pdf) / [ISSS](https://www.hw.ac.uk/study/research/institute-of-sensors-signals-and-systems) / [Tuition fees](https://www.hw.ac.uk/students/your-money/uk-campuses/tuition-fees)
- UCL(ウェブアーカイブ経由): [Off-Campus Study](https://www.ucl.ac.uk/study/doctoral-school/regulations/essential-procedures-and-policies/campus-study) / [PGR fees 2026-27](https://www.ucl.ac.uk/study/student-finances/tuition-fees/fee-schedules/fee-schedules-2026-2027/postgraduate-research-fees-2026-2027)
- Strathclyde: [PG Fees 2026-27 v.12](https://www.strath.ac.uk/media/1newwebsite/documents/tuitionfees/16092026_PG_Fees_2026-2027_Entry_v.12.pdf) / [Fees Policy](https://www.strath.ac.uk/media/1newwebsite/documents/tuitionfees/20241212-university-fees-policy.pdf) / [EEE research](https://www.strath.ac.uk/courses/research/electronicelectricalengineering/)
- Flinders: [HDR Admission and Enrolment Procedures](https://www.flinders.edu.au/content/dam/documents/staff/policies/academic-students/hdr-admission-enrolment-procedures.pdf) / [公式 FAQ(2025-04、アーカイブ)](http://web.archive.org/web/20250419210539/https://students.flinders.edu.au/my-course/apply/hdr.html) / [Fee schedule 2026](https://www.flinders.edu.au/content/dam/documents/study/international/international-commencing-tuition-fee-schedule-2026.pdf) / [Karl Sammut](https://www.flinders.edu.au/people/karl.sammut)
- USN: [PhD in Technology](https://www.usn.no/english/research/postgraduate-studies-phd/our-phd-programmes/technology/) / [Nautical Operations の出願要件](https://www.usn.no/english/research/postgraduate-studies-phd/our-phd-programmes/nautical-operations/qualification-requirements-and-application-process-for-the-phd-in-nautical-operations) / [Autonomy グループ](https://www.usn.no/english/research/our-research-centres-and-groups/technology/autonomy/)
- HVL: [Before applying](https://www.hvl.no/en/research/phd-programmes/before-applying/) / [PhD 規程](https://lovdata.no/dokument/SF/forskrift/2024-06-24-1859)
- Dalhousie: [Graduate Calendar 2026/27](https://cdn.dal.ca/content/dam/dalhousie/pdf/academics/academiccalendar/GR_2026_2027.pdf) / [PhD fee schedule](https://www.dal.ca/content/dam/www/admissions/cost-and-payment/tuition-and-fee-schedules/phd-tuition-fee-schedule.pdf)

## 次のアクション(優先度順)

1. ~~York を個別調査~~ → **完了**(`labs/york.md`)。総合1位。残課題は**パートタイム学費レートの確認**(総額を左右する最重要項目)
2. ~~TU Delft の居住要件・リモート可否~~ → **一次調査完了**(`labs/tudelft.md`)。公式サイトで判断できる範囲は尽きた。残りは**照会案件**(3mE が外部PhDを受け入れるか、EU域外リモートが通るか)
3. ~~UOW の分野の受け皿~~ → **完了**(`labs/uow.md`)。制度◎だが受け皿△。残課題は Decision Systems Lab のメンバー特定
4. ~~Twente / Eindhoven の External PhD を調査~~ → **一次調査完了**(2026-09-28 追加の節)。どちらも自費の外部PhDを明記。残課題は日本在住のまま進められるかの確認
5. York・UTS・UOW・TU Delft への照会文面を作成(`contacts/`)。各校の未確認事項をまとめて投げる
6. `research-theme/` のテーマ具体化。York・Swansea とも出願に研究提案書が要る。【2026-09-29 決定】**個別調査と並行して進める**。指導教員候補が分かった大学から、その研究に合わせてテーマを詰める
7. 【2026-09-28 追加】ランキング上位校の有望校を個別調査(`labs/<大学名>.md`)
   - 【2026-09-29 決定】**第1陣は Warwick (WMG)・Southampton・TU/e・Cambridge の4校**。規程の原文で判定を固め、学科が遠隔を受け入れるか・パートタイム学費・指導教員候補・出願締切まで確認する
   - Bristol・Aalto・ANU・Twente は第2陣。いずれも大学への照会で決まる論点が中心なので、第1陣の後に事務照会でまとめて確認する
   - 第1陣で残った大学へ事務照会を送る(`contacts/admin-inquiries.md`)
8. 【2026-09-28 追加】年40日〜数週間の渡英に必要な休暇を、勤務先に確認する
9. 【2026-10-01 追加】費用比較の結果、**第1陣は TU/e を先頭にする**。Twente は第2陣のまま、TU/e と一緒に照会する。NTNU は分野が最も合うので候補に残し、制度面を照会する
10. 【2026-10-01 決定】**勤務先との取り決めは確定事項として扱わない。** 進学先が具体的になった段階で改めて相談するので、「勤務先との取り決めとぶつかる」ことだけを理由に候補を外さない(Imperial PRI など、学外の受入機関・雇用主が要る型も同様)
11. 【2026-10-01 追加】3軸の再評価で Tier S(TU/e・Twente・Plymouth・MUN・NTNU・USN・Aalto・LJMU)を個別調査と照会の優先対象にする。どの順に進めるかは要相談
12. 【2026-10-02 追加】評判・制度の補完が完了(2026-10-02 追加の節)。Flinders を Tier A の優先候補に上げる。Plymouth・Flinders・Heriot-Watt・Strathclyde への照会事項を追加
