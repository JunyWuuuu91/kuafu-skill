<div align="right">

[English](./README_en.md) | [中文](./README_zh.md)

</div>

<div align="center">

# 🌅 Kuafu · Cognitive Framework Distiller

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> *"What we chase is not the sun, but the operating principles behind it. Frameworks can be extracted, inspiration cannot; but once frameworks are extracted, the probability of inspiration rises."*

</div>

---

## What is Kuafu?

Kuafu is an AI skill that distills any person, school of thought, or intellectual system into a **runnable cognitive operating system**. It evolved from [Nuwa](https://github.com/alchaincyf/nuwa-skill) with a critical addition: the **Meta-Cognition Layer** — making distilled frameworks dynamic rather than static snapshots.

**Key Distinction**: We capture *HOW they think*, not *WHAT they said*.

---

## The Six-Layer Distillation

| Layer | Content | Key Question |
|-------|---------|--------------|
| Layer 1 | Expression DNA | What are their sentence patterns, rhythm, and taboo words? |
| Layer 2 | Mental Models | Through what lens do they see the world? |
| Layer 3 | Decision Heuristics | What are their intuitive rules? |
| Layer 4 | Anti-Patterns | Where are their value boundaries? |
| Layer 5 | Honesty Boundaries | Where does this framework systematically fail? |
| Layer 6 ★ | Meta-Cognition | How do they update their own cognitive system? |

**Layer 6 is Kuafu's core evolution over Nuwa**: Without it, you get a static snapshot; with it, you get a dynamic cognitive system.

---

## Quick Start

### Installation

```bash
# Copy SKILL.md to your skills directory
cp SKILL.md ~/.config/opencode/skills/kuafu-framework-distiller/SKILL.md
```

### Usage

Simply invoke with a person's name or intellectual system:

```
/distill Charlie Munger
/distill Nassim Taleb's antifragility framework
/distill I need a thinking framework to help me make decisions
```

---

## How It Works

### Phase 0: Input Routing

| Input Type | Path |
|------------|------|
| Clear name/system | **Direct Path** → Phase 0A |
| Vague need/confusion | **Diagnostic Path** → Phase 0B |

### Phase 1: Information Gathering

- **Local Corpus Mode**: User-provided documents (books, transcripts, blogs) take priority
- **Network Search Mode**: Systematic search across writings, interviews, social media, biographies

### Phase 2: Six-Layer Distillation

Each layer undergoes rigorous validation:
- Mental models require **triple verification**: cross-domain reproduction, generative power, exclusivity
- Decision heuristics need: trigger condition → rule → underlying logic → known counterexamples

### Phase 3: Stress Testing (Red/Blue Team)

Every core model faces:
- 🔵 **Blue Team**: Optimal scenarios and success cases
- 🔴 **Red Team**: Systemic failure modes and historical counterexamples

### Phase 4: Generate SKILL.md

Output follows a standardized structure stored at:
```
.claude/skills/[name]-perspective/SKILL.md
```

---

## Output Structure

Generated SKILL.md includes:

```
├── Role-Playing Rules (first-person activation)
├── Layer 1: Expression DNA
├── Layer 2: Mental Model Library (3-7 models, triple-verified)
├── Layer 3: Decision Heuristic Handbook
├── Layer 4: Anti-Pattern Checklist
├── Layer 5: Honesty Boundaries
├── Layer 6: Meta-Cognition Layer ★
│   ├── Framework Update Mechanism
│   ├── Internal Tension Map
│   └── Cognitive Evolution Trajectory
└── Response Workflow (Agentic Protocol)
```

---

## Special Scenarios

### Topic Skills (Non-Person)

When the need points to a methodology rather than a person:

| Dimension | Person Skill | Topic Skill |
|-----------|--------------|-------------|
| Core | One person's thinking | A domain's toolkit |
| Model Source | Primarily one person | Multiple perspectives |
| Expression | Simulate their style | Neutral but professional |

### Updating Existing Skills

```
/update Charlie Munger skill with new 2024 interviews
```

### Handling Information Scarcity

For subjects with limited public information:
- Explicitly note low confidence levels
- Still complete all six layers with caveats
- Document information gaps in honesty boundaries

---

## Honest Boundaries (Kuafu's Own Limitations)

- Cannot distill **intuition** — frameworks can be extracted, inspiration cannot
- Cannot capture **mutations** — only a snapshot at research time
- Public expression ≠ true thoughts — based only on observable information
- **Meta-cognition layer is inferential** — subjects may not self-describe their update mechanisms
- **Action advice has temporal validity** — requires re-verification as conditions change

> *A skill that doesn't tell you where it fails isn't worth trusting.*

---

## Examples

### Distilling a Person

```
Input: Distill Charlie Munger's investment philosophy

Output: SKILL.md with:
- 5 mental models (inversion, circle of competence, latticework, etc.)
- 8 decision heuristics with trigger conditions
- Meta-cognition: How Munger updates via "flipping" and reading biographies
- Tension map: Patience vs. decisiveness (High tension)
```

### Distilling a Topic

```
Input: Create a framework for understanding complex systems

Output: SKILL.md with:
- Mental models from Taleb, Santa Fe Institute, evolutionary economics
- Decision heuristics for non-linear problems
- Meta-cognition: How the field's paradigms evolve
```

---

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## License

Distributed under the MIT License. See `LICENSE` for more information.

---

## Acknowledgments

- Evolved from [Nuwa (女娲)](https://github.com/alchaincyf/nuwa-skill)
- Inspired by cognitive science research on mental models and decision-making
- Built for the [OpenCode](https://github.com/nicepkg/opencode) ecosystem

---

<div align="center">

**[English](./README_en.md)** | **[中文](./README_zh.md)**

</div>
