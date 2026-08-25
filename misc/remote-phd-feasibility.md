# フルリモートPhDの実現性調査

## 調査目的

日本在住・フルリモートで海外大学のPhD(自動運転・自律移動系、実機検証を伴わないシミュレーション・アルゴリズム中心テーマ)を実現する現実性を調べる。

## 制度的にリモートを認めているパターン

### 1. Distance Learning PhD (公式プログラムとして存在)

- **Swansea University** (英国) - Electronic and Electrical Engineering / Aerospace Engineering で "Ph.D. Distance Learning" を公式提供。
  - 指導教員との定例ミーティングは最低月1回(オンライン可)
  - キャンパス訪問は基本的に任意(要求された場合のみ)
  - 通常のPhDと同じ大学規定が適用され、審査基準に差はない
  - 出願要件: 学部で2.1相当の成績、IELTS 6.5等
  - [Electronic and Electrical Engineering, Ph.D. Distance Learning](https://www.swansea.ac.uk/postgraduate/research/aerospace-civil-electrical-mechanical-engineering/electrical/phd-electronic-and-electrical-engineering-distance-learning/)
  - [Aerospace Engineering, Ph.D. Distance Learning](https://www.swansea.ac.uk/postgraduate/research/aerospace-civil-electrical-mechanical-engineering/aerospace/phd-aerospace-engineering-distance-learning/)

- **University of Technology Sydney (UTS)** (オーストラリア) - "PhD by Distance" を提供。国際学生も対象で、ビザ取得不要。
  - 学位の質・審査要件はキャンパス生と同等
  - 奨学金の一部は距離生も対象になり得る
  - [PhD by distance | UTS](https://www.uts.edu.au/research/graduate/future-research-students/phd-distance)

→ どちらも工学系(電気・航空)での公式リモートPhDの実例。**分野を問わず、まず「Distance PhD」を公式に提供している大学かどうかを確認するのが最も確実なルート**。

### 2. Split-site / Sandwich PhD (2拠点型)

- **Commonwealth Split-site Scholarships**、Manchester大学の split-site PhD制度など。ホスト大学(海外)と自国の supervisor の両方に登録し、期間を分けて研究する形式。
  - 主指導教員はホスト大学側、月1回以上の面談(対面 or オンライン)
  - Commonwealth Split-site は低中所得国の学生が対象のため、**日本在住者は対象外の可能性が高い**(要個別確認)
  - [Split-site PhDs (Manchester)](https://documents.manchester.ac.uk/display.aspx?DocID=30521)
  - Wageningen の Sandwich PhD: 最初9か月はホスト大学、その後30か月は自国で研究、最後9か月はホスト大学で仕上げ、という設計。フルリモートではないが「大半の期間を自国で過ごす」設計の参考になる。

→ 完全リモートではなく「一定期間の現地滞在+大半は自国」という折衷案。フルリモートに固執しない場合の選択肢として記録。

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
