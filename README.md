# Design_Research

`Design_Research` is a skill for competitor design research around specific app or web product features.

It focuses on collecting concrete evidence instead of broad market analysis:

- interface screenshots
- walkthrough videos
- page-level UI evidence
- feature-specific competitor references

## Installation

Copy this skill into your Codex skills directory:

```bash
mkdir -p ~/.codex/skills/Design_Research
cp SKILL.md ~/.codex/skills/Design_Research/SKILL.md
mkdir -p ~/.codex/skills/Design_Research/agents
cp agents/openai.yaml ~/.codex/skills/Design_Research/agents/openai.yaml
```

## Usage

Typical prompts:

```text
Use $Design_Research to find competitor UI for Shopee Express delivery notification in Southeast Asia.
```

```text
Use $Design_Research to find screenshots and usage videos for trunk logistics task homepages in China.
```

```text
Use $Design_Research to research competitor job-list homepages for third-party workers in Southeast Asia.
```

## Output Format

| Competitor | 应用商店相关 | 视频或者直接使用视角 | 其他相关截图等 |
|---|---|---|---|

For videos and screenshots, prefer high-signal evidence and leave cells empty when useful results are not available.
