# 参照ソース一覧：Storey「技術的負債から認知的負債・意図負債へ」レビュー

- 作成日：2026-11-06
- 対象：前回レビュー作成時に参照・検索・読解したソース
- 注意：URLは検索結果、アップロードPDF内の参考文献リスト、または各論文のarXiv番号に基づく。二次情報（ブログ・ニュース）は一次資料の代替ではないため、引用時は一次資料を確認すること。

---

## 表A：回答中で直接に引用・言及したもの

| No. | 文献／ソース | 種別 | URL・識別子 | 回答での使われ方 |
|---|---|---|---|---|
| A1 | Storey, M.-A. (2026). From Technical Debt to Cognitive and Intent Debt: Rethinking Software Health in the Age of AI. ACM Queue | 本論文（ポジション・ペーパー） | https://queue.acm.org/detail.cfm?id=3807966 | レビュー対象。トリプル負債モデルの要旨・文献分析 |
| A2 | 同上（arXivプレプリント、2026-03-23投稿、v4まで改訂） | プレプリント | https://arxiv.org/abs/2603.22106 | 刊行経緯の確認 |
| A3 | Kosmyna, N. et al. (2025). Your Brain on ChatGPT: Accumulation of Cognitive Debt when Using an AI Assistant for Essay Writing Task | 実験研究（EEG、54名） | https://arxiv.org/abs/2506.08872 ／ https://www.media.mit.edu/publications/your-brain-on-chatgpt/ | 個人レベルの「認知的負債」概念との区別 |
| A4 | Shen, J. H. & Tamkin, A. (2026). How AI Impacts Skill Formation（Anthropic） | RCT（52名） | https://arxiv.org/abs/2601.20245 | 習熟度17%低下、使い方による分断 |
| A5 | Anthropic (2026-01-29). How AI assistance impacts the formation of coding skills | 企業研究ブログ | https://www.anthropic.com/research/AI-assistance-coding-skills | A4の補足（相互作用パターン別スコア） |
| A6 | InfoQ (2026-02). Anthropic Study: AI Coding Assistance Reduces Developer Skill Mastery by 17% | ニュース記事 | https://infoq.com/news/2026/02/ai-coding-skill-formation/ | A4の限界（直後測定のみ等）の確認 |
| A7 | Becker, J., Rush, N., Barnes, E., Rein, D. (2025). Measuring the Impact of Early-2025 AI on Experienced Open-Source Developer Productivity（METR） | RCT（16名・246タスク） | arXiv:2507.09089 | 19%の遅延と自己評価（20%高速化）のギャップ |
| A8 | Willison, S. (2025-07-12). METRの研究に関するブログ解説 | ブログ | https://simonwillison.net/2025/Jul/12/ai-open-source-productivity/ | METR研究の詳細（暗黙知・文脈の欠如） |
| A9 | diginomica (2025-07-15). AI tools slow down experienced developers by 19% | ニュース記事 | https://diginomica.com/node/29061 | METR研究の設計と限界の確認 |
| A10 | Becker et al. (2026). We are changing our developer productivity experiment design（METR） | 研究機関ブログ | https://metr.org/blog/2026-02-24-uplift-update/ | 後継研究の設計変更（Balepurらの文献リスト経由で確認） |
| A11 | Vibehackers (2026). Anthropic Quietly Showed Their Own Tool Drops Dev Skill 17%（DEV Community） | ブログ | https://dev.to/vibehackers/anthropic-quietly-showed-their-own-tool-drops-dev-skill-17-450i | METR後継研究が参加者の非AIタスク拒否で難航したとの記述（二次情報・要一次確認） |
| A12 | Balepur, N. et al. (2026). (Im)Paired Programming: Coding Agents Improve Productivity but Harm Understanding | ユーザー研究（54名） | https://arxiv.org/pdf/2607.26375 | エージェントによる理解低下、低労力インタラクションとの関連 |
| A13 | GitClear (2025). AI Copilot Code Quality 2025 | ベンダー調査（2.11億行） | https://www.gitclear.com/ai_assistant_code_quality_2025_research | 技術的負債の楽観論への反証データ |
| A14 | Vibe Graveyard. GitClear study finds AI coding assistants are pushing codebases toward copy-paste debt | 二次解説 | https://vibegraveyard.ai/story/gitclear-ai-copilot-code-quality-study/ | 移動行24.8%→9.5%、コピペ行8.4%→12.3%の数値、ベンダー報告への注意 |
| A15 | DORA / Google Cloud (2025). State of AI-assisted Software Development（InfoQ報道） | 大規模サーベイ（約5,000名） | https://www.infoq.com/news/2025/09/dora-state-of-ai-in-dev-2025 | 「AIは増幅器」、不安定性の継続 |
| A16 | IT Revolution (2025-09-25). AI's Mirror Effect: How the 2025 DORA Report Reveals Your Organization's True Capabilities | 解説記事 | https://itrevolution.com/?p=78991 | スループットとの正の相関と不安定性の併存 |
| A17 | He, H. et al. (2026). AI Writes Faster Than Humans Can Review: A Longitudinal Study of an Enterprise 2x Mandate | 縦断的ケーススタディ | https://arxiv.org/abs/2607.01904 | 人間レビュー率68%への低下、レビューのボトルネック化 |
| A18 | Emergent Mind. 上記A17の要約ページ | 要約サイト | https://www.emergentmind.com/papers/2607.01904 | A17の図表要点の確認 |
| A19 | The Nature of Technical Debt in Research Software（2026） | 実証研究 | https://arxiv.org/pdf/2603.20415 | 認知的負債とNaur理論、LLMによる負のスパイラル |
| A20 | Faster Code, Deeper Debt? A Multivocal Literature Review on Technical Debt and Its Early Signs in LLM-Assisted Software Development（2026） | 多声的文献レビュー | https://arxiv.org/pdf/2606.14796 | Storeyを引用している後続研究の例 |
| A21 | Atono. Intent Debt: the category has a name now | 実務者ブログ | https://atono.substack.com/p/intent-debt-the-category-has-a-name | 実務界の反響 |
| A22 | Kanat-Alexander, M. LinkedIn投稿（Cognitive Tours予告、Queue掲載の経緯） | SNS投稿 | https://linkedin.com/in/mkanat | Cognitive Tours、掲載の速さ |
| A23 | Tech Lead Journal #264. From Technical Debt to Triple Debt（Storeyインタビュー） | ポッドキャスト | https://techleadjournal.dev/episodes/264/ | Cognitive Toursの紹介、Queue論文リンクの確認 |
| A24 | Naur, P. (1985). Programming as theory building | 古典論文 | https://www.sciencedirect.com/science/article/abs/pii/0165607485900328 | 「システムの理論」の理論的基盤 |
| A25 | Hutchins, E. (1995). Cognition in the Wild. MIT Press | 書籍 | ISBN等は書誌参照 | 分散認知 |
| A26 | Wegner, D. M. (1987). Transactive memory: a contemporary analysis of the group mind | 書籍所収論文 | In Theories of Group Behavior, Springer, pp.185–208 | トランザクティブ・メモリ |
| A27 | Starr, A. & Storey, M.-A. (2026). Theory of troubleshooting: the developer's cognitive experience of overcoming confusion. ACM TOSEM | 論文（著者自身の共著） | https://dl.acm.org/doi/abs/10.1145/3800945 | 診断兆候の主要根拠（著者自己引用への注意） |
| A28 | Shaw, S. D. & Nave, G. (2026). Thinking—fast, slow, and artificial: ... cognitive surrender. SSRN | ワーキングペーパー | https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6097646 | 認知的降伏概念（一般的推論の研究） |
| A29 | Willison, S. (2026). Cognitive debt | ブログ | https://simonwillison.net/2026/Feb/15/cognitive-debt/ | 本論文が参照する実務者の議論 |
| A30 | Curtis, B., Krasner, H., Iscoe, N. (1988). A field study of the software design process for large systems. CACM | 古典論文 | https://dl.acm.org/doi/10.1145/50087.50089 | 古典的理論群の例 |
| A31 | von Mayrhauser, A. & Vans, A. M. (1995). Program comprehension during software maintenance and evolution. Computer | 古典論文 | https://dl.acm.org/doi/10.1109/2.402076 | 古典的理論群の例 |
| A32 | Clark, H. H. & Brennan, S. E. (1991). Grounding in communication | 書籍所収論文 | In Perspectives on Socially Shared Cognition, APA | 古典的理論群の例 |
| A33 | McLuhan, M. & McLuhan, E. (1988). Laws of Media: The New Science | 書籍 | University of Toronto Press | 古典的理論群の例（「回復」概念） |
| A34 | Cunningham, W. (1993). The WyCash portfolio management system | 原典 | https://dl.acm.org/doi/10.1145/157710.157715 | 技術的負債の正典 |
| A35 | Fowler, M. (2003). Technical debt | ブログ | martinfowler.com/bliki/TechnicalDebt.html | 技術的負債の正典 |
| A36 | Kruchten, P., Nord, R. L., Ozkaya, I. (2012). Technical debt: From metaphor to theory and practice. IEEE Software | 論文 | https://ieeexplore.ieee.org/document/6336722 | 技術的負債の正典 |
| A37 | Beck, K. (1999). Extreme Programming Explained | 書籍 | Addison-Wesley | 技術的負債の正典群（比較の基準点） |
| A38 | Evans, E. (2003). Domain-Driven Design | 書籍 | Addison-Wesley | 同上（意図の明示化手法として本論文が引用） |
| A39 | Nygard, M. (2011). Documenting architecture decisions | ブログ | https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions | 同上（ADR） |

