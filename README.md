# skill-AI
A collection of practical AI skills for clearer prompts and more reliable workflows.

# Giancarlo’s Prompt Engineering Skills

This repository brings together reusable instructions designed to improve how prompts are written and applied. Each skill has a focused purpose, a clear workflow, and a ready-to-use SKILL.md file.

## Naming convention

Skills I create end with -giancarlo, so they’re easy to identify and filter.

## Skills

### prompt-improver-giancarlo

Reviews and improves prompts while preserving their original purpose, constraints, and delegated choices. It focuses on changes that solve a concrete problem, avoids adding unsupported requirements, and returns a complete prompt ready to use.

Status: available

### prompt-improver-italiano-giancarlo

Same as prompt-improver-giancarlo but specific for Italian language.

### Other skill

Coming soon!

## Repository structure

.
├── prompt-improver-giancarlo/
│   └── SKILL.md
├── prompt-improver-italiano-giancarlo/
│   └── SKILL.md
└── coming-skill/
    └── SKILL.md

## Design principles

Follow https://platform.claude.com/docs/en/agents-and-tools/agent-skills/best-practices

## Use

Choose where to install a skill:

- **Global** — available across your projects on this computer.
- **Local** — available only in the project where you install it. Commit the skill folder to share it with others working on that project.

The commands below assume you are running them from the root of this repository. Replace `<skill-folder>` with a skill directory name, such as `prompt-improver-giancarlo`.

### Claude Code

**Global**

```bash
mkdir -p ~/.claude/skills
cp -R <skill-folder> ~/.claude/skills/
```

**Local**

```bash
mkdir -p .claude/skills
cp -R <skill-folder> .claude/skills/
```

### Codex

**Global**

```bash
mkdir -p ~/.agents/skills
cp -R <skill-folder> ~/.agents/skills/
```

**Local**

```bash
mkdir -p .agents/skills
cp -R <skill-folder> .agents/skills/
```

Each skill folder contains a SKILL.md file with the instructions and metadata Codex and Claude Code use to discover the skill.

## About this project

I’m building this collection to explore how well-designed instructions can make AI-assisted work more effective. The skills are developed as focused, reusable workflows and refined around clarity, usefulness, and respect for user intent.
