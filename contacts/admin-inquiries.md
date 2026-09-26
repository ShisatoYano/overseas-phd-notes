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
| York | cs-pgr-admissions@york.ac.uk | 2026-09-23 | | **返信待ち** |
| York(署名追補) | 同上(同一スレッド) | 2026-09-23 | | **送信済**(下記1-b) |
| UTS | grs@uts.edu.au | 2026-09-23 | (自動応答のみ) | **返信待ち** |
| TU Delft | 3mE Graduate School(宛先はユーザーが確認のうえ送信) | 2026-09-23 | | **返信待ち** |
| UOW | graduate-research-school@uow.edu.au | 2026-09-23 | 2026-09-26 | **返信受領(定型文。質問1〜4いずれも未回答)** |
| UOW(HPS) | ~~hoang_dung_duong@uow.edu.au~~ | 2026-09-23 | — | **不達(宛先不明)** |
| UOW(EIS) | ddgr-eis@uow.edu.au | 2026-09-26 | | **返信待ち**(下記6) |
| Swansea | a.m.pauly@swansea.ac.uk | 2026-09-23 | 2026-09-26 | **返信受領(質問1〜4すべてに回答あり)** |
| Swansea(お礼・追加質問) | 同上(同一スレッド) | 2026-09-26 | | **返信待ち**(独立した個人研究の場合に勤務先との合意書が要るか) |

署名はいずれも以下を想定(氏名以外はご自身で補う)。

```
Shisato Yano
Software engineer (autonomous driving / vehicle control), based in Japan
GitHub: https://github.com/ShisatoYano/AutonomousVehicleControlBeginnersGuide
```

OSSのリンクを添えるのは、York が「非標準の経歴でも十分なCSの知識と経験を示せれば考慮する」と明記しているため。事務照会の段階では必須ではないが、経歴の裏付けとして機能する。

## 送信前チェックリスト

1. **宛先アドレスが現在も有効か**、公式ページで確認する
2. **宛名(Dear ...)が現在の正式名称と一致するか**(例: TU Delft は「Graduate School 3mE」と「Graduate School ME」の表記が混在している)
3. **コースコード・学費・年限など、本文で引用した数値が最新か**(年度で変わる)
4. **署名を入れたか** — 氏名 + 所在国 + 職種 + OSSのリンク
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

---

## 2. TU Delft — テーマ適合度トップだが不確実性最大

**宛先**: **要確認**。[3mE Graduate School の Contact ページ](https://www.tudelft.nl/en/me/research/graduate-school-me/contact)に窓口担当者の記載はあるがメールアドレスが取得できていない。送信前に同ページで確認する
**狙い**: 3mE が外部PhDを受け入れるか、「stay where you live」に日本が含まれるか

```
Subject: External PhD candidate based outside Europe — enquiry (Cognitive Robotics)

Dear Graduate School 3mE,

I am a software engineer based in Japan, working in autonomous driving
and vehicle control. My research interests — motion planning, control,
and multi-robot coordination — align closely with the Cognitive
Robotics department, in particular the Autonomous Multi-robots Lab and
the Learning and Autonomous Control group.

The TU Delft PhD pages state that an alternative to full-time study is
to "keep your current job and/or stay where you live and work on your
project part-time as an external PhD candidate". Before approaching a
potential promotor, I would like to establish whether this route is
open to me in practice:

1. Does Graduate School 3mE currently accept external PhD candidates,
   and does it accept self-funded candidates? I ask because I
   understand the Faculty of Architecture and the Built Environment
   stopped accepting self-funded candidates from 1 January 2025, and
   I would like to know whether 3mE applies a similar policy.

2. Does "stay where you live" extend to a candidate residing outside
   Europe — specifically, in Japan — for the whole of the doctoral
   programme? Are there precedents of external candidates supervised
   remotely from outside the EU?

3. The bench fee of €10,000 per year is described as covering
   workspace and laboratory access, determined by anticipated use of
   facilities. For a candidate whose research is entirely
   computational and who would not use campus facilities, can this
   fee be reduced or waived?

4. What is the maximum duration for a part-time external PhD?

5. Is physical presence in Delft required at any point, for example
   for the go/no-go assessment or the doctoral defence?

Thank you for your time.

Kind regards,
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

## 返信を受けた後にやること

- 各校の `labs/<大学名>.md` の「未確認事項」を、回答内容に置き換える(**返信本文は逐語引用せず要旨のみ**)
- `labs/_candidates.md` の判定(◎○△×)を更新
- 制度面が確定した時点で、`research-theme/` の具体化状況と突き合わせ、**教授への打診に進む大学を1〜2校に絞る**