> 補足：回答中で言及した「設計根拠（design rationale）研究」（IBIS、QOC等）、「要求トレーサビリティ研究」、「自己申告型技術的負債（SATD）研究」は、分野名としての言及であり、特定のソースは参照していない。

---

## 表B：間接的な主題性の関連が強く示唆されるソース

| No. | 文献／ソース | 種別 | URL・識別子 | 関連性 |
|---|---|---|---|---|
| B1 | Larridin. AI vs human developer productivity | 解説記事 | https://larridin.com/blog/ai-vs-human-developer-productivity | GoogleのRCT（96名、約21%短縮）とMETRの結果の相違の整理 |
| B2 | Intuition to Evidence: Measuring AI's True Impact on Developer Productivity（DeputyDev、300名、1年） | 企業縦断研究 | https://arxiv.org/abs/2509.19708 | 企業規模のAI導入効果（PRレビューサイクル31.8%短縮） |
| B3 | Debt Behind the AI Boom: A Large-Scale Empirical Study of AI-Generated Code in the Wild | 実証研究 | arXiv:2603.28592 | 実運用リポジトリにおけるAI生成コードの負債 |
| B4 | Beyond the 'Diff': Addressing Agentic Entropy in Agentic Software Development | 論文 | https://arxiv.org/pdf/2604.16323 | エージェント開発における理解・エントロピー問題 |
| B5 | Verdent. What Is Comprehension Debt in AI-Generated Code? | ベンダーブログ | https://www.verdent.ai/guides/answers/comprehension-debt-ai-generated-code | 近縁概念「comprehension debt」の説明（ベンダー記事） |
| B6 | Osmani, A. Comprehension debt | ブログ | https://addyosmani.com/blog/comprehension-debt/ | 近縁概念（DEV Community記事経由で確認、未読） |
| B7 | Moksh. Cognitive Debt: The Hidden Cost of Letting AI Write Your Code（DEV Community） | ブログ | https://dev.to/moksh/cognitive-debt-the-hidden-cost-of-letting-ai-write-your-code-5d5c | 関連研究（Explanation Gate等）の紹介（二次情報） |
| B8 | LeadDev. Code maintainability plummets in the AI coding era | 業界メディア | https://leaddev.com/ai/code-maintainability-plummets-in-the-ai-coding-era | GitClear 2026年版の報告に言及 |
| B9 | LeadDev. How AI-generated code accelerates technical debt | 業界メディア | https://leaddev.com/software-quality/how-ai-generated-code-accelerates-technical-debt | AI生成コードと技術的負債 |
| B10 | DevClass (2025-02-20). AI is eroding code quality, states new in-depth report | ニュース記事 | https://devclass.com/2025/02/20/ai-is-eroding-code-quality-states-new-in-depth-report/ | GitClear報告とDORA 2024の食い違い |
| B11 | Thoughtworks Technology Radar. Complacency with AI-generated code | 技術動向レポート | https://www.thoughtworks.com/en-in/radar/techniques/complacency-with-ai-generated-code | 実務界での警戒論 |
| B12 | TechTarget. Google DORA: Software delivery caught up to AI coding tools | ニュース記事 | https://www.techtarget.com/it-infrastructure/news/366631712/Google-DORA-Software-delivery-caught-up-to-AI-coding-tools | DORA 2025の補足 |
| B13 | InfoQ (2026-03). AI Is Amplifying Software Engineering Performance, Says the 2025 DORA Report | ニュース記事 | https://infoq.com/news/2026/03/ai-dora-report/ | DORA AI Capabilities Model |
| B14 | Faros系ブログ. AI Writes Most of Your Code Now. That's the Problem. | ブログ | https://goncalovelosa.github.io/blog/acceleration-whiplash | レビュー時間増加のテレメトリ（二次情報・数値は要一次確認） |
| B15 | SoftwareSeni. The Case Against Vibe Coding | ブログ | https://www.softwareseni.com/the-case-against-vibe-coding-understanding-craftsmanship-and-long-term-costs | 理解負債・保守負担の議論（二次情報） |
| B16 | Steady. Triple Debt Modelの解説記事 | 解説記事 | https://steady.page/de/software-insights/posts/8edd536b-499a-4e31-808a-28724c2c5e67 | 三層の分離（decoupling）の解釈 |
| B17 | Liu, G. et al. (2026). AI assistance reduces persistence and hurts independent performance | 論文 | arXiv:2604.04721 | AI依存と独立遂行能力（Balepur文献リスト経由） |
| B18 | Cui, K. Z. et al. (2026). The effects of generative AI on high-skilled work: three field experiments with software developers. Management Science | フィールド実験 | Balepur文献リスト経由 | 生産性向上側のエビデンス |
| B19 | Huang, H. et al. (2026). More code, less reuse: code quality and reviewer sentiment towards AI-generated pull requests | 実証研究 | arXiv:2601.21276 | コード再利用低下（GitClearと整合） |
| B20 | Fransoo et al. (2025). AI-assisted Programming May Decrease the Productivity of Experienced Developers by Increasing Maintenance Burden | 論文 | arXiv:2510.10165 | 保守負担の増大（He et al.文献リスト経由） |
| B21 | Zindulka, T. et al. (2026). The AI memory gap: Users misremember what they created with AI or without. CHI '26 | 論文 | Balepur文献リスト経由 | AI使用時の記憶の誤り |
| B22 | Peng, S. et al. (2023). The impact of AI on developer productivity: evidence from GitHub Copilot | 論文 | https://arxiv.org/abs/2302.06590 | 生産性向上の古典的エビデンス（本論文の参考文献24） |
| B23 | Hou, X. et al. (2024). Large language models for software engineering: a systematic literature review. ACM TOSEM | 文献レビュー | https://dl.acm.org/doi/10.1145/3695988 | AIによるリファクタリング等への期待の根拠（本論文の参考文献14） |
| B24 | Borg, M. et al. (2026). Code for machines, not just humans: quantifying AI-friendliness with code health metrics | 論文 | https://arxiv.org/abs/2601.02200 | AIエージェントと低品質コード（本論文の参考文献4） |

