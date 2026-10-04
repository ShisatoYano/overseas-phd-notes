# 事務照会(制度確認)下書き

作成日: 2026-09-22

## 方針

- **目的は「不明点の確認」**。出願の意思表示は、質問の意図を伝えるための文脈づけにとどめ、約束はしない
- **指導教員への打診はここに含めない。** 教授への初回接触は研究提案の中身で判断されるため、`research-theme/` の具体化が終わるまで送らない
- 事務窓口への質問は定型業務であり、後から改めて出願しても不利にならない。一方、教授への接触は一度きりである点が決定的に違う
- 各校の未確認事項は `labs/<大学名>.md` の末尾に列挙してあり、本ファイルの質問項目はそこから抽出したもの
- **ビザ論法は自分から先に提示して確認を取る形にする。** そうしないと担当者が反射的に「国際学生はフルタイムのみです」と定型回答してくる事故が起きやすい

### 公開範囲について

本リポジトリは public。以下は書かない。

- 自分のメールアドレス、勤務先名
- 先方担当者の氏名・返信本文の逐語引用(返信は**要旨のみ**を記録する)

## ステータス

| 大学 | 宛先 | 送信日 | 返信日 | 状態 |
|---|---|---|---|---|
| York | cs-pgr-admissions@york.ac.uk | 2026-09-23 | 2026-10-04 | **返信受領(質問1〜5すべてに回答あり)** |
| York(署名追補) | 同上(同一スレッド) | 2026-09-23 | | **送信済**(下記1-b) |
| York(お礼・追加質問) | 同上(同一スレッド) | 2026-10-04 | | **返信待ち**(下記1-c。PT の来校回数、出願前に指導教員の内諾が要るか) |
| UTS | grs@uts.edu.au | 2026-09-23 | (自動応答のみ) | **返信待ち** |
| TU Delft | graduateschool-ME@tudelft.nl | 2026-10-04 | | **返信待ち**(下記2。9/23 に送信済みと誤記録していたため、10/4 に改訂した文面で初回送信) |
| UOW | graduate-research-school@uow.edu.au | 2026-09-23 | 2026-09-26 | **返信受領(定型文。質問1〜4いずれも未回答)** |
| UOW(HPS) | ~~hoang_dung_duong@uow.edu.au~~ | 2026-09-23 | — | **不達(宛先不明)** |
| UOW(EIS) | ddgr-eis@uow.edu.au | 2026-09-26 | | **返信待ち**(下記6) |
| Swansea | a.m.pauly@swansea.ac.uk | 2026-09-23 | 2026-09-26 | **返信受領(質問1〜4すべてに回答あり)** |
| Swansea(お礼・追加質問) | 同上(同一スレッド) | 2026-09-26 | 2026-10-04 | **返信受領**(独立した個人研究なら大学と勤務先の合意書は不要) |

署名は以下を使う(2026-10-04 改訂)。

```
Shisato Yano
Software engineer (autonomous driving / vehicle control), based in Japan
GitHub: https://github.com/ShisatoYano
LinkedIn: https://www.linkedin.com/in/shisatoyano
```

- この改訂より前に送ったメール(York 1-b・1-c、TU Delft 2 など)は、旧署名(GitHub は `AutonomousVehicleControlBeginnersGuide` のリポジトリへのリンク、LinkedIn なし)で送っている。送った文面の記録は、送ったときのまま残す
- 経歴の裏付けを添える理由は変わらない(York が「非標準の経歴でも十分なCSの知識と経験を示せれば考慮する」と明記しているため)。改訂後は GitHub のプロフィールから OSS をたどれ、LinkedIn で職歴も確認できる

## 送信前チェックリスト

1. **宛先アドレスが現在も有効か**、公式ページで確認する
2. **宛名(Dear ...)が現在の正式名称と一致するか**(例: TU Delft は「Graduate School 3mE」と「Graduate School ME」の表記が混在している)
3. **コースコード・学費・年限など、本文で引用した数値が最新か**(年度で変わる)
4. **署名を入れたか** — 氏名 + 職種 + 所在国 + GitHub + LinkedIn(上記の改訂後の署名)
5. 送信後、本ファイルのステータス表に送信日を記入する

> 2026-09-23: York 宛の送信で署名を付け忘れた。差出人欄で本人は特定できるため追いメールはせず、**先方からの返信への返答時に署名を付けて OSS を提示する**方針とした。

---

## 1. York — 最優先

**宛先**: cs-pgr-admissions@york.ac.uk(CS学科のPGR出願窓口。大学全体の窓口は pg-admissions@york.ac.uk)
**狙い**: パートタイム学費レート。総額を左右する最重要項目

```
Subject: Part-time distance PhD in Computer Science — fee rate and entry requirements

Dear Postgraduate Research Admissions,

I am a software engineer based in Japan, working in autonomous driving
and vehicle control. I am planning to apply for the PhD in Computer
Science by distance learning (DRPCOMSSDL3) on a part-time basis, while
continuing in full-time employment in Japan.

Before I approach a potential supervisor, I would be grateful for
clarification on the following:

1. The published international rate for research degrees is £32,030
   per year (2027/28, STEM band) for full-time study. What is the
   corresponding part-time rate for the 72-month distance-learning
   mode?

2. Does ATAS clearance apply to a distance-learning candidate who will
   not travel to or reside in the UK?

3. What English language qualification is required for this programme?

4. I note that part-time study is not available to applicants who
   require a Student Visa. As I would be studying entirely from Japan
   and would not require a visa, I understand this restriction would
   not apply to me. Could you confirm that this understanding is
   correct?

5. Are there any restrictions on which research groups can supervise a
   distance-learning candidate? My interests align with the Centre for
   Assuring Autonomy and the Real-Time and Distributed Systems group.

Thank you for your time.

Kind regards,
```

### 1-b. York — 署名の追補(2026-09-23)

初回送信で署名が漏れたため、同一スレッドへの返信として送る。**詫びを前面に出さず、経歴情報の補足として扱う**。事務窓口にとって、誰からの問い合わせかは差出人欄で既に分かっているため、謝罪よりも「判断材料の追加」として読めるほうが有用。

```
Subject: Re: Part-time distance PhD in Computer Science — fee rate and entry requirements

Dear Postgraduate Research Admissions,

A short addition to my message below — I omitted my signature, and
some of this background may be relevant to your assessment of points
2 and 3.

I am a software engineer in Japan working on autonomous driving and
vehicle control. Alongside my work I maintain an open-source textbook
and codebase on autonomous vehicle control algorithms, linked below,
which is the foundation I would build a research proposal on.

Kind regards,

Shisato Yano
Software engineer (autonomous driving / vehicle control), based in Japan
GitHub: https://github.com/ShisatoYano/AutonomousVehicleControlBeginnersGuide
```

### 1-c. York — お礼と追加質問(2026-10-04 送信)

