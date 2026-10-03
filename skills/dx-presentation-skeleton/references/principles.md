# 骨子作成の原則と根拠

骨子を作るときに守る原則。各原則の出典を併記する。

## 1. 全体の組み立て

| 原則 | 内容 | 出典・根拠 |
|---|---|---|
| ピラミッド原則 | 一番言うべきことを頂点に置き、その下に根拠を並べる。根拠は互いに重複せず、漏れがないようにする | Barbara Minto『The Pyramid Principle』（McKinsey） |
| SCQA | 導入は 状況 → 問題・変化 → 問い → 答え の順。答えが一番言うべきこと | 同上 |
| 結論先行（PREP） | 結論 → 理由 → 具体例 → 結論 の順で話す | PREP法 |
| 空・雨・傘 | 事実（空）→ 解釈（雨）→ 行動（傘）。各ページで「だから何か（So What）」と「なぜそう言えるか（Why So）」を確かめる | コンサルティング会社の思考法 |

## 2. ページの作り方

| 原則 | 内容 | 出典・根拠 |
|---|---|---|
| アクションタイトル | タイトルは結論を文章で書く。名詞だけのタイトルにしない | コンサルティング会社のスライド作法 |
| タイトルテスト／ゴーストデッキ | 本文を作る前にタイトルだけを並べ、それだけで話が通じるか確かめる | 同上 |
| 主張と根拠（Assertion-Evidence） | 2行以内の文章タイトル＋図・写真・グラフによる根拠。箇条書きを避ける。箇条書き型より理解・記憶が良いという研究結果がある | Michael Alley（ペンシルベニア州立大学）、ASEE（米国工学教育学会）論文 |
| 1ページ1メッセージ | 1ページで言うことは1つ | 上記に共通 |
| 横の論理・縦の論理 | 横：タイトルを順に読んで話が通るか。縦：各ページの図がタイトルを証明しているか | コンサルティング会社のレビュー作法 |
| 根拠は3点以内 | 1ページの根拠は最大3点。各ページの間に「つなぎ」を置き、最後に依頼事項を置く | 既存スキル presentation-writing-claude-skill |
| 図は1つ、言いたい点を書き込む | 結果のページは図を1つに絞り、注目点を図に直接書く。出典を付ける。最終ページは結論のまま質疑に入る | 既存スキル academic-pptx-skill |
| 現状とあるべき姿の対比 | 現状（what is）とあるべき姿（what could be）の差を示し、提案をその差を埋める手段として出す | Nancy Duarte『Resonate』 |
| 文章で論理を詰める | 箇条書きは論理の飛びを隠す。事前配布資料は文章で書き、論理のつながりを示す | Amazon の6ページメモ |
| AIらしい言い回しを消す | 数字のない抽象語、毎回揃った3点の箇条書きを避ける。「人に向かって口に出して言うか」で確かめる | 既存スキル presentation-writing-claude-skill |
| 工程を分けて人が確認する | 前提整理 → 構成案 → 本文 → 図表 → レビューの順に進め、各段階で人が直す | 国内の生成AI資料作成ガイド |

## 3. 場面別の土台

| 場面 | 土台 | 要点 |
|---|---|---|
| 稟議（A1） | 稟議書の記載項目 | 件名・依頼事項・目的・投資額・効果・回収期間・リスク。運営費＋減価償却費を上回る効果があるか |
| 進捗報告（B1・E2） | 信号表示（青・黄・赤） | 悪い知らせを先に。上位者ほど詳細を減らし、判断が必要な事項を目立たせる |
| 展示会等の報告（B2） | 視察報告書の作法 | 事前に目的と質問を決める。各トピックに「自社への示唆」を1行付け、関係の深い順に並べる |
| 検証（C1） | PoCの進め方 | 目的・基準の設定 → 範囲の限定 → 計画 → 実施 → 評価・意思決定。基準は事前に数値で合意する。観点は価値・技術・事業性 |
| 原因分析（C1-2） | トヨタのA3報告書 | 背景 → 現状 → 目標 → 原因分析 → 対策 → 実行計画 → フォローアップ。1枚に収まらなければ理解が足りない |
| DXロードマップ（型E） | デジタルガバナンス・コード3.0（経済産業省、2024年） | DXを経営・企業価値向上と結び付けて示す |

## 4. 利用者の状況に合わせた原則

