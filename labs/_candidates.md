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
| **York** | 英 | Distance PhD | PT 6年 | **◎ 明記** | **◎ Centre for Assuring Autonomy 他** | **◎ 最有力** |
| **Swansea** (CS) | 英 | Distance PhD | PT 6年 | **◎ 明記** | △ 受け皿なし(要翻訳) | ○ |
| **UOW** | 豪 | Distance HDR | PT可 | **◎ 明記** | ? 未確認 | ○ |
| **UTS** | 豪 | PhD by distance | PT 最長8年 | ○ 推定 | **◎ Robotics Institute** | ○ |
| **TU Delft** | 蘭 | ? 不明 | External PhD | ? 不明 | **◎ 自律移動・制御が世界的に強い** | ? 要調査 |
| Reading | 英 | PhD by Distance | PT 4-6年 | △ 条件付き | ? 未確認 | △ |
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
| **TU Delft**(External) | 一時金 €11,000 + bench fee €10,000/年(**記載が併存しており要確認**) | 4年で約€51,000か |
| **Swansea** (CS) | PT £11,800/年 | 6年 約£70,800 |
| **York** (CS) | FT £32,030/年(2027/28)。PT額は未掲載、半額なら約£16,000/年 | 6年 約£96,000 |
| **UTS** | course fee A$198,543(CS)/ A$215,274(Eng)。年額か総額か要確認。PTは年額×0.5 | 要確認 |

→ **蘭の External PhD ルートが桁違いに安い可能性がある**。ただしリモート可否が全く不明で、ここが最大の未知数。

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
- 次: 個別ファイル `labs/york.md` を作り、Centre for Assuring Autonomy と Real-Time and Distributed Systems の教員を洗い出す

### UOW - University of Wollongong(豪州) — 制度面が最もクリーン

- **在職可否が肯定形で明記されている唯一の例**(上記引用)
- 対象は「**コースワークを含まない研究学位のみ**」(PhD または MPhil)。指導はバーチャル。居住地は豪州内外を問わない
- **「Suitable only for research projects that do not require physical access to facilities based at UOW campuses」** → 自分のシミュレーション中心方針と要件が一致
- キャンパス出席は不要。在学中のオンキャンパス学生からの転換も申請可
- **未確認**: 学費、年限、そして**自律移動・制御系の受け皿があるか**(今回の検索では確認できず)
- 出典: [Higher Degrees by Research (UOW)](https://www.uow.edu.au/research/graduate-research/future-students/higher-degrees-by-research/)

### TU Delft(オランダ) — 高リスク・高リターン

- **External PhD(buitenpromovendus)**: 大学に雇用されず、自己資金で学位を目指す正規ルート。TU Delft とは雇用契約を結ばず、報酬もない
- 費用: 「外部PhDの授業料 **€11,000(一時金)**、監督費用等を含む」という記載と、「外部PhD候補者には**監督のための bench fee €10,000/年**」という記載が併存。学部ごとに異なる可能性があり**要確認**
- 4年プログラムの1年目末に go/no go 判定あり
- 入学要件: 関連分野の修士号、英語での口頭・記述能力
- **最大の未知数: 居住要件とリモート可否**。「大学は外部PhD候補者に関する方針を自由に定められる」とされ、TU Delft の方針は今回確認できなかった
- **分野の受け皿は極めて強い**(自律移動・制御)。リモートさえ通れば最有力になり得る
- 出典: [PhD Fees and funding (TU Delft)](https://www.tudelft.nl/en/education/programmes/phd/phd-admission/fees-and-funding) / [External PhD candidates (PNN)](https://hetpnn.nl/en/kennisbank/buitenpromovendi/)

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

## 次のアクション(優先度順)

1. **York を個別調査**(`labs/york.md`): 制度・学費(PT額)・教員。現時点で「制度◎ × テーマ◎」を同時に満たす唯一の候補
2. **TU Delft の居住要件・リモート可否**を確認。通れば費用面で圧倒的に有利
3. **UOW の分野の受け皿**を確認。制度は最もクリーンなので、受け皿さえあれば有力
4. Twente / Eindhoven の External PhD を調査
5. UTS・UOW・TU Delft への照会文面を作成(`contacts/`)