回答(下記「受領記録」)を受けて、総額と出願の段取りに直結する2点だけを聞き直す。ATAS は、日本国籍が免除対象であることを**質問ではなく情報として**添える(先方の回答は国籍を考慮しない一般論とみられ、後で手続きの行き違いが起きないようにするため)。ビザは国際課の管轄と案内されたが、日本国籍は短期訪問なら査証不要(ETA のみ)なので、ここでは聞かない。

```
Subject: Re: Part-time distance PhD in Computer Science — fee rate and entry requirements

Dear <担当者の名前>,

Thank you very much for your detailed reply — it answers my questions
clearly and is very helpful for my planning.

May I ask two short follow-up questions?

1. You mentioned that the number of milestone visits is reduced for
   part-time students. In practice, how many one-week visits per year
   would a part-time distance-learning student normally be expected to
   make? As I will be balancing these visits with full-time employment
   in Japan, knowing this in advance would help me plan my leave.

2. Should I secure the agreement of a potential supervisor before
   submitting my application, or is it acceptable to apply with a
   research proposal and a statement of my interests (the Centre for
   Assuring Autonomy and the Real-Time and Distributed Systems group),
   and have my profile passed on to the relevant groups as you
   described?

Regarding ATAS, I note from the UK government guidance that Japanese
nationals are currently exempt from the ATAS requirement. I mention
this only for your records; I will of course follow the University's
guidance if this changes.

Thank you again for your help.

Kind regards,

Shisato Yano
Software engineer (autonomous driving / vehicle control), based in Japan
GitHub: https://github.com/ShisatoYano/AutonomousVehicleControlBeginnersGuide
```

---

## 2. TU Delft — テーマ適合度トップだが不確実性最大

