# Delft University of Technology (TU Delft) (オランダ)

調査日: 2026-09-22

## 結論(先に)

**「在職のまま、現在の居住地に留まってパートタイムで進める」ことは制度として公式に認められている。** ただし**その居住地が日本(EU域外)まで含むかは明記がなく**、さらに**学部ごとに方針が大きく異なり、一部学部は自己資金PhDの受け入れを停止している**。制御・ロボティクス系を担当する 3mE / EEMCS の方針は今回確認できなかった。

また、当初「費用が桁違いに安いのでは」と見立てていたが、**これは誤りだった**。実際は授業料に加えて年額の bench fee がかかり、6年で見ると Swansea とほぼ同水準になる。

## 制度サマリ

| 項目 | 内容 |
|---|---|
| リモート制度 | **External PhD(buitenpromovendus)**。大学に雇用されず自己資金で学位を目指す正規ルート |
| **在職可否** | **◎ 公式に明記**。「An alternative to full-time PhD study is to **keep your current job and/or stay where you live and work on your project part-time as an external PhD candidate**」 |
| **居住地の扱い** | 「stay where you live」とあるが、**EU域外・日本からの遠隔を想定しているかは不明**。一方 IDE 学部は「**オランダでの生活費(月額最低€1,390)**をカバーするスカラシップ」を要求しており、**居住を前提とする学部が現に存在する** |
| **修業年限** | 博士課程は名目4年。パートタイムの年限は未確認 |
| **資金要件** | **自己資金の確保が必須**。TU Delft は雇用契約を結ばず、報酬も出さない。パートタイム外部PhDについて公式に想定されている資金源は「**雇用主からのスポンサーシップ**」 |
| 費用 | **授業料 €11,000(プログラムにつき1回)** — 支援・訓練・キャンパス施設利用の対価。加えて **bench fee €10,000/年** — 作業スペースと実験室利用の費用で、**想定される施設利用量と研究内容に応じて決定**。所属機関に請求され、機関の資金がなければ本人負担。**学部は授業料・bench fee のいずれも免除する裁量を持つ** |
| 出願要件 | オランダ法および TU Delft 博士規程により**修士号が必須**。英語での口頭・記述能力 |
| **学部ごとの差** | **Architecture and the Built Environment は2025年1月1日から、生活費・授業料・bench fee をカバーしないスカラシップの候補者、および自己資金の候補者の受け入れを停止**。IDE は生活費+授業料+bench fee €20,000 のカバーを要求。**方針は学部ごとに大きく異なる** |
| 手続き | 開始時(できれば初出勤日より前)に、費用の算定方法等を合意して記録する。4年課程では1年目末に go/no go 判定がある |
| 出典 | [PhD at TU Delft](https://www.tudelft.nl/en/education/programmes/phd) / [Fees and funding](https://www.tudelft.nl/en/education/programmes/phd/phd-admission/fees-and-funding) / [PhD Admission](https://www.tudelft.nl/en/education/programmes/phd/phd-admission) / [A+BE Finding a position](https://www.tudelft.nl/en/architecture-and-the-built-environment/research/graduate-school-a-be/finding-a-position) |

### 費用の試算と訂正

`labs/_candidates.md` の初版で「TU Delft の External PhD は桁違いに安い可能性」と書いたが、**bench fee が年額であることを見落としていた**。訂正した試算は以下。

| 期間 | 授業料 | bench fee | 合計 |
|---|---|---|---|
| 4年 | €11,000 | €10,000 × 4 = €40,000 | **€51,000** |
| 6年(パートタイム想定) | €11,000 | €10,000 × 6 = €60,000 | **€71,000** |

→ 6年なら **Swansea CS(約£70,800)とほぼ同水準**。「圧倒的に安い」わけではない。

ただし **bench fee は「作業スペースと実験室利用」の対価で、想定利用量に応じて決まる**と明記されており、かつ**学部に免除の裁量がある**。完全リモートで施設を一切使わない場合に減免され得るかは、照会する価値がある(推測。公式の言及はない)。

### 在職可否の判定: ◎(ただし条件付き)

「keep your current job and/or stay where you live and work on your project part-time」という文面は、**これまで調べたどの大学よりも直接的に今回の条件を記述している**。York・Swansea の「パートタイム×distance」が制度の組み合わせとして成立するのに対し、TU Delft は**在職・現居住地維持そのものを一つの選択肢として提示している**。

一方で、リスクは以下の3点。

1. **「stay where you live」の地理的範囲が不明。** 欧州域内の在職者を想定した文面である可能性がある
2. **資金モデルが「雇用主のスポンサーシップ」前提。** 現職の勤務先が学費を負担する構図が想定されており、自己資金で通るかは学部次第
3. **自己資金PhDの受け入れを停止した学部が現に存在する**(A+BE)。この流れが 3mE / EEMCS に及んでいないかの確認が必須

### 未検証: 学位授与(promotie)の対面要件

オランダの博士号授与式は対面で行われるのが通例とされるが、**今回の調査では TU Delft 博士規程から裏付けを取れなかった**(規程PDFの該当箇所を特定できず)。1日だけの渡航であれば在職の障害にはならない見込みだが、事実として未確認。

## 研究室 / 教授

### Cognitive Robotics (CoR) 学部 — 3mE 所属

機械知覚、人工知能、**モーションプランニング**、ダイナミクス、人間ロボット相互作用、システム統合を扱い、応用先はロボティクス、スマート産業、**インテリジェントビークル**。

- **Learning and Autonomous Control (LAC)**: 高次の認知的アプローチ(適応・学習)から低次のモーション制御までのロボット制御手法。**マルチロボット制御(リアルタイム協調、動的な車両ルーティングとタスク割当、マルチロボット学習、マルチロボットシステムのセキュリティとプライバシー)を含む**
- **Autonomous Multi-robots Lab**: **モーションプランニング、マルチロボットシステム、ロボット自律性、インテリジェント交通、協調と計画のための学習**

→ **興味領域(経路計画・制御・マルチロボット協調)に対して、これまで調べた中で最も直接的な受け皿。** UTS Robotics Institute と並ぶか、それ以上。

[出典: CoR People](https://www.tudelft.nl/en/me/about/departments/cognitive-robotics-cor/people) / [Learning and Autonomous Control](https://www.tudelft.nl/en/me/about/departments/cognitive-robotics-cor/research/learning-and-autonomous-control)

---

### Assoc Prof Javier Alonso-Mora — Cognitive Robotics / Autonomous Multi-robots Lab

- 専門: 自律移動ロボットの**ナビゲーション、モーションプランニング、制御**。特に**マルチロボットシステム**、オンデマンド交通、動的・不確実な環境で他のロボットや人と相互作用するロボット
- テーマ適合度: **◎** — 「経路計画」「制御」「複数台ロボット・モビリティの協調制御」という興味領域3つすべてに重なる。現時点の全候補中で最も適合度が高い
- 実機依存度: **中(要精査)** — オンデマンド交通・マルチロボット協調はシミュレーション主体で研究可能だが、CoR は実機ラボを持つ
- リモート受け入れ姿勢: 未確認
- 代表論文: 未取得(次回 Scholar / TU Delft Pure で近年5年分を確認)
- 連絡先: 未取得(CoR People ページから取得する)
- 所見 / 次に調べること: **テーマ適合度では York の Calinescu を上回る可能性がある。** ただし制度リスク(3mE が外部PhDをどう扱うか、EU域外リモートが通るか)が未解消なので、制度確認が先

## この大学に対する現時点の結論

- **テーマ適合度は全候補中トップクラス。** Autonomous Multi-robots Lab / LAC は興味領域そのもので、Javier Alonso-Mora は経路計画・制御・マルチロボット協調の3つすべてに重なる。
- **在職可否の記述も最も直接的**(「keep your current job and/or stay where you live」)。
- **一方で不確実性が最も大きい。** 地理的範囲の不明確さ、学部ごとの方針差、自己資金受け入れ停止の流れ、雇用主スポンサー前提の資金モデル。York のように出願ページの履修モード欄で確定できる類の情報ではなく、**照会しないと判断できない**。
- 費用は当初の見立てを訂正し、6年で約€71,000。Swansea とほぼ同水準で、特別な優位性はない。
- **位置づけ: 「テーマ最優先なら本命、確実性を取るなら York」。** 照会の優先度は高い。
- 未確認事項(優先度順):
  1. **3mE / Cognitive Robotics が外部PhD候補者を受け入れているか**、および自己資金の可否
  2. **「stay where you live」に日本(EU域外)が含まれるか**、遠隔での指導実績があるか
  3. bench fee が、施設を使わない完全リモート候補者に対して減免され得るか
  4. パートタイム外部PhDの修業年限
  5. Javier Alonso-Mora の近年論文の実機比率、受け入れ余力
  6. promotie(学位授与式)の対面要件