| 原則 | 内容 |
|---|---|
| 顧客成果につなげる | 効果は現場KPI → 工場KGI → 顧客成果 → 事業（EBIT・サービス収益）の順につなげる。QCDは手段 |
| ライフサイクルで見る | 設計・製造・運用・保全のどこに効くかを示す |
| 安全・法令・倫理が前提 | 該当する案件では必ず扱う |
| データ主権とセキュリティ | 社外とのデータ連携、クラウド利用、ベンダーとの打合せでは必ず扱う |
| 統計の根拠 | 効果や合否はばらつき（σ、Cp/Cpk など）を含めて示す。平均値だけで判断しない |
| 骨子の段階で上司と合わせる | PPT化の前に、骨子（一番言うべきこと＋タイトル一覧）を上司に見せて方向を確認する |

## 5. 既存のスキル・ツールから取り入れたこと

| 既存のもの | 取り入れたこと | 取り入れなかったこと |
|---|---|---|
| presentation-writing-claude-skill（物語の型7種、1ページ1主張） | 根拠3点以内、つなぎ、最後に依頼、AIらしい言い回しの点検 | 投資家向けピッチなど、利用者の場面に無い型 |
| academic-pptx-skill（学術発表） | 図は1つ、注目点の書き込み、出典、結論のまま質疑 | 学会固有の引用形式（予備R1を使うときに再検討） |
| コンサル向けスキル（ピラミッド・アクションタイトル） | 横の論理・縦の論理の点検 | 戦略コンサルの市場分析フレーム（利用者の場面では使わない） |
| 国内の Claude スライド作成スキル・生成AI資料作成ガイド | 工程を分けて人が確認する、役割・目的・対象者・枚数の指定 | 自社フォーマットへの自動流し込み（会社のテンプレートが必要） |
| Claude for PowerPoint（2026年2月公開、Max・Team・Enterprise向け） | 骨子の後の工程として、会社テンプレートへの流し込みに使う | — |
| Anthropic のスキル作成の作法 | 説明文に使う場面と使わない場面を書く、本体は短く詳細は参照ファイルへ、見本を付ける、試験ケースで確かめる | — |

## 6. 出典

- Barbara Minto, The Pyramid Principle — https://www.powerusersoftwares.com/post/give-a-brilliant-structure-to-your-presentations-with-the-pyramid-principle
- Pyramid Principle / ghost deck — https://deckary.com/blog/pyramid-principle-consulting
- Michael Alley, Assertion-Evidence — https://writing.engr.psu.edu/research.html
- Assertion-Evidence の効果研究（ASEE） — https://peer.asee.org/assertion-evidence-slides-appear-to-lead-to-better-comprehension-and-recall-of-more-complex-concepts.pdf
- 進捗報告の信号表示 — https://deckary.com/blog/project-status-slide
- PoCの進め方と評価基準 — https://www.nri.com/jp/media/column/scs_blog/20221212_1.html
- 展示会報告書の書き方 — https://biz.moneyforward.com/work-efficiency/basic/22625/
- トヨタのA3報告書 — https://resources.rework.com/ja/libraries/process-management/a3-problem-solving
- QCストーリー — https://www.kaonavi.jp/dictionary/qc_mokuhyosettei/
- 稟議書の記載項目 — https://biz.moneyforward.com/accounting/basic/78232/
- 空・雨・傘、So What／Why So — https://president.jp/articles/-/16678
- デジタルガバナンス・コード3.0 — https://www.kaiketsu-j.com/environment/12286
- presentation-writing-claude-skill — https://github.com/marcusnelson/presentation-writing-claude-skill
- academic-pptx-skill — https://github.com/Gabberflast/academic-pptx-skill
- 横の論理・縦の論理 — https://deckary.com/blog/consulting-quality-slides
- Nancy Duarte『Resonate』— https://www.duarte.com/blog/ultimate-guide-to-contrast/
- Amazon の6ページメモ — https://managementconsulted.com/amazon-memo/
- Claude でのスライド作成（国内）— https://ai-keiei.shift-ai.co.jp/claude-slide-creation/
- Claude for PowerPoint — https://www.prezent.ai/blog/claude-for-powerpoint
- スキル作成の作法 — https://www.beri.net/learning/claude-docs-skill-authoring-best-practices
- Skills と Projects の違い — https://claude.com/blog/skills-explained