**宛先**: graduateschool-ME@tudelft.nl(Graduate School of the Faculty of Mechanical Engineering。[Contact ページ](https://www.tudelft.nl/en/me/research/graduate-school-me/contact)で 2026-10-04 に確認。窓口は Project manager/policy advisor)
**状態**: **送信済(2026-10-04)**。9/23 に送信済みと誤記録していたが、実際はこの日が初回送信
**狙い**: ME 学部が自費の外部 PhD を受け入れるか、日本に住んだままで成り立つか

### 2026-10-04 の改訂で変えた点

- **「keep your current job and/or stay where you live」を大学全体の記述として引用するのをやめた。** 再確認すると、この一文は **A+BE 学部(建築)の [Finding a position](https://www.tudelft.nl/en/architecture-and-the-built-environment/research/graduate-school-a-be/finding-a-position) のページ**にあるもので、同じページで A+BE は 2025-01-01 から自費の候補者の受け入れを止めている。大学全体の PhD ページ・Admission ページにはこの一文は見当たらない。ME 学部の担当者にこれを「TU Delft の方針」として示すと、誤りを指摘されて話がそこで止まるおそれがある
- **bench fee の額(€10,000/年)を書かない。** 大学の [Fees and funding](https://www.tudelft.nl/en/education/programmes/phd/phd-admission/fees-and-funding) は現在「候補者と研究内容で変わる。年ごとに課し、在籍中は固定」とだけ書いている。授業料 €11,000 と「学部の裁量で両方とも免除できる」は変わらず
- **ビザ論法を先に書く**(第1陣の照会の方針どおり)。日本に住み、渡航は短期の訪問だけになることを先に示す
- 受け皿に、10/2 の調査で加えた **Maritime and Transport Technology(Negenborn、自律船・マルチロボット)** を加える
- 質問を5つから4つにまとめた(来校の要否は居住の質問に含めた)

```
Subject: Self-funded external PhD based in Japan — enquiry (Cognitive Robotics / Maritime and Transport Technology)

Dear Graduate School ME,

I am a software engineer based in Japan, working in autonomous driving
and vehicle control. I am considering a part-time external PhD in the
Faculty of Mechanical Engineering, self-funded, while continuing in
full-time employment in Japan. My research interests are motion
planning, control and multi-robot coordination, pursued through
simulation, which align with the Cognitive Robotics department
(Autonomous Multi-robots Lab, Learning and Autonomous Control) and the
Department of Maritime and Transport Technology.

I would live in Japan throughout and would not need a Dutch residence
permit; I would travel to Delft only for short visits where the
programme requires it. Before approaching a potential promotor, I
would like to establish whether this route is open in practice:

1. Does the Faculty of Mechanical Engineering currently accept
   self-funded external PhD candidates? I understand that the Faculty
   of Architecture and the Built Environment stopped accepting
   self-funded candidates from 1 January 2025, and I would like to
   know whether a similar policy applies in your faculty.

2. Can an external candidate reside in Japan for the whole programme,
   with supervision mainly online? If so, at which stages is physical
   presence in Delft required (for example, the go/no-go assessment
   or the doctoral defence)? Are there precedents of external
   candidates based outside Europe?

3. How is the bench fee determined for an external candidate whose
   research is entirely computational and who would not use campus
   workspace or laboratories? Is a reduction or waiver possible in
   such a case?

4. What is the maximum duration of a part-time external PhD, and how
   is the go/no-go assessment timed for part-time candidates?

Thank you for your time.

Kind regards,

Shisato Yano
Software engineer (autonomous driving / vehicle control), based in Japan
GitHub: https://github.com/ShisatoYano/AutonomousVehicleControlBeginnersGuide
```

---

## 3. UTS — 在職可否が推定止まり

**宛先**: grs@uts.edu.au(Graduate Research School)
**狙い**: PhD by distance をパートタイムで履修できるか。ここが不可なら UTS は脱落

```
Subject: PhD by distance — part-time enrolment and FEIT availability

Dear Graduate Research School,

I am a software engineer based in Japan, working in autonomous driving
and vehicle control. I am interested in the PhD by distance, with
research interests in motion planning, control, and multi-robot
coordination that align with the UTS Robotics Institute.

I would be grateful for clarification on the following:

1. Can the PhD by distance be undertaken part-time? I understand the
   maximum course duration is four years full-time or eight years
   part-time, and that international HDR fees are calculated pro-rata
   at 0.5 of the annual rate for part-time candidature. I also note
   that the requirement to enrol full-time and on campus arises from
   Australian student visa conditions, which would not apply to me as
   I would study entirely from Japan without a visa. Could you confirm
   whether part-time distance candidature is permitted on that basis?

2. Is the PhD by distance available through the Faculty of Engineering
   and IT, and specifically the Robotics Institute? The examples on
   the PhD by distance pages are drawn from other faculties, so I
   would like to confirm that FEIT participates and whether there are
   precedents.

3. The course pages list a course fee of A$198,543.42 (Computer
   Science) and A$215,274.49 (Engineering). Is this figure the total
   for the degree or an annual rate?

4. The PhD by distance pages state that candidates should "have access
   to your research environment locally". For a robotics-related but
   entirely computational project, what would satisfy this
   requirement?

5. Admission requires a master's by research or bachelor honours
   (first class / second class division 1). Japanese master's degrees
   normally require a research thesis. Would such a degree be assessed
   as equivalent to a master's by research?

Thank you for your time.

Kind regards,
```

---

## 4. UOW — 制度は最もクリーン、受け皿を探す必要がある

**宛先**: graduate-research-school@uow.edu.au
**狙い**: Decision Systems Lab のメンバー特定と、distance HDR の基本条件

```
Subject: HDR by distance learning — supervision in autonomous systems

Dear Graduate Research School,

I am a software engineer based in Japan, working in autonomous driving
and vehicle control. I am interested in undertaking a PhD by distance
learning on a part-time basis, and I note that UOW states
international candidates based overseas do not require an Australian
study visa and are therefore eligible to study part-time.

My research interests are in motion planning, control, and multi-agent
coordination, pursued entirely through simulation — which fits the
requirement that distance projects must not need physical access to
UOW campus facilities.

I would be grateful for help with the following:

1. The Decision Systems Lab appears to be the closest match to my
   interests, given its work on autonomous AI multi-agent systems and
   autonomous unmanned vehicles. The lab page does not list individual
   academics. Could you direct me to the academics in that group who
   supervise HDR candidates, or advise who I should contact?

2. What is the maximum duration for a part-time HDR candidature?

3. What is the annual international tuition fee for a part-time PhD
   candidature in the Faculty of Engineering and Information Sciences?

4. Are there precedents of distance HDR candidates supervised in
   engineering or computing disciplines?

Thank you for your time.

Kind regards,
```

---

## 5. Swansea — 宛先が事務ではなく Admissions Tutor

**宛先**: a.m.pauly@swansea.ac.uk(Dr Arno Pauly, CS Admissions Tutor)
**注意**: 事務窓口ではなく教員。ただし公式手続き上の窓口なので、**制度・手続きの質問のみであれば問題ない**。この段階では研究提案書を添えない
**狙い**: Distance × パートタイムの運用条件

```
Subject: PhD Computer Science (Distance Learning, part-time) — enquiry before proposal

Dear Dr Pauly,

I am a software engineer based in Japan, working in autonomous driving
and vehicle control. I am considering applying for the PhD in Computer
Science by distance learning on a part-time basis (6 years), while
continuing in full-time employment in Japan.

I understand the formal process is to submit a Research Proposal Form
and discuss it with you before applying. Before I prepare that, I
would like to check a few points about how the arrangement works in
practice:

1. Is the distance-learning mode available with all four start dates
   (October, January, April, July) when studying part-time, or are
   start dates restricted for that combination?

2. Swansea's postgraduate research pages state that candidates may
   pursue the programme part-time "by pursuing research at an external
   place of employment". Does this apply to the Computer Science
   distance-learning route, and would any agreement or consent from my
   employer be required?

3. The Electronic and Electrical Engineering distance-learning pages
   set out requirements such as a minimum of one supervisory meeting
   per month and a research topic that can be pursued entirely without
   laboratory work. Do equivalent conditions apply in Computer
   Science?

4. Is ATAS clearance required for a distance-learning candidate who
   will not enter the UK?

Thank you for your time.

Kind regards,
```

---

## 受領記録

### UTS(2026-09-23、自動応答)

自動応答のため実質回答なし。ただし以下が判明した(詳細は `labs/uts.md`)。

- **学費の質問は GRS の管轄外**(「Ask UTS」へ誘導)。照会の質問3は別ルートで聞き直す必要がある見込み
- 出願には **faculty pre-assessment (EoI)** が必要な場合があり、これを欠くと審査されずに出願が閉じられる。FEIT に適用されるかは要確認
- GRS は「new HDR operating model」へ移行中で、返信が遅れる可能性
- メール以外に **Zoom drop-in(平日15-16時 AEST)/ コールバック依頼**が使える。返信が芳しくない場合の代替手段

### UOW(2026-09-23、自動応答)

自動応答のため実質回答なし。ただし以下が判明した。

- **組織名が「School of Graduate Research and Research Culture」に変わっている**(旧: Graduate Research School)。メールアドレスは同じ。今後の宛名はこちらを使う
- **「Head of Postgraduate Studies (HPS) に連絡を」と明示的に誘導している**。照会の質問1(Decision Systems Lab のメンバー特定)は学部側のほうが確実に答えられるため、HPS へ分けて出す価値がある
  - DSL は School of Computing and Information Technology 所属 → HPS は **Dr Steven Duong**(hoang_dung_duong@uow.edu.au)
  - 参考: Deputy Dean (Graduate Research), EIS は **Senior Professor Huijun Li**(ddgr-eis@uow.edu.au)
  - [出典: HDR faculty contacts](https://www.uow.edu.au/research/graduate-research/current-students/faculty-contacts/)
- 事務は「high volume of enquiries」で遅延中

### Swansea(2026-09-26、Admissions Tutor からの返信)

質問1〜4のすべてに具体的に答えてくれた。詳細は `labs/swansea.md`。

1. **開始時期**: Distance × パートタイムは10月・1月・4月開始。7月は設定されていないが、本人は設定漏れだろうとの見解。10月・1月・4月から選ぶのが無難
2. **勤務先との関係**: 勤務先が支援する研究プロジェクトは総じて歓迎。ただし**勤務先との正式な合意書を強く推奨**。取り決めておくべき点は、(a) 勤務時間を研究に使える範囲、(b) 勤務先の設備を論文作業に使えるか、(c) **最重要は成果公開に勤務先がかける制限**。本人を守るための措置であり、学科としても勤務先の方針変更で学位取得の道筋が途切れないことを確かめたい
3. **指導の条件**: EEE と同じ。大学規定で**指導教員との接触は最低月1回**(遠隔なら通常 Zoom、形式上はメールでも可)。ただし**実際には平均で週1回程度の面談が望ましい**。CS の研究は大半が専門設備を要しないので制約になりにくい。**物理的な設備が必要でも、勤務先が提供できるなら(上記の合意があれば)問題ない**
4. **ATAS**: 本人は法務の専門家ではないとしたうえで、学生ビザの対象にならない以上不要だろうとの見解。訪英する場合は通常の短期滞在の扱いで、日本国籍なら査証も不要。いずれにせよ ATAS は大した手続きではない

### York(2026-10-04、CS学科 PGR Admissions からの返信)

質問1〜5のすべてに回答があった。詳細は `labs/york.md`。

1. **学費**: PT(6年)は distance でも対面でも **£16,015/年**。FT の £32,030 とともに毎年改定される
2. **ATAS**: distance でも必要との回答。理由は自費での来校が必須なため。**入学時に2週間**、節目ごとに**年2回・各1週間**(PT は回数を減らす)、**最終試験(viva)は原則対面**。→ ただし日本国籍は ATAS の免除対象([GOV.UK](https://www.gov.uk/guidance/academic-technology-approval-scheme))。回答は一般論とみられる
3. **英語**: 大学全体の要件ページを案内されただけ。自分で確認した結果は IELTS 6.0(各5.5)/ TOEFL iBT 79
4. **PT とビザ**: **distance の PT は認める**。ビザそのものは学科では答えられず、国際課(international@york.ac.uk)の管轄
5. **グループの制限**: distance 特有の制限はない。条件は指導教員の空きとテーマの適合だけ。**出願後にプロフィールを関係する研究グループへ回す**

→ PT の来校回数と、出願前に指導教員の内諾が要るかを 1-c で追加質問する。

### Swansea(2026-10-04、Admissions Tutor からの追加質問への返信)

- **勤務先との合意書**: 勤務時間外に勤務先の資源を使わず個人で研究する状況なら、**大学と勤務先の合意書は要らない**との回答
- 研究提案書を楽しみにしている、と添えられていた。期限の指定はない
- → 返信はしない。お礼は研究提案書を送るときに兼ねる(内容のない往復で先方の手間を増やさないため)

### UOW(2026-09-26、担当者からの返信)

Candidature Management Officer からの返信。**中身は HDR の一般案内の定型文で、照会の質問1〜4にはどれも答えていない。**

- 案内先は How to apply ページ(指導教員の探し方と打診、研究テーマと研究計画書、費用の見積もり、オンライン出願)と HDR Scholarship ページだけ。それ以上の質問は Future Students に回すよう書かれていた
- distance・パートタイム・Decision Systems Lab のいずれにも触れておらず、**質問を読んだうえでの回答ではない**とみられる
- → GRS はテンプレートを返す窓口と判断。**質問1(DSL のメンバー)と4(distance の前例)は下記6の EIS 宛で聞く。** 質問2(年限)と3(学費)は公開資料で確認した(`labs/uow.md`)

---

## 6. UOW(EIS Deputy Dean)— 指導教員の特定のみ

### 経緯: HPS 宛が不達(2026-09-23)

当初 School of Computing and IT の Head of Postgraduate Studies である Dr Steven Duong 宛(hoang_dung_duong@uow.edu.au)に送信したが、**宛先不明で不達**。

- このアドレスは UOW の [HDR faculty contacts ページ](https://www.uow.edu.au/research/graduate-research/current-students/faculty-contacts/)に現在も記載されているもので、**転記ミスではなくページ側の情報が古い**とみられる
- SCIT の Our people ページでは Dr Steven Duong が Head of Postgraduate Studies として掲載されているが**メールアドレスの記載がない**。UOW Scholars のプロフィール(https://scholars.uow.edu.au/hoang-dung-duong)はブラウザ判定で内容を取得できなかった
- 同ページには Dr Nan Li が Higher Degree Research Leader として掲載されているが、こちらもアドレス非掲載

→ **役職ベースのアドレスに切り替える**。`ddgr-eis@uow.edu.au` は個人名ではなく役職のメールボックスで、担当者が代わっても生きている。EIS 全体を統括する立場なので Computing and IT の件も扱える。

**宛先**: ddgr-eis@uow.edu.au(Senior Professor Huijun Li, Deputy Dean (Graduate Research), Faculty of Engineering and Information Sciences)
**状態**: **送信済(2026-09-26)**。GRS の返信(2026-09-26)が定型文で質問1に答えていなかったため送った。宛先アドレスは送信前に faculty contacts ページで再確認済み
**位置づけ**: GRS の自動応答が HPS への連絡を明示的に誘導しているため、列を飛ばす行為にはあたらない。GRS が遅延中なので、**指導教員の特定だけ分けて出す**もの。年限・学費の事務的な質問は GRS 側に残す
**送信日**: 2026-09-26

```
Subject: Distance HDR supervision in autonomous systems — School of Computing and IT

Dear Deputy Dean,

I am a software engineer based in Japan, working in autonomous driving
and vehicle control. I have written to the School of Graduate Research
and Research Culture about undertaking a PhD by distance learning on a
part-time basis, and their reply suggested contacting the Head of
Postgraduate Studies for questions about supervision.

I first wrote to Dr Steven Duong at the address listed for the School
of Computing and Information Technology on the HDR faculty contacts
page, but the message could not be delivered. I am therefore writing
to you instead, and would be grateful if you could redirect this
enquiry to the appropriate person if that is more suitable.

My research interests are in motion planning, control, and multi-agent
coordination, pursued entirely through simulation. This fits UOW's
requirement that distance projects must not need physical access to
campus facilities.

The Decision Systems Lab appears to be the closest match, given its
work on autonomous AI multi-agent systems and autonomous unmanned
vehicles, and its algorithmic and simulation-based approach. The lab
page does not list individual academics, so I would be grateful if you
could advise:

1. Which academics in the Decision Systems Lab, or elsewhere in the
   School, supervise HDR candidates in these areas?

2. Are there precedents of distance HDR candidates being supervised in
   the School of Computing and Information Technology?

You may also wish to know that the email address currently published
for the School of Computing and Information Technology on the HDR
faculty contacts page appears to be out of date.

I am not yet approaching potential supervisors — I would like to
establish first whether suitable supervision exists before preparing a
research proposal.

Thank you for your time.

Kind regards,
```

## 7. 催促(返信待ちの5校)

作成日: 2026-10-02

**方針**
- 送信から2週間たっても返事がないものに、**一度だけ**送る。それでも返事がなければ「回答が得られなかった」と記録し、判断材料から外す
- 元のメールへの返信として同じスレッドで送り、質問を繰り返さない(相手が元のメールを探さなくて済むように、質問の数だけ書き添える)
- 返事が遅いことを責める書き方はしない。事務窓口が混んでいることは UTS・UOW の自動応答で分かっている

| 大学 | 元の送信日 | 催促の目安 | 備考 |
|---|---|---|---|
| ~~York~~ | 2026-09-23 | — | 2026-10-04 に返信受領。催促不要 |
| York(追加質問) | 2026-10-04 | 2026-10-18 | 1-c。本質問には回答済みなので、返事がなくても判断は進められる |
| UTS | 2026-09-23 | 2026-10-07 | 返事がなければ、自動応答にあった Zoom drop-in(平日15-16時 AEST)を使う |
| TU Delft | 2026-10-04 | 2026-10-18 | 9/23 は未送信だった。10/4 に初回送信 |
| UOW(EIS) | 2026-09-26 | 2026-10-10 | |
| ~~Swansea(追加質問)~~ | 2026-09-26 | — | 2026-10-04 に返信受領。催促不要 |

### 7-a. UOW(EIS)・TU Delft 用

```
Subject: Re: <元の件名>

Dear <元のメールと同じ宛名>,

I am writing to follow up on my enquiry below, sent on <送信日>. I
appreciate that this is a busy time of year, and I would be grateful
for any answers you are able to give to the <N> questions it raises,
or for a pointer to a more appropriate contact if this enquiry should
go elsewhere.

Kind regards,

Shisato Yano
Software engineer (autonomous driving / vehicle control), based in Japan
GitHub: https://github.com/ShisatoYano
LinkedIn: https://www.linkedin.com/in/shisatoyano
```

- `<N>`: UOW(EIS)は2、TU Delft は4(York は返信受領済み)

### 7-b. UTS 用

自動応答で、学費の質問(質問3)は GRS の管轄外と分かっている。質問3は自分で外し、残りの4問に絞ったことを伝える。

```
Subject: Re: PhD by distance — part-time enrolment and FEIT availability

Dear Graduate Research School,

I am writing to follow up on my enquiry below, sent on 23 September.
Your automatic reply noted that fee questions are handled by Ask UTS,
so please disregard question 3; I will raise it there.

I would still be grateful for guidance on the other four questions,
particularly question 1 (whether the PhD by distance can be undertaken
part-time from outside Australia) and question 2 (whether it is
available through the Faculty of Engineering and IT).

Kind regards,

Shisato Yano
Software engineer (autonomous driving / vehicle control), based in Japan
GitHub: https://github.com/ShisatoYano
LinkedIn: https://www.linkedin.com/in/shisatoyano
```

### 7-c. Swansea 用(10/10 時点で返事がなければ)

```
Subject: Re: PhD Computer Science (Distance Learning, part-time) — enquiry before proposal

Dear Dr Pauly,

A brief follow-up to my message of 26 September. There is no urgency,
but if you have a moment, I would be grateful for your view on the one
remaining point: whether a formal agreement with my employer would
still be expected if the research were entirely independent of my
employment.

Kind regards,

Shisato Yano
```

---

## 8〜13. 第1陣の照会: Tier S の6校(2026-10-02 作成)

`misc/todo.md` の 1-2。答え次第で候補から外れる、または費用が大きく変わる点だけを聞く。宛先と引用した文言は 2026-10-02 に公式ページで確認した(出典は各節)。

**6校に共通する書き方**
- 冒頭で「日本在住・フルタイム勤務・自費・研究はシミュレーション中心」と立場を示す
- **ビザ論法を先に示す**(方針どおり)。学生ビザを取らず、渡航は短期の訪問だけになることを書いてから質問する
- **勤務先との合意書については、可否ではなく「何が求められるか」を聞く。** 勤務先との取り決めは進学先が決まってから相談し直すので(2026-10-01 の決定)、照会の段階で「勤務先は署名しない」とは書かない
- TU/e・Aalto・MUN は、実質的な窓口が指導教員(または事前審査をしない)。「指導教員に連絡する前に、制度で外れないかを確かめたい」という位置づけを明示し、質問を絞る
- 署名を必ず付ける(York で付け忘れた反省)

**送る順番**(2026-10-02 決定)
- 1日目: TU/e・NTNU・Plymouth(答え次第で外れる可能性が高い、または第1候補)
- 2日目: Aalto(ELEC と ENG)・MUN・Flinders

| # | 大学 | 宛先 | 状態 |
|---|---|---|---|
| 8 | TU/e | secretariat.dc@tue.nl | 下書き |
| 9 | NTNU | postmottak@itk.ntnu.no(cc: berit.dahl@ntnu.no, lill.hege.pedersen@ntnu.no) | 下書き |
| 10 | Plymouth | doctoralcollege@plymouth.ac.uk(cc: researchdegreeadmissions@plymouth.ac.uk) | 下書き |
| 11 | Aalto(ELEC) | doctoral-sci-elec@aalto.fi | 下書き |
| 11-b | Aalto(ENG) | kitta.peura@aalto.fi, reetta.mannola@aalto.fi | 下書き |
| 12 | MUN | engrdoffice@mun.ca | 下書き |
| 13 | Flinders | hdr.admissions@flinders.edu.au(cc: gradresearch@flinders.edu.au) | 下書き |

---

## 8. TU/e — 第1候補。学費減免と日本在住の前例

**宛先**: secretariat.dc@tue.nl(Mechanical Engineering の Dynamics & Control グループの事務局)
**宛先の理由**: TU/e には PhD 出願の全学窓口が公開されていない。学費は「confirmed during the application process by the department's HR services」、減免の申請は「submitted by the (intended) promotor」とされ、学科と指導教員が窓口になる。van de Wouw の所属するグループの事務局に送り、学科の PhD 担当へ回してもらう
**狙い**: 日本在住・在職の外部 PhD を受け入れるか。減免の見込み(6年の総額が €0〜42k のどこになるか)
**出典**: [How to become a PhD candidate](https://www.tue.nl/en/education/graduate-school/phd-at-tue/how-to-become-a-phd-candidate) / [Doctoral Regulations Nov 2025](https://assets.w3.tue.nl/w/fileadmin/content/Our_University/Werken%20bij/TUe%20Doctoral%20regulations%202025%20-%20incl%20DMP.pdf) / [Dynamics and Control](https://www.tue.nl/en/research/research-groups/dynamics-and-control)

```
Subject: Self-funded external PhD candidate based in Japan — enquiry before contacting a supervisor

Dear Secretariat of the Dynamics and Control Group,

I am a software engineer based in Japan, working in autonomous driving
and vehicle control. I am considering a self-funded external PhD at
TU/e in the area of cooperative and autonomous driving (motion
planning and control), which I would pursue part-time and entirely
through simulation, while remaining in full-time employment in Japan.

I understand that the first step is to find a TU/e professor willing
to supervise the research. Before I approach a potential supervisor,
I would like to check that the arrangement is possible in principle.
If these questions are better answered by the department's PhD or HR
services, I would be grateful if you could forward this message.

1. Does the Department of Mechanical Engineering accept self-funded
   external PhD candidates who live outside the Netherlands and remain
   in full-time employment elsewhere? Are there precedents of
   candidates based outside Europe?

2. The 2026 tuition fee for self-funded external candidates is
   EUR 7,000 per year, and a waiver may be requested by the intended
   promotor, for example where the candidate is "not working fulltime
   on the PhD trajectory" or "not using the campus facilities or
   labs". Both would apply to me. In practice, are such waivers
   usually full or partial?

3. Is there a maximum duration for a part-time external PhD, and is
   the annual fee charged for every year until the defence?

4. Apart from the defence, which takes place on campus (Article 22 of
   the Doctoral Regulations), is physical presence required at any
   other point, such as a go/no-go assessment? I would be able to
   visit Eindhoven for short periods; as a Japanese citizen, I can
   stay in the Schengen area for up to 90 days without a visa.

Thank you for your time.

Kind regards,

Shisato Yano
Software engineer (autonomous driving / vehicle control), based in Japan
GitHub: https://github.com/ShisatoYano
LinkedIn: https://www.linkedin.com/in/shisatoyano
```

---

## 9. NTNU — 分野は最も合う。在職のまま時間要件を満たせるか

**宛先**: postmottak@itk.ntnu.no(Department of Engineering Cybernetics の受付アドレス)。cc に PhD 事務担当の berit.dahl@ntnu.no と lill.hege.pedersen@ntnu.no
**狙い**: フルタイム勤務のまま、時間要件(勤務時間の50%以上を研究に充てる)と3者間の合意書をどう扱うか。成り立たなければ NTNU は外れる
**確認した規程**
- 出願ページ: 「at least 50 per cent of the working hours during the doctoral degree programme are available for research education, cf. the PhD agreement. Normally, a minimum of 80 per cent of the working hours during one year must be allocated to full-time studies」「must have a minimum gross income of NOK 17,000 per month」
- PhD 規程(2026-02-03)§6-3: NTNU に雇用されていない人は「a total of one year or more」の滞在が要る。§7-1: 「The maximum admission period is a net period of six (6) years」。§7-2: 外部から資金・雇用・その他の貢献を受ける場合は3者間の合意書
- 工学部の補足規程(2025-10-05): 「In general, reductions in the residency requirement at NTNU are not granted」。ただし複数回に分けて満たせる
- → 50%で研究すると正味3年分に6年かかり、上限ちょうどで余裕がない
**出典**: [Apply and admission](https://www.ntnu.edu/studies/phtk/apply-and-admission) / [PhD regulations 2026-02-03](https://www.ntnu.edu/documents/1263185004/1285991844/NTNU+PhD-regulations+updated+20260203+(1).pdf/b9ab638d-5d97-b2bc-ab17-5a20ff1ceac0?t=1778059527861) / [工学部の補足規程](https://www.ntnu.edu/documents/1263185004/1285991844/Revidert+utfyllende+bestemmelser+i+ph.d.+forskriften_ENGELSK+05.10.25.pdf/9d394d01-0b39-0cca-df85-41a10fdc2604?t=1763989511222)

```
Subject: PhD in Engineering Cybernetics — self-funded candidate in full-time employment in Japan

Dear PhD Administration, Department of Engineering Cybernetics,

I am a software engineer based in Japan, working in autonomous driving
and vehicle control. My research interests are guidance, navigation
and control, motion planning and state estimation for autonomous
vehicles, including marine vessels, which I would pursue through
simulation. I am considering applying for the PhD in Engineering
Cybernetics with my own funds, while remaining in full-time
employment in Japan.

Before I approach a potential supervisor, I would like to understand
how the admission requirements would apply to my situation:

1. The admission page states that at least 50 per cent of the working
   hours during the programme must be available for research
   education, and that normally a minimum of 80 per cent of the
   working hours during one year must be allocated to full-time
   studies. For a candidate in full-time employment who would carry
   out the research outside working hours, how is this requirement
   assessed? Does it require the employer to formally allocate
   working time to the PhD?

2. Section 7-2 of the PhD regulations requires a separate agreement
   between the candidate, NTNU and the external party where the
   candidate is employed by an external party. If my employer would
   provide no funding, time or other contribution, and the research
   would be independent of my employment, what would the employer be
   expected to commit to in this agreement?

3. I understand that the residency requirement of one year may be
   fulfilled by accumulating several periods. Would it be acceptable
   to complete it in, for example, three or four stays of three to
   four months each over the course of the programme?

4. The maximum admission period is a net period of six years. If the
   research were carried out at 50 per cent, would an extension
   beyond six years be possible?

5. My own funds would come from my salary in Japan, which exceeds the
   minimum gross income of NOK 17,000 per month. What documentation
   of funding would be accepted for this?

Thank you for your time.

Kind regards,

Shisato Yano
Software engineer (autonomous driving / vehicle control), based in Japan
GitHub: https://github.com/ShisatoYano
LinkedIn: https://www.linkedin.com/in/shisatoyano
```

---

## 10. Plymouth — 船舶系で最安級。来校と現地指導者の条件

**宛先**: doctoralcollege@plymouth.ac.uk(出願前の質問の窓口)。学費の質問を含むので、cc に researchdegreeadmissions@plymouth.ac.uk(学費の窓口)
**狙い**: 年6週の来校が現行でも必須か、日本側の現地指導者の資格要件、海外研究の料金を受けられるか
**前提**: 2026-10-02 時点で、日本側で現地指導者を頼めそうな人はいない。→ 質問3では資格要件に加えて、大学が探すのを手伝うか、現地指導者なしの代替策があるかを聞く。**現地指導者が必須で代替策もなければ、Plymouth は外れる**
**確認したこと**
- 2026-27年の料金表: 「Research carried out overseas (MPhil/PhD/MD only) Band 2」の PT 国際料金は £4,830。対象者の条件は書かれていない
- 料金表の注記: 2024-08-01以降に入学する PT は、writing-up に入る前に「registered at least 6 years PT for PhD」。一方 PhD Robotics のページは「you will pay part time fees for four years」で、食い違っている
- PhD Mechanical Engineering のページ: 「Remote supervision of overseas students is possible subject to identification of a supervisor local to the candidate」(Robotics のページにはこの文はない)
- 年6週の来校は2017年版の Code of Practice にしかなく、現行の Handbook はログインが要る
- 2026-27 Fees Policy: 英国外から在籍する場合、居住国の sales tax を上乗せすることがある
**出典**: [PGR fees 2026-27](https://www.plymouth.ac.uk/study/fees/tuition-fees-for-postgraduate-research-students-2026-27) / [PhD Mechanical Engineering](https://www.plymouth.ac.uk/courses/postgraduate/phd-mechanical-engineering) / [Research degree awards](https://www.plymouth.ac.uk/study/postgraduate/research-degree-awards)

```
Subject: Part-time PhD with research carried out overseas (Japan) — attendance, local supervisor and fees

Dear Doctoral College Admissions Team,

I am a software engineer based in Japan, working in autonomous driving
and vehicle control. I am interested in a part-time PhD in the School
of Engineering, Computing and Mathematics, in the area of marine
autonomy (navigation, guidance and control of autonomous vessels),
pursued through simulation. I would carry out the research in Japan
while remaining in full-time employment there. I would not apply for
a Student visa; any visits to Plymouth would be short.

Before I contact a potential supervisor, I would be grateful for
clarification on the following:

1. The 2026-27 fee table lists a part-time international rate of
   GBP 4,830 per year for "Research carried out overseas" (Band 2).
   Would a part-time candidate living and researching in Japan, as
   described above, be eligible for this rate?

2. Earlier versions of the Research Degrees Code of Practice required
   candidates conducting their research mainly overseas to spend at
   least six weeks a year at the University. Is this still the
   current requirement?

3. The PhD Mechanical Engineering page states that remote supervision
   of overseas students is possible "subject to identification of a
   supervisor local to the candidate". What qualifications must the
   local supervisor have, and must they hold a doctorate? At present I
   do not have a suitable person in Japan in mind. Does the University
   help candidates identify a local supervisor, or are there
   alternative arrangements where none is available?

4. The fee table notes that part-time PhD students starting on or
   after 1 August 2024 must be registered for at least six years
   before writing up, while the PhD Robotics page states that
   part-time students pay part-time fees for four years. Which
   applies?

5. The Fees Policy notes that a sales tax at the local rate may be
   added for students studying from outside the UK. Would this apply
   to a student resident in Japan?

Thank you for your time.

Kind regards,

Shisato Yano
Software engineer (autonomous driving / vehicle control), based in Japan
GitHub: https://github.com/ShisatoYano
LinkedIn: https://www.linkedin.com/in/shisatoyano
```

---

## 11. Aalto(ELEC)— 学費ゼロ。居住の最低期間

**宛先**: doctoral-sci-elec@aalto.fi(Doctoral Programme in Electrical Engineering の出願窓口。School of Science と共用)
**宛先の理由**: 制御・ロボット・自律システムは ELEC、自律船は ENG(Marine Technology)。研究テーマを車両系と船舶系のどちらに寄せるかはまだ決めていない(`misc/todo.md` 2-2)ので、**両方に送る**(2026-10-02 決定)。同じ大学の別の窓口に同じ質問を送ることになるので、両方の文面に「もう一方にも送っている」と明記し、回答が重複してもよいことを示す。居住の文言は両プログラムで同じ
**狙い**: 「reside in Finland at least part of the study time」の最低期間。12か月以内に収まるか
**確認したこと**
- 「It is also possible to start pursuing doctoral studies without funding (part-time doctoral studies). In this case, please contact the potential supervising professor directly. Note that to pursue the degree, you need to reside in Finland at least part of the study time.」→ 月数は書かれていない。資金なしの PT は指導教員に直接連絡するよう案内されているので、質問は居住の1点に絞る
- 勤務先の承認書が要るのは「Full-time students working outside of Aalto University」だけ
- 「Aalto University doctoral studies are free of tuition fees」。ELEC の出願は通年(2026-12-01まで、7月は処理しない)
**出典**: [Aalto Doctoral Programme in Electrical Engineering](https://www.aalto.fi/en/study-options/aalto-doctoral-programme-in-electrical-engineering) / [Aalto Doctoral Programme in Engineering](https://www.aalto.fi/en/study-options/aalto-doctoral-programme-in-engineering)

```
Subject: Part-time doctoral studies without funding — residence requirement for a candidate based in Japan

Dear Doctoral Programme in Electrical Engineering Admissions Team,

I am a software engineer based in Japan, working in autonomous driving
and vehicle control, with research interests in motion planning,
control and state estimation for autonomous vehicles. I am considering
part-time doctoral studies without funding, while remaining in
full-time employment in Japan.

I understand that for part-time doctoral studies I should contact a
potential supervising professor directly, and I intend to do so. Before
that, I would like to check one point about eligibility. The programme
page notes that "to pursue the degree, you need to reside in Finland
at least part of the study time".

1. Is there a minimum length for this period of residence?

2. Could it be fulfilled through several shorter stays rather than one
   continuous period? As a Japanese citizen, I can stay in the
   Schengen area for up to 90 days without a residence permit.

3. I understand that an employer's approval document is required only
   for full-time students working outside Aalto. Could you confirm
   that it is not required for a part-time student?

As my interests span both programmes, I am sending the same questions
to the Aalto Doctoral Programme in Engineering. Please feel free to
leave them to whichever office is more appropriate.

Thank you for your time.

Kind regards,

Shisato Yano
Software engineer (autonomous driving / vehicle control), based in Japan
GitHub: https://github.com/ShisatoYano
LinkedIn: https://www.linkedin.com/in/shisatoyano
```

---

### 11-b. Aalto(ENG)

**宛先**: kitta.peura@aalto.fi(planning officer)、reetta.mannola@aalto.fi(coordinator)。ENG の Contact information ページで、どちらも「applications for doctoral studies」の担当として載っている。役職のアドレスがないので、2人を並べて宛先にする
**ENG 固有の点**: PT は「Their studies are planned in such a way that the time spent on doctoral studies is eight years or less」。出願は年4回で、今期は 2026-06-03〜2026-11-03
**出典**: [ENG Contact information](https://www.aalto.fi/en/programmes/aalto-doctoral-programme-in-engineering/contact-information) / [Aalto Doctoral Programme in Engineering](https://www.aalto.fi/en/study-options/aalto-doctoral-programme-in-engineering)

```
Subject: Part-time doctoral studies without funding — residence requirement for a candidate based in Japan

Dear Doctoral Education Services, Aalto Doctoral Programme in Engineering,

I am a software engineer based in Japan, working in autonomous driving
and vehicle control, with research interests in guidance, navigation
and control of autonomous vehicles, including autonomous ships. I am
considering part-time doctoral studies without funding, while
remaining in full-time employment in Japan.

I understand that for part-time doctoral studies I should contact a
potential supervising professor directly, and I intend to do so. Before
that, I would like to check one point about eligibility. The programme
page notes that "to pursue the degree, you need to reside in Finland
at least part of the study time".

1. Is there a minimum length for this period of residence?

2. Could it be fulfilled through several shorter stays rather than one
   continuous period? As a Japanese citizen, I can stay in the
   Schengen area for up to 90 days without a residence permit.

3. Is a statement from my employer required for part-time doctoral
   studies?

As my interests span both programmes, I am sending the same questions
to the Aalto Doctoral Programme in Electrical Engineering. Please feel
free to leave them to whichever office is more appropriate.

Thank you for your time.

Kind regards,

Shisato Yano
Software engineer (autonomous driving / vehicle control), based in Japan
GitHub: https://github.com/ShisatoYano
LinkedIn: https://www.linkedin.com/in/shisatoyano
```

---

## 12. MUN — 船舶系で最安。学外で居住要件を満たせるか

**宛先**: engrdoffice@mun.ca(Faculty of Engineering and Applied Science の Graduate Office。2026-04-22更新の Contact us で確認)
**注意**: FAQ に「We do not provide one-on-one pre-assessment for MEng and PhD applications」「Admission is conditional on acceptance of a faculty member as supervisor」とある。**経歴の評価は頼まず、制度の質問だけにする**
**狙い**: 3学期の居住要件を、学外(日本)のまま Dean の承認で満たせるか
**確認したこと**
- Calendar 4.3.5: 「each student for a Ph.D. … shall normally spend at least three semesters in residence」。ただし「it is possible therefore that the residency requirement may be satisfied in an off campus location. In such cases the Dean of Graduate Studies must be satisfied that the attributes are met」。在籍の上限は「seven years beyond first registration」
- Calendar 44.12: 工学の PhD は「may be obtained either through full-time or part-time studies」。comprehensive exam は口頭試問で「open to the University community」、通常は4学期以内
- 学費(2026-08-19更新): 博士の国際学生は Program Cost CA$17,988(12学期で分割)、その後は1学期 CA$1,466 の continuance fee。→ **前回のメモの CA$26.8k は誤り。** PT で6〜7年なら約 CA$27〜31k(推定)
**出典**: [Contact us](https://www.mun.ca/engineering/graduate/contact-us/) / [FAQ](https://www.mun.ca/engineering/graduate/faq-for-prospective-research-students/) / [Calendar 4.3](https://www.mun.ca/university-calendar/school-of-graduate-studies/school-of-graduate-studies/4/3/) / [Calendar 44.12](https://www.mun.ca/university-calendar/school-of-graduate-studies/school-of-graduate-studies/44/12/) / [Graduate tuition](https://www.mun.ca/finance/graduate-student-tuition-and-fees/)

```
Subject: Part-time PhD in Engineering from outside Canada — residency requirement

Dear Engineering Graduate Office,

I am a software engineer based in Japan, working in autonomous driving
and vehicle control. I am interested in the PhD in Engineering on a
part-time basis, in the area of autonomous marine vehicles (state
estimation, navigation and control), pursued through simulation. I
would remain in full-time employment in Japan and would not apply for
a study permit; any visits to St. John's would be short.

I understand that admission depends on a faculty member agreeing to
supervise, and that the Faculty does not offer pre-assessments, so I
am not asking for an evaluation of my background. I would be grateful
for clarification on a few procedural points:

1. Section 4.3.5 of the Graduate Calendar states that the residency
   requirement of three semesters "may be satisfied in an off campus
   location" if the Dean of Graduate Studies is satisfied that the
   required attributes are met. Has this been approved for part-time
   PhD candidates in Engineering who live outside Canada? If so, what
   would normally need to be shown, for example regular online
   meetings with the supervisor and participation in the research
   group?

2. Is the part-time PhD route in Engineering open to international
   candidates who live outside Canada throughout the programme?

3. Can the comprehensive examination and the thesis proposal
   presentation be taken online, or is attendance in person required?

4. For doctoral students, the tuition page lists a program cost of
   CAD 17,988 paid over 12 semesters, followed by a continuance fee
   for each additional semester. Does the same structure apply to
   part-time doctoral students?

Thank you for your time.

Kind regards,

Shisato Yano
Software engineer (autonomous driving / vehicle control), based in Japan
GitHub: https://github.com/ShisatoYano
LinkedIn: https://www.linkedin.com/in/shisatoyano
```

---

## 13. Flinders — Tier A で唯一の来校ゼロ候補

**宛先**: hdr.admissions@flinders.edu.au(Office of Graduate Research の出願窓口。cc に gradresearch@flinders.edu.au)
**注意**: 現行の国際向け HDR ページにはメールアドレスがなく、AskFlinders ポータルに誘導している。アドレスは OGR のブログ(2025-01)と担当一覧(2022)で確認したもの。**返事がなければ同じ文面を AskFlinders から送る**
**狙い**: 海外在住の留学生が、PhD (Engineering) に Online モードの PT で入れるか
**確認したこと(前回のメモからの訂正を含む)**
- HDR Admission and Enrolment Procedures(2025-11-20改正): 「Online: … No in person attendance is required. [Note: this mode of delivery was previously termed 'external']」。§4.3(b)(ii): Online 系のモードでは、本人と指導教員が「HDR Online Plus Study Agreement」を出す
- **一方、PhD (Engineering) のコースページは、国際学生には「Delivery mode: In Person」しか表示していない**
- 「Complete your HDR from anywhere in the world」は、オンラインの在籍管理システム(Inspire)の説明で、**オンラインで在籍できるという意味ではない**(前回のメモの解釈を訂正)
- 学費 2026年: PhD (Engineering) 年 A$44,800。研究学位の PT 料金の明文はなく、「based on the number of days of candidature in each half-year period」
**出典**: [HDR Admission and Enrolment Procedures](https://www.flinders.edu.au/content/dam/documents/staff/policies/academic-students/hdr-admission-enrolment-procedures.pdf) / [PhD (Engineering)](https://www.flinders.edu.au/study/courses/doctor-philosophy-phd-engineering) / [Meet the OGR](https://blogs.flinders.edu.au/hdr-students/2025/01/29/meet-the-ogr/) / [Fee schedule 2026](https://www.flinders.edu.au/content/dam/documents/study/international/international-commencing-tuition-fee-schedule-2026.pdf) / [Tuition fees procedures](https://www.flinders.edu.au/content/dam/documents/staff/policies/academic-students/international-student-tuition-fees-procedures.pdf)

```
Subject: PhD (Engineering) in Online mode, part-time, for an international applicant based in Japan

Dear HDR Admissions Team,

I am a software engineer based in Japan, working in autonomous driving
and vehicle control. I am interested in a PhD (Engineering) in the
area of autonomous marine vehicles (navigation, guidance and control),
pursued through simulation, and the work of the Maritime Engineering
and Robotics group appears to be a close match. I would remain in
full-time employment in Japan and would not apply for a student visa.

Before I approach a potential supervisor, I would be grateful for
clarification on the following:

1. The HDR Admission and Enrolment Procedures define an "Online" mode
   in which "no in person attendance is required", supported by an HDR
   Online Plus Study Agreement. The PhD (Engineering) course page,
   however, shows only "In Person" delivery for international
   students. Can an international applicant living in Japan be
   admitted to the PhD (Engineering) in Online mode?

2. The procedures restrict part-time candidature for international
   students studying in Australia on a student visa. Is part-time
   candidature available to an international candidate studying
   online from overseas?

3. In Online mode, can milestones such as the confirmation of
   candidature be completed online, or is any visit to Adelaide
   required?

4. The 2026 annual fee for the PhD (Engineering) is AUD 44,800. For a
   part-time candidate, would the fee be 50 per cent of this amount?

5. If I study in my own time outside working hours, would my employer
   still need to confirm study release?

Thank you for your time.

Kind regards,

Shisato Yano
Software engineer (autonomous driving / vehicle control), based in Japan
GitHub: https://github.com/ShisatoYano
LinkedIn: https://www.linkedin.com/in/shisatoyano
```

---

## 返信を受けた後にやること

- 各校の `labs/<大学名>.md` の「未確認事項」を、回答内容に置き換える(**返信本文は逐語引用せず要旨のみ**)
- `labs/_candidates.md` の判定(◎○△×)を更新
- 制度面が確定した時点で、`research-theme/` の具体化状況と突き合わせ、**教授への打診に進む大学を1〜2校に絞る**
