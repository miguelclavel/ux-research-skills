# UX research skills

Eighteen Claude Code skills for UX research, one per job: from planning a study and writing a screener to personas, journey maps, usability test analysis, AI browser walkthroughs and synthetic users. Each one tells Claude exactly how the job is done well, and what not to do.

By [Miguel Clavel](https://github.com/miguelclavel), Senior Product Designer. Sister repo to [claude-skills-for-designers](https://github.com/miguelclavel/claude-skills-for-designers).

**Looking for a skill? [See all 28 by job](https://github.com/miguelclavel/claude-skills-for-designers/blob/main/SKILLS.md)**, these eighteen and the ten design skills together.

## Plan

| Skill | What it does |
| --- | --- |
| [research-plan](skills/research-plan/SKILL.md) | Starts from the decision, then picks questions, method, participants, ethics and timeline |
| [screener-survey](skills/screener-survey/SKILL.md) | Recruits by behaviour with disguised questions, quotas and accessibility needs |
| [stakeholder-interviews](skills/stakeholder-interviews/SKILL.md) | Surfaces goals, constraints and an assumptions map before design starts |

## Discover

| Skill | What it does |
| --- | --- |
| [interview-guide](skills/interview-guide/SKILL.md) | Questions about real past behaviour, with probes, timings and no leading |
| [diary-study](skills/diary-study/SKILL.md) | Captures behaviour over days or weeks, in context |
| [jobs-to-be-done](skills/jobs-to-be-done/SKILL.md) | Job statements and the four forces that push and hold people |
| [user-personas](skills/user-personas/SKILL.md) | Personas built from evidence, each claim traced to a source, with a confidence level |
| [journey-map](skills/journey-map/SKILL.md) | A current state journey with evidence for every pain point |
| [competitive-analysis](skills/competitive-analysis/SKILL.md) | Conventions, differentiators and gaps across products, for one flow |

## Evaluate

| Skill | What it does |
| --- | --- |
| [usability-test-plan](skills/usability-test-plan/SKILL.md) | Realistic task scenarios, success criteria, metrics and a neutral script |
| [usability-test-analysis](skills/usability-test-analysis/SKILL.md) | Severity ranked findings with how many people hit each one, and fixes |
| [ai-browser-walkthrough](skills/ai-browser-walkthrough/SKILL.md) | An AI agent tries your flow in a real browser, keyboard only and on a phone size, before you test with people |
| [synthetic-users](skills/synthetic-users/SKILL.md) | AI simulated users to sharpen questions and anticipate objections, always labelled "not evidence" |
| [card-sort-tree-test](skills/card-sort-tree-test/SKILL.md) | Plan and analyse card sorts and tree tests for navigation |
| [accessibility-research](skills/accessibility-research/SKILL.md) | Research with disabled people and assistive technology users, with proper accommodations |

## Measure

| Skill | What it does |
| --- | --- |
| [survey-design](skills/survey-design/SKILL.md) | Neutral questions, sensible length, honest sampling and an analysis plan |
| [analytics-insights](skills/analytics-insights/SKILL.md) | Funnels, heatmaps and recordings turned into testable hypotheses |

## Share

| Skill | What it does |
| --- | --- |
| [research-readout](skills/research-readout/SKILL.md) | Insights with evidence counts, confidence and recommendations that change decisions |

For turning notes into themes, use [research-synthesis](https://github.com/miguelclavel/claude-skills-for-designers/tree/main/skills/research-synthesis) in the sister repo.

## Install

As a Claude Code plugin, all eighteen at once. In Claude Code, run:

```
/plugin marketplace add miguelclavel/claude-skills-for-designers
/plugin install ux-research-skills@miguelclavel
```

That marketplace also has the ten [design skills](https://github.com/miguelclavel/claude-skills-for-designers). Or copy only the skills you want:

```bash
git clone https://github.com/miguelclavel/ux-research-skills
cp -R ux-research-skills/skills/usability-test-plan ~/.claude/skills/
```

Copy into `~/.claude/skills/` to use everywhere, or `.claude/skills/` in one project. Claude picks a skill up when your request matches its description.

## The rules every skill follows

1. **Start from the decision.** Research that can't change anything isn't worth running.
2. **Evidence, counted.** "4 of 6 participants", quotes with participant ids, data with its caveats.
3. **Say how sure you are.** Strong, moderate or early signal; patterns from eight interviews, not percentages.
4. **AI assists, people decide.** AI walkthroughs and synthetic users are labelled and never reported as user research.
5. **Privacy and consent first.** Plain language consent, only the data you need, names replaced with ids.
6. **Include people with disabilities,** with real accommodations, not simulations.

---

MIT licensed. Made by [Miguel Clavel](https://miguelclavel.com/?utm_source=github&utm_medium=ux-research-skills) with Claude Code.
