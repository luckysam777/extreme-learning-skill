# Extreme Learning Skill

An AI-powered deep learning method based on MIT pedagogy — master any domain from zero through thinking model extraction, controversy mapping, and stress testing.

## Description

Uses three core mechanisms — **thinking model construction**, **controversy collision**, and **extreme pressure testing** — to help users master the underlying logic and deep insights of any domain in minimal time.

## When To Use

- Rapidly learning a new field from scratch
- Analyzing textbooks, papers, lecture transcripts, or any professional materials
- Building systematic expert-level thinking frameworks
- High-intensity practice to verify true understanding
- Triggered by: extreme learning, deep mastery, rapid learning, MIT method, thinking model, knowledge map

## Workflow

### Phase 1: Knowledge Injection (Context Building)

- Ask user to upload core materials: textbooks, seminal papers, conference proceedings, transcribed lectures
- Preprocess and build a local knowledge base

### Phase 2: Thinking Pattern Extraction

Analyze materials and identify the 5 core thinking models or underlying logic that top experts agree on.

Output: A thinking framework diagram — helps users see problems through an expert's lens, not memorize definitions.

### Phase 3: Map of Controversy

Search for academic conflicts or industry debates within the materials.

Output: A knowledge domain map with three zones:

- **Consensus zone** — established knowledge
- **Controversy zone** — active debates with opposing arguments
- **Frontier zone** — open, unsolved questions

List 3 core debate points and拆解 the most representative arguments on each side.

### Phase 4: Stress Test & Iteration

Generate 10 high-discrimination questions (focus on logical application, not terminology).

Interactive flow:

1. Present the 10 questions
2. User answers them
3. Socratic follow-up on each answer:
   - "What logic did you miss?"
   - "Why doesn't this inference hold?"
   - "What would falsify your answer?"
4. Iterate until user can perfectly explain all 10 questions

## Agent Prompt Fragment

> "You are a stern and wise MIT mentor. Your goal is not to give direct answers. Instead, you will first use the materials I provide to extract expert thinking models and map core controversies in the field. Then you will relentlessly torment me with 10 extremely challenging questions until I truly master the underlying logic of this domain."

## Install

```bash
git clone https://github.com/luckysam777/extreme-learning-skill.git
cp -r extreme-learning-skill/extreme-learning ~/.claude/skills/
```

## Repository Structure

```
extreme-learning-skill/
  LICENSE
  README.md / README_zh.md
  extreme-learning/
    SKILL.md                    ← Main skill file (Claude Code compatible)
    platforms/
      claude-code/
        extreme-learning/
          SKILL.md
    references/
      methodology.md            ← Detailed methodology
```

## Why This Works

### Thinking Pattern Extraction

Traditional learning停留在"knowing what"层面. Experts differ because they possess **internalized thinking models**. Extracting 5 core models lets you stand on expert shoulders immediately.

### Map of Controversy

Every mature field has internal disputes. Understanding them isn't about picking sides — it's about knowing **where knowledge boundaries lie**: what's established, what's debated, what's open.

### Stress Test Principle

True mastery requires **application and reasoning**, not recognition and recall. Socratic questioning forces you to close gaps in your reasoning chain until you can logically justify all 10 questions.