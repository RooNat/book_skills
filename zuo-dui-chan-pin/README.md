# 《做对产品》Skills

This directory contains 12 Codex/Claude skills distilled from 《做对产品》 by Alberto Savoia / 阿尔贝托·索维亚.

## One-Line Theme

在投入资源把产品构建正确之前, 先用可量化假说、预型试验和带切身利益的一手市场数据验证自己是否正在构建市场真正会响应的“正确的它”。

## Install

From the repository root:

```bash
cp -R zuo-dui-chan-pin/{adjust-before-pivot,escape-thoughtland,hypozoom-to-xyz,market-engagement-hypothesis,market-failure-prior,minimize-data-distance-hours-dollars,pretotype-technique-selection,pretotype-yoda,right-it-diagnosis,skin-in-game-caliper,tri-meter,xyz-hypothesis} ~/.codex/skills/
```

Restart Codex after installation.

## Skills

| Skill | When to use |
|---|---|
| [`market-failure-prior`](./market-failure-prior/SKILL.md) | Reset the default risk prior for a new product idea. |
| [`right-it-diagnosis`](./right-it-diagnosis/SKILL.md) | Diagnose whether failure is launch, operation, or premise failure. |
| [`escape-thoughtland`](./escape-thoughtland/SKILL.md) | Replace opinions, OPD, likes, and surveys with YODA-seeking behavior tests. |
| [`market-engagement-hypothesis`](./market-engagement-hypothesis/SKILL.md) | Define how the market is expected to engage with an idea. |
| [`xyz-hypothesis`](./xyz-hypothesis/SKILL.md) | Convert vague demand claims into "at least X% of Y will Z". |
| [`hypozoom-to-xyz`](./hypozoom-to-xyz/SKILL.md) | Shrink a broad XYZ into a small, local, testable xyz. |
| [`pretotype-yoda`](./pretotype-yoda/SKILL.md) | Design quick, cheap pretotypes that produce skin-in-the-game YODA. |
| [`pretotype-technique-selection`](./pretotype-technique-selection/SKILL.md) | Choose fake-door, Pinocchio, Mechanical Turk, infiltrator, relabel, video, or facade pretotypes. |
| [`minimize-data-distance-hours-dollars`](./minimize-data-distance-hours-dollars/SKILL.md) | Prioritize validation paths by DTD, HTD, and $TD. |
| [`skin-in-game-caliper`](./skin-in-game-caliper/SKILL.md) | Rank evidence by how much skin in the game users committed. |
| [`tri-meter`](./tri-meter/SKILL.md) | Combine multiple YODA arrows into a TRI decision. |
| [`adjust-before-pivot`](./adjust-before-pivot/SKILL.md) | Use weak or bad YODA to adjust, then flip, then abandon if needed. |

## Navigation

- [INDEX.md](./INDEX.md): skill groups, relationship graph, and recommended learning order
- [BOOK_OVERVIEW.md](./BOOK_OVERVIEW.md): whole-book understanding
- [verified.md](./verified.md): triple-verified methodology units
- [candidates/](./candidates/): raw extraction pool
- [rejected/](./rejected/): downgraded or merged candidates

## Test Coverage

Each skill includes:

- `SKILL.md`
- `test-prompts.json`
- `test-results.md`

Stage 4 pressure tests passed at 100% for all 12 skills.
