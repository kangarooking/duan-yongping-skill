# Duan Yongping Skill

A ready-to-use AI skill toolkit — distilling the business logic and investment methods from Duan Yongping's Investment Q&A Collection into 15 modular judgment tools that can be triggered individually or composed together.

This is not a book summary page. The book is the source of these skills, not the main character of this page.

## What Problems Do These Skills Solve

- Wanting to judge whether a company is worth investing in, but not knowing where to start
- Unable to distinguish between "a good business model" and "a good product"
- Unsure whether you are "doing the right things" or just "doing things right"
- Wanting to build your own Stop Doing List, but not knowing what to exclude
- Hesitating between concentration vs. diversification, holding vs. selling

## What Was Distilled

15 triple-verified skills extracted from *Duan Yongping Investment Q&A Collection* (Business Logic + Investment Logic), divided into two parts:

### Business Logic (7 Skills)

- **Foundational Philosophy**: `right-things-first` (Do the Right Things — Binary Decision), `stop-doing-list` (Stop Doing List Construction Method)
- **Investment Framework**: `right-business-people-price` (Investment Trinity: B>P>P), `business-model-evaluator` (Business Model Evaluation), `culture-judger` (Corporate Culture Judgment)
- **Competitive Strategy**: `dare-to-follow` (Dare to Follow, Not Lead), `profit-above-pursuit` (Pursuit Beyond Profit)

### Investment Logic (8 Skills)

- **Investment Philosophy**: `ownership-mindset` (Buying Stocks Means Buying the Company), `stop-doing-list` (Elimination-Based Investment Discipline)
- **Analysis Methods**: `capability-circle` (Circle of Competence Decision-Making), `good-business` (Good Business Identification), `dcf-valuation` (DCF Thinking-Based Valuation)
- **Decision Framework**: `opportunity-cost` (Opportunity Cost Decision-Making), `concentrated-investing` (Concentrated Investing)
- **Psychological Management**: `equanimity-mindset` (Equanimity in Investing)

## Effect Examples

### Example 1: Should You Invest in a Company?

**User Question**

> "There's a company with a great product and fast user growth, but it's not profitable yet. Is it worth investing in?"

**Skill Judgment**

- First trigger `right-things-first` to confirm whether you are doing the right things or just doing things right
- Call `right-business-people-price` to break it down by the B>P>P trinity
- Use `business-model-evaluator` to deeply examine the business model: Is there differentiation? Is there a moat? Is there pricing power?
- Supplement with `ownership-mindset`: If you were the sole owner of this company, how would you think about it?

**Response Example**

> Don't look at user growth and profitability first — ask a more fundamental question: Where is the differentiation in this business? If the product is good but lacks differentiation, and users are coming because of subsidies or a trend, the faster it grows, the harder it will fall. Then examine the business model: What prevents competitors from copying it? Where does pricing power come from? If these two questions can't be answered clearly, no matter how good the product is, it's not a good business. Finally, adopt the owner's perspective: If you were to buy this company outright and rely on its future cash flows to recoup your investment, how much would you pay? If the answer depends on "continued fundraising" or "being acquired," it's not an investment target — it's a bet.

### Example 2: Should You Stop-Loss and Sell?

**User Question**

> "A stock I bought has dropped 30%. Should I cut my losses?"

**Skill Judgment**

- Trigger `opportunity-cost` to unify buying, selling, and holding criteria under an opportunity cost framework
- Call `equanimity-mindset` to check whether the decision is emotionally driven
- Supplement with `capability-circle` to confirm whether the original purchase was truly within your circle of competence

**Response Example**

> The question about stop-loss isn't "how much has it dropped" — it's "if you had cash in hand right now, would you still buy this stock?" If yes, a 30% drop is actually a better opportunity. If no, then the original reason for buying has already changed, and it has nothing to do with how much you've lost. Most stop-loss decisions are emotionally driven: the discomfort of unrealized losses makes you want to "end the pain." But the only standard for investment decisions is opportunity cost: where does your money earn the highest return. Set aside the purchase price and look only at current value.

## How These Skills Were Generated

These skills were generated using the **cangjie-skill** RIA-TV++ pipeline, which consists of six stages:

