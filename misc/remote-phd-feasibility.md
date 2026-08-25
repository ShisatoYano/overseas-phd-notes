# フルリモートPhDの実現性調査

## 調査目的

日本在住・フルリモートで海外大学のPhD(自動運転・自律移動系、実機検証を伴わないシミュレーション・アルゴリズム中心テーマ)を実現する現実性を調べる。

## 制度的にリモートを認めているパターン

### 1. Distance Learning PhD (公式プログラムとして存在)

- **Swansea University** (英国) - Electronic and Electrical Engineering / Aerospace Engineering で "Ph.D. Distance Learning" を公式提供。
  - 期間: フルタイム3年、開始は10月/1月/4月/7月の年4回
  - 出願要件: 学部で2.1相当の成績(工学または関連科学分野)、IELTS 6.5(各項目5.5以上)、推薦状1通、非UK/EU出願者はATAS(学術技術承認制度)クリアランス必須
  - リモート実施の要件: 指導教員との定例面談を**月1回以上厳格に実施**、学部主催の月例研究セミナー等にリモート参加、**安定したインターネット接続の実証**、研究拠点での郵便・配送サービス利用可能性の証明が求められる。実験室での製造・測定が必須なテーマは対面が必要
  - 学費(2026年10月入学): UK £5,238/年、国際 £25,000/年(2年目以降は年3%値上げ)
  - 研究テーマ例(Electrical): パワー半導体・パワーエレクトロニクス、機械学習による太陽光発電予測、光電力システムの制御設計、マルチゲートトランジスタのモンテカルロシミュレーション
  - 研究テーマ例(Aerospace): 複合構造の不確実性定量化、モーフィング構造、等幾何有限要素法、高速粘性空力流のCFDシミュレーション → **経路計画・制御そのものではないが、シミュレーション/数値モデリング主体の研究が多く、テーマの相性は良さそう**
  - 出願は先に研究提案書を用意し分野担当官(engineering@swansea.ac.uk)に相談してから正式出願が推奨。10月入学なら国際出願は7月15日締切
  - [Electronic and Electrical Engineering, Ph.D. Distance Learning](https://www.swansea.ac.uk/postgraduate/research/aerospace-civil-electrical-mechanical-engineering/electrical/phd-electronic-and-electrical-engineering-distance-learning/)
  - [Aerospace Engineering, Ph.D. Distance Learning](https://www.swansea.ac.uk/postgraduate/research/aerospace-civil-electrical-mechanical-engineering/aerospace/phd-aerospace-engineering-distance-learning/)

- **University of Technology Sydney (UTS)** (オーストラリア) - "PhD by Distance" を提供。「ビザ申請や転居なしにグローバルな文脈で研究者としてのキャリアを築く」という位置づけ。
  - 候補資格審査(candidature stage assessment)、学生規則、想定される研究期間はキャンパス生と同一
  - 学費はキャンパス生の国際学生と同額(奨学金対象になる場合あり)
  - 指導教員との連絡頻度・キャンパス訪問要否・対応研究分野(工学系の有無)は当該ページに明記がなく、要個別確認(Admissions requirements / 各学部ページを別途参照する必要あり)
  - [PhD by distance | UTS](https://www.uts.edu.au/research/graduate/future-research-students/phd-distance)

→ どちらも工学系(電気・航空)での公式リモートPhDの実例。**分野を問わず、まず「Distance PhD」を公式に提供している大学かどうかを確認するのが最も確実なルート**。

### 2. Split-site / Sandwich PhD (2拠点型)

ホスト大学(海外)と自国側の指導体制を組み合わせ、現地滞在期間を圧縮する制度。**完全リモートではないが、現地滞在を数か月〜1年程度に抑えられる**という点で、フルリモートが難しい場合の代替案になる。

- **University of Manchester の Split-site PhD**
  - 学位はManchester大学から授与される(Manchesterが学位授与機関)
  - 主指導教員は必ずManchester側に所属し、**学生・主指導教員は月1回以上面談**(対面/オンライン問わず)。提携機関側にも副指導教員を置く
  - 最低在籍期間はフルタイム3年/パートタイム6年
  - 提携機関はManchesterと機関レベルの連携協定が必要(個人の交渉だけでは組成できない)
  - [Split-site PhDs (Manchester)](https://documents.manchester.ac.uk/display.aspx?DocID=30521) / [PGR Policy(規定)](https://www.regulations.manchester.ac.uk/pgr-split-site-phd-arrangements/)

- **Commonwealth Split-site Scholarships** (Bath, Cranfield等の英国大学が実施)
  - 母国の大学でPhDに登録済みの学生が、英国の大学に**最大12か月**滞在して研究する形式。学費全額・往復航空券・生活費(月£1,378程度)等が支給される手厚い制度
  - **対象はCommonwealth加盟の低中所得国の国籍者に限定されており、日本は対象外**
  - Cranfield大学の同制度は現在レビュー中で2026年の募集は行われていない(要最新確認)
  - [Commonwealth Split-site Scholarship (Bath)](https://www.bath.ac.uk/guides/commonwealth-split-site-scholarship/) / [Commonwealth Split-site PhD Scholarships (Cranfield)](https://www.cranfield.ac.uk/funding/funding-opportunities/commonwealth-split-site-phd-scholarships)

- **Wageningen University & Research (オランダ) の Sandwich PhD Programme**
  - 全体で約48か月: 最初と最後の**計約9か月をWageningenで**、中間の**約30か月を自国で**研究する構成
  - 自国側の指導教員が副指導教員を兼務し、Wageningen側の主指導教員とオンラインで定期連絡、節目には相互訪問も行う
  - 応募者は修士号保持者で「selected countries」出身であることが条件、かつ博士課程全体を通じて自国の所属機関に雇用されている必要がある(**対象国リストは要確認だが、開発途上国向けの人材育成色が強く、日本は対象外の可能性が高い**)
  - 生物システム工学など工学系分野も対象。資金は生活費(18か月分)・渡航費・ビザ費用・施設利用料をカバー。応募は毎年春
  - [WGS Sandwich PhD Programme](https://www.wur.nl/en/education/phd-programme/funding/wgs-sandwich-phd-programme)

→ **注意点**: Commonwealth系・Wageningen系のSplit-site/Sandwich制度は、多くが「途上国の人材育成」を目的とした奨学金プログラムであり、**日本在住者は対象外になりやすい**。一方Manchesterのように国籍を問わない制度上のSplit-site PhDの枠組みもあるが、これは提携機関(自国側の大学・研究機関)との機関レベルの連携が前提のため、**個人で申し込める制度ではない**点に注意。

## 非制度的な実現パターン(個別交渉)

- note記事「[フルリモートで博士課程を行う](https://note.com/former_surname/n/n03e457f96954)」(社会科学分野、実験・施設不要な研究):
  - 公式のDistance PhD制度ではなく、**過去に面識のあった教授に直接連絡し、事情を説明して個別に受け入れを合意してもらった**という実例
  - 課題: 「研究の壁打ち相手がいない」ことが最大のボトルネック、家族の理解(時間管理の可視化が難しい)、TA等の教育機会は対面必須のため得られない
  - 分野は自動運転・ロボティクス・制御とは無関係(社会科学)だが、「実験・施設不要」という条件は自分の志向するシミュレーション中心テーマと共通するため、実現パターンとしては参考になる

→ 公式制度がない大学・研究室でも、**指導教員個人との合意ベースでリモートPhDが成立する例がある**。ただし孤立しやすいという副作用は要注意。

## 自動運転・ロボティクス・制御分野特有の留意点

- 検索で「remote/virtual lab in control education」の研究(José Sánchez 等)が多く見つかったが、これは**遠隔で制御工学の実験環境をオンライン提供する研究テーマ**であり、「リモートでPhDを受け入れている実例」ではない。検索時に混同しやすいので注記。
- 自動運転・ロボティクス分野のPhDは実機・実験室作業を伴う研究室が多数派で、そうした研究室はフルリモートに不向きと想定される。
- → 既存の方針(`research-theme/candidates.md`: 経路計画・制御・モデル推定でシミュレーション/アルゴリズム中心)は、リモート実現性の観点からも妥当な絞り込み。

## まとめ・次のアクション

1. `labs/` で研究室調査する際、以下を優先的に確認する
   - 大学として Distance PhD / PhD by Distance を公式提供しているか(Swansea, UTSのような制度がある大学は狙い目)
   - 公式制度がなくても、指導教員個人がリモート学生の受け入れに前向きか(業績・過去の学生構成・SNS等での言及)
2. Split-site型(現地滞在を一部組み込む)も選択肢として排除しない。完全リモートにこだわりすぎると候補が過度に狭まるリスクがある。
3. 孤立対策(壁打ち相手不足)は今後の課題として意識しておく(コミュニティ・共同研究者の確保などは`interview/`や`contacts/`検討時に反映)。
