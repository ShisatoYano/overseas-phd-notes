# University of York (英国)

調査日: 2026-09-22

## 制度サマリ

| 項目 | 内容 |
|---|---|
| リモート制度 | **PhD by distance learning**(公式)。「同等の指導(主にオンライン)と同等の学術的厳格さ」を掲げ、研究・論文執筆は遠隔で行い「**joining us on campus only occasionally**」 |
| **在職可否** | **◎ 可**。出願ページに履修モードとして「**Part-time: Distance Learning (72 months)**」が明示されている。リモートとパートタイムの組み合わせが公式に提供されている |
| **修業年限** | フルタイム3年 / **パートタイム6年(72か月)**。居住地は英国内・国外いずれでも可 |
| **在職要件** | 明示的な要件記載なし。ただし「**You cannot study a part-time course at the University of York if you require a Student Visa.**」とあり、**パートタイム不可の根拠はビザ要件**。日本からのリモートでビザ不要なら適用されない |
| 対象学部・学科 | Computer Science(コース番号 DRPCOMSSDL3)ほか。今回はCSのみ確認 |
| 出願要件 | CS または関連分野の **honours 2:1 以上**。「非標準の経歴でも、十分なCSの知識と経験を示せれば考慮する」と明記。提出物は成績証明書・**研究提案書(または関心領域の概要)**・CV。語学証明・パーソナルステートメントは任意提出 |
| 学費 | 研究学位の国際生レート(**2027/28**)は STEM・ラボ系バンドで **£32,030/年**(人文社会系は£26,240/年)。CSはSTEMバンド。**パートタイムのレートは非掲載 → 要確認**(半額なら約£16,000/年、6年で約£96,000) |
| 開始時期 | **2月 / 9月**(2027年2月・9月、2028年2月・9月の受付を確認) |
| 事前手続き | **出願前に指導教員候補を特定すること**が前提。選考通過者は面接があり、国際出願者はZoom |
| 出典 | [PhD Computer Science](https://www.york.ac.uk/computer-science/study/postgraduate-research/phd-computer-science/) / [出願ページ DRPCOMSSDL3](https://www.york.ac.uk/study/postgraduate/courses/apply?course=DRPCOMSSDL3) / [国際学費(PGR)](https://www.york.ac.uk/study/postgraduate-research/fees/international/) / [研究グループ](https://www.york.ac.uk/computer-science/research/groups/) |

### 制度面の所見

- **必須2条件(リモート可 × 在職可)を、出願ページの履修モード欄という最も確実な形で満たしている。** Swansea と並び、UTS(推定止まり)より確実性が高い。
- 「非標準の経歴も考慮する」という明記は、**`AutonomousVehicleControlBeginnersGuide` を実績として提示できる自分にとって有利**に働く可能性がある。
- **最大の懸念は学費。** フルタイム £32,030/年 は Swansea(£23,650)より大幅に高い。パートタイムが半額だとしても6年総額で約£96,000となり、Swansea の約£70,800を上回る。パートタイムレートの確認が必須。
- 出願書類に研究提案書が含まれるため、**Swansea 同様テーマの具体化が前提条件**になる。

## 研究室 / 教授

### 関連する組織・グループ

- **Centre for Assuring Autonomy (CfAA)**: Lloyd's Register Foundation と York のパートナーシップ。AIと安全性の交差領域を扱う。安全なAI・AI駆動の自律システムの保証フレームワークを、**セクター非依存**の立場で研究。所長は Prof John McDermid(出資規模は出典により £10m / £12m と記載が割れており要確認)
- **Institute for Safe Autonomy (ISA)**: £45m の施設。地上・水中・空中の自律システムを対象とする「living lab」で、研究者100名超。**実験施設主体なのでリモート適性は低い**が、CS側の検証・保証研究は理論主体
- **Real-Time and Distributed Systems (RTDS)**: スケジューリング、タイミング解析、モデリング、**シミュレーション**、性能最適化。応用先に**自動車・航空宇宙・通信・製造・ロボティクス**。グループリードは Dr Pengcheng Liu
- **High Integrity Systems Engineering (HISE)**、**Artificial Intelligence**、**Automated Software Engineering** も関連

CfAA は自動運転を明示的に扱っており、「安全な自動運転車の導入」に関する技術研究とデモンストレータ(センサ・共有制御)を実施。**Swansea には存在しなかった「自動運転そのものの受け皿」がある**のが決定的な違い。

[出典: CfAA](https://www.york.ac.uk/assuring-autonomy/) / [CfAA Automotive](https://www.york.ac.uk/assuring-autonomy/automotive/) / [ISA](https://www.york.ac.uk/safe-autonomy/) / [RTDS](https://www.york.ac.uk/computer-science/research/groups/real-time-distributed-systems/)

---

### Prof Radu Calinescu — Computer Science / Trustworthy Adaptive and Autonomous Systems and Processes チームリード

- 専門: 形式手法と**確率的モデル検査**を用いた自律システム・自己適応システムの高信頼化。形式モデリング、解析、検証、**コントローラ合成(controller synthesis)**。応用先はロボティクス、サイバーフィジカル、組込み、サービスベースシステム
- 役職: Assuring Autonomy International Programme の **Safety of AI テーマリード**、UKRI Trustworthy Autonomous Systems Node in Resilience の PI
- テーマ適合度: **◎** — `research-theme/candidates.md` の「安全性の形式検証」候補に直撃。かつ**コントローラ合成は「制御」そのもの**であり、興味領域の中心とも接続する。深層学習の知覚コンポーネントを持つ自律システムのコントローラ合成という主題は、自動運転と直結する
- 実機依存度: **低** — 形式手法・モデル検査・合成アルゴリズムが主体で、完全にソフトウェアで完結する。**Swansea EEE の Distance 要件(実験室作業を含まないこと)も余裕で満たす性質**
- リモート受け入れ姿勢: 未確認
- 代表論文:
  - Discrete-Event Controller Synthesis for Autonomous Systems with Deep-Learning Perception Components (2022)
  - Quantitative Assurance and Synthesis of Controllers from Activity Diagrams (2024)
  - Verification and External Parameter Inference for Stochastic World Models (2025)
  - Permissive Controller Synthesis for Probabilistic Systems
  - AMLAS(機械学習の安全性保証プロセス)の策定に関与
  - 製造現場の移動協働ロボット向け安全コントローラを確率的モデル検査で合成した研究
- 連絡先: https://www-users.cs.york.ac.uk/~raduc/
- 所見 / 次に調べること: **York の第一候補。** 「制御」と「形式検証」を同時に満たす稀なポジションで、かつ研究が純ソフトウェア。リモート・パートタイム学生の指導実績と、現在の受け入れ余力を確認する

### Dr Pengcheng Liu — Computer Science / RTDS グループリード(Associate Professor)

- 専門: ロボティクス・機械学習・生物学の交差領域。生物の適応性・頑健性をロボットアーキテクチャへ移す方向
  - **動的・不確実環境における「ロボットのモーション/経路計画/学習と最適化」**(生物模倣モデル・機械学習を活用)
  - 生物模倣/ソフトロボットのモデリング・設計・制御(自己推進型の振動駆動カプセルロボット、剛体/柔軟アーム・グリッパ)
  - CPS、IoT、デジタルツイン、Human-in-the-Loop の共有制御・自動化
- テーマ適合度: **◎** — 「経路計画」に直撃。論文数70本超
- 実機依存度: **中** — 経路計画・最適化の部分はシミュレーションで完結するが、ソフトロボット・カプセルロボット・グリッパは実機主体。**研究テーマの選び方次第で振れ幅が大きい**
- リモート受け入れ姿勢: 未確認
- 連絡先: https://www.cs.york.ac.uk/people/liup / https://sites.google.com/view/pliu/
- 所見 / 次に調べること: 近年の論文で、経路計画・最適化側とソフトロボット側の比率を確認する。前者に寄った提案なら有力

### Prof John McDermid — CfAA 所長

- 専門: 自律システムの安全性保証。CfAA を統括
- テーマ適合度: ○(組織のトップであり、実務上は配下の教員が指導者になる可能性が高い)
- 所見: 直接の指導教員候補というより、**組織としての受け入れ可否を測る指標**として見る

### Prof Iain Bate — RTDS

- 専門: リアルタイムシステム、スケジューリング、タイミング解析(グループの主題より推定)
- テーマ適合度: △ — 自動運転の実時間性という切り口はあるが、興味領域の中心ではない
- 連絡先: iain.bate@york.ac.uk

### その他 RTDS メンバー(未精査)

Dr Steven Dai (xiaotian.dai@york.ac.uk)、Dr Ian Gray、Dr Steven Wright、Dr Poonam Yadav、Dr Chris Crispin-Bailey、Prof Alan Burns(名誉教授)

## この大学に対する現時点の結論

- **現時点の全候補中で総合1位。** 「リモート可 × 在職可」を出願ページの履修モード欄という最も確実な形で満たし、かつ**自動運転・自律システムの受け皿が組織として存在する**(CfAA)。Swansea の弱点(受け皿なし)と UTS の弱点(在職可否が推定止まり)を両方クリアしている。
- **最有力の指導教員候補は Prof Radu Calinescu。** 形式手法によるコントローラ合成という主題が「制御」と「安全性の形式検証」の両方に接続し、研究が純ソフトウェアでリモート適性が極めて高い。次点は Dr Pengcheng Liu(経路計画に直撃だが、実機寄りテーマとの切り分けが必要)。
- **最大の弱点は学費。** 国際生 STEM バンドで £32,030/年(2027/28)は Swansea の £23,650 を大きく上回る。パートタイムレートが半額でも6年総額で Swansea を上回る見込み。
- 未確認事項(優先度順):
  1. **パートタイム(distance)の学費レート**。総額を左右する最重要項目
  2. Calinescu / Liu のリモート学生・パートタイム学生の指導実績、現在の受け入れ余力
  3. CS の distance PhD が、CfAA / RTDS など特定グループでも利用できるか(グループ単位の制限の有無)
  4. IELTS の要求スコア(CSページに記載なし)
  5. ATAS クリアランスの要否(英国の工学・CS系では一般に必要)
  6. CfAA の出資規模(£10m / £12m と出典で記載が割れている)