1. **Whole-Book Understanding (Adler Analysis)** — Apply Mortimer Adler's analytical reading method: structure, interpretation, critique, and application. Produces `BOOK_OVERVIEW.md`
2. **Parallel Extraction** — Deploy 5 specialized extractors simultaneously (frameworks, principles, cases, counterexamples, terminology) to extract candidate methodology units from the text
3. **Triple-Verification Screening** — Each candidate must pass three checks: at least 2 independent supporting references in the book (cross-domain), ability to answer unstated new questions (predictive power), and non-obviousness (uniqueness)
4. **RIA++ Construction** — Structure verified content across six dimensions: R (Original Quote) / I (Rewrite in Own Words) / A1 (Book Case) / A2 (Future Trigger Scenario) / E (Executable Steps) / B (Boundaries & Blind Spots)
5. **Zettelkasten Linking** — Identify dependency, contrast, and composition relationships between skills. Generate `INDEX.md` and reference graph
6. **Stress Testing** — Design test cases including decoy questions for each skill. Failed skills are sent back for rework

## Generated by Cangjie Skill

This repository was generated by [cangjie-skill](https://github.com/kangarooking/cangjie-skill) — an open-source toolchain that distills books into executable AI skills.

cangjie-skill is based on the RIA-TV++ methodology, extracting methodologies, frameworks, and principles from books into atomic skills that can be directly invoked by AI agents in real-world scenarios.

## Repository Structure

```text
duan-yongping-skill/
├── README.md              ← You are here (Chinese)
├── README.en.md           ← English version
├── README.ja.md           ← Japanese version
├── LICENSE                ← MIT
├── business-logic/        ← Business Logic section
│   ├── BOOK_OVERVIEW.md
│   ├── INDEX.md
│   ├── candidates/
│   ├── rejected/
│   ├── verified.md
│   └── */SKILL.md         ← 7 skills
└── investment-logic/      ← Investment Logic section
    ├── BOOK_OVERVIEW.md
    ├── INDEX.md
    ├── candidates/
    ├── rejected/
    ├── verified.md
    └── */SKILL.md         ← 8 skills
```

## How to Use

1. Browse `business-logic/INDEX.md` and `investment-logic/INDEX.md` respectively for the skill landscape
2. Find the `*/SKILL.md` relevant to your current problem and use the trigger conditions and execution steps directly
3. Integrate skills into your agent framework, or use the prompts as standalone tools

## Source

- Books: *Duan Yongping Investment Q&A — Volume 1 (Business Logic)* + *Volume 2 (Investment Logic)* (段永平投资问答录)
- Author: Duan Yongping (compiled by Xueqiu user @Zliya)

## More Skills

- [Buffett Letters Skill](https://github.com/kangarooking/buffett-letters-skill) — 20 investment judgment skills from Buffett's 60+ years of shareholder letters
- [Poor Charlie's Almanack Skill](https://github.com/kangarooking/poor-charlies-almanack-skill) — 12 decision and judgment skills from Charlie Munger's core thinking methods
- [No Rules Rules Skill](https://github.com/kangarooking/no-rules-rules-skill) — 10 organizational design skills from Netflix's freedom and responsibility culture
- [Cognitive Dividend Skill](https://github.com/kangarooking/cognitive-dividend-skill) — 15 cognitive tool skills for thinking upgrades from *Cognitive Dividend*

## About the Author

**kangarooking** — AI blogger, indie developer. Creator of AI Top WeChat Official Account「袋鼠帝 AI 客栈」

Volcengine Navigation KOL, Baidu Qianfan Developer Ambassador, GLM Evangelist, Trae Kunming's First Fellow

| Platform | Link |
|----------|------|
| 𝕏 Twitter | https://x.com/aikangarooking |
| Xiaohongshu | https://xhslink.com/m/5YejKvIDBbL |
| Douyin | https://v.douyin.com/hYpsjphuuKc |
| WeChat Official Account | 袋鼠帝 AI 客栈 |
| WeChat Video Channel | AI 袋鼠帝 |

WeChat Official Account「袋鼠帝 AI 客栈」QR code:

![](https://raw.githubusercontent.com/kangarooking/cangjie-skill/main/assets/kangarooking-gzh.jpg)

## License

MIT. See [LICENSE](./LICENSE).
