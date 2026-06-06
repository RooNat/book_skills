# book_skills

这个仓库用于存放从书籍中蒸馏出来的 Codex/Claude skills。每本书占用一个独立目录, 目录内包含可直接安装的 skills、测试 prompt、压力测试结果和拆书审计轨迹。

## Books

| Book | Directory | Skills | Status |
|---|---|---:|---|
| 《做对产品》 Alberto Savoia / 阿尔贝托·索维亚 | [`zuo-dui-chan-pin/`](./zuo-dui-chan-pin/) | 12 | Ready |

## Install A Book's Skills

安装某一本书的全部 skills:

```bash
git clone https://github.com/RooNat/book_skills.git
cd book_skills
cp -R zuo-dui-chan-pin/{adjust-before-pivot,escape-thoughtland,hypozoom-to-xyz,market-engagement-hypothesis,market-failure-prior,minimize-data-distance-hours-dollars,pretotype-technique-selection,pretotype-yoda,right-it-diagnosis,skin-in-game-caliper,tri-meter,xyz-hypothesis} ~/.codex/skills/
```

安装后重启 Codex, 新 skills 才会被自动发现。

## Repository Layout

```text
book-slug/
├── README.md                  # Book-specific install and usage guide
├── INDEX.md                   # Skill index, dependency graph, learning order
├── BOOK_OVERVIEW.md           # Stage 0 whole-book understanding
├── verified.md                # Stage 1.5 verified methodology units
├── candidates/                # Stage 1 raw candidate pool
├── rejected/                  # Stage 1.5 rejected/downgraded units
└── <skill-slug>/
    ├── SKILL.md               # Installable skill
    ├── test-prompts.json      # Darwin-compatible trigger tests
    └── test-results.md        # Stage 4 pressure test results
```

## Quality Bar

Each published skill directory should include:

- `SKILL.md` with complete `R / I / A1 / A2 / E / B` sections
- `test-prompts.json` with `should_trigger`, `should_not_trigger`, and `edge_case` cases
- `test-results.md` recording the trigger pressure-test result
- Clear `related_skills` links in frontmatter when relationships exist

## Darwin-Skill

The included `test-prompts.json` files are intended to be darwin-skill compatible. After installing or modifying a book's skills, you can evolve them with:

```bash
darwin evolve <book-directory>/
```