---

## 表C：その他（本論文の参考文献のうち回答で個別に扱わなかったもの、および関連の薄い検索ヒット）

| No. | 文献／ソース | 種別 | URL・識別子 | 備考 |
|---|---|---|---|---|
| C1 | Kahneman, D. (2011). Thinking, Fast and Slow | 書籍 | Farrar, Straus and Giroux | 認知的降伏の理論的背景（本論文参考文献16） |
| C2 | Tornhill, A. (2015). Your Code as a Crime Scene | 書籍 | Pragmatic Programmers | バスファクターの根拠（参考文献28） |
| C3 | Tornhill, A. (2025). Skills rot at machine speed? Forbes | 寄稿記事 | https://www.forbes.com/councils/forbestechcouncil/2025/04/28/skills-rot-at-machine-speed-ai-is-changing-how-developers-learn-and-think/ | 参考文献29 |
| C4 | Wynne, M., Hellesøy, A., Tooke, S. (2017). The Cucumber Book | 書籍 | Pragmatic Bookshelf | BDD（参考文献34） |
| C5 | Herbsleb, J. D. (2007). Global software engineering: the future of socio-technical coordination | 論文 | https://dl.acm.org/doi/10.1109/FOSE.2007.11 | 参考文献11 |
| C6 | Hermans, F. (2021). The Programmer's Brain | 書籍 | Manning | 参考文献12 |
| C7 | Garg, R. (2026). Patterns for reducing friction in AI-assisted development | ブログ | https://martinfowler.com/articles/reduce-friction-ai/ | 参考文献10 |
| C8 | Böckeler, B. (2026). Context engineering | ブログ | https://martinfowler.com/articles/exploring-gen-ai/context-engineering-coding-agents.html | 参考文献3 |
| C9 | Zhang, D. et al. Cloud Intelligence/AIOps 2.0: Knowledge-Anchored Agentic AIOps | ワークショップ論文 | ACM FSE 2026 DISE | 参考文献35 |
| C10 | Ulloa, M. et al. (2026). Product manager practices for delegating work to generative AI | 論文 | arXiv:2510.02504 | 参考文献30 |
| C11 | Miller, C. et al. (2026). "Maybe we need some more examples:" individual and team drivers of developer GenAI tool use | 論文 | arXiv:2507.21280 | 参考文献21 |
| C12 | Petre, M. & Shaw, M. (2025). Contrasting to spark creativity in software development teams | 論文 | https://doi.org/10.1109/MS.2025.3538670 | 参考文献25 |
| C13 | Hicks, C. M. et al. (2024). The new developer: AI skill threat, identity change & developer thriving | プレプリント | https://osf.io/preprints/psyarxiv/2gej5_v2 | 参考文献13 |
| C14 | Alakmeh, T. et al. (2026). Grasping AI reliance in program comprehension and coding through the AIRELI persona taxonomy | 論文 | https://aireli.hasel.dev/download/aireli-preprint.pdf | 参考文献1 |
| C15 | Miles, R. (2026). On cognitive debt and the care of the habitat | ブログ | https://www.softwareenchiridion.com/p/on-cognitive-debt-and-the-care-of | 参考文献20 |
| C16 | Forsgren, N. et al. DevEx in Action | ACM Queue関連記事 | https://queue.acm.org/detail.cfm?id=3639443 | 本論文末尾の関連資料 |
| C17 | Allman, E. Managing Technical Debt | ACM Queue関連記事 | https://queue.acm.org/detail.cfm?id=2168798 | 同上 |
| C18 | Matsudaira, K. Working Models for Tackling Tech Debt | ACM Queue関連記事 | https://queue.acm.org/detail.cfm?id=3674114 | 同上 |
| C19 | Smallpdf (2026). AI-written documents at work（米国1,000名調査） | ベンダー調査 | https://smallpdf.com/blog/ai-written-documents-at-work | 検索ヒット。ソフトウェア開発に直接関係せず、回答では未使用 |

---

## 利用上の注意

1. 表Aの一部（A9、A11、A14、A16、A18、A21–A23）は二次情報であり、数値や主張を研究に用いる際は一次資料で確認すること。
2. 表Bの一部（B6、B14、B15）は本文を直接読んでおらず、検索結果の断片に基づく。
3. 検索結果に現れた日付・数値は、ソース側の記載を転記したものである。

