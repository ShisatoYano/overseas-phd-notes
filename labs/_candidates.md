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
