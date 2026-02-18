# Socratic Method Skill for Claude

🇩🇪 **[Deutsche Version / German Version](docs/de/README.md)**

A Claude Skill that transforms AI into a Socratic tutor, guiding users toward knowledge discovery through systematic questioning rather than direct instruction.

## Overview

This skill implements the classical Socratic method (maieutics) for pedagogical interactions, cognitive restructuring, strategic coaching, and analytical thinking. Instead of delivering direct answers, Claude uses disciplined questioning to help users develop deep understanding through self-discovery.

## Key Features

- **Pedagogical Mode**: Deep conceptual learning through guided exploration
- **Therapeutic Mode**: CBT-based cognitive restructuring and belief examination
- **Legal/Analytical Mode**: Rigorous logical reasoning and edge-case analysis
- **Coaching Mode**: Strategic decision-making and problem-solving

## Use Cases

This skill activates when users:
- Ask to learn: "explain to me", "help me understand", "teach me X"
- Seek problem-solving help: "I'm stuck", "how do I solve"
- Show confusion or need critical thinking
- Request conceptual understanding
- Face strategic decisions or management challenges

## Core Principles

1. **Maximize user output, minimize system output** — Users generate knowledge from their own mind (Generation Effect)
2. **Never lecture** — Questions are the catalyst, not direct instruction
3. **Maieutics** — Claude acts as "midwife of ideas", not a content delivery system
4. **Dialectical balance** — Explore both thesis and antithesis

## Installation

### For Claude.ai Projects

1. Download the `SKILL.md` file from this repository
2. Go to your Claude.ai project → Project Settings → Skills
3. Upload the `SKILL.md` file or create a new custom skill
4. The skill will automatically activate based on user interaction patterns

### For Claude Desktop/API

Include the skill content in your system prompts or custom instructions.

## Usage Examples

### Example 1: Mathematics
```
User: "Why is negative times negative positive?"
Claude: "Good question. Let's look at a pattern. What is 3 × -2?"
User: "-6"
Claude: "Right. And 2 × -2?"
User: "-4"
Claude: "Now 1 × -2?"
User: "-2"
Claude: "Look at the results: -6, -4, -2. What happens each time?"
User: "They go up by 2."
Claude: "Exactly. So continuing the pattern, 0 × -2 equals 0. What should -1 × -2 be?"
User: "Oh! Positive 2!"
```

### Example 2: Cognitive Restructuring
```
User: "My friends are ignoring me. They hate me."
Claude: "That's a painful thought. What evidence do you have that they hate you?"
User: "They haven't texted me all weekend."
Claude: "I see. Is it possible there are other reasons they haven't texted?"
User: "Well, one of them has exams..."
Claude: "If she has exams, does her silence mean she hates you, or that she's busy?"
```

## Question Taxonomy

The skill uses six question types:

1. **Clarification Questions** — Operationalize vague terms
2. **Assumption Probes** — Uncover unstated beliefs
3. **Evidence Questions** — Demand data and reasoning
4. **Perspective Questions** — Encourage cognitive flexibility
5. **Implication Questions** — Follow logic to conclusions
6. **Meta-Questions** — Reflect on the dialogue itself

## Operating Modes

- **Pedagogical (Default)**: Collaborative, patient, curious
- **Therapeutic (CBT-based)**: Empathetic, gentle, validating
- **Legal/Analytical**: Rigorous, precise, challenging
- **Coaching/Strategic**: Professional, pragmatic, future-oriented

## Safety Measures

The skill includes important safeguards:
- Psychological safety measures for frustrated users
- Ethical boundaries to prevent manipulation
- Bias balance for exploring multiple perspectives
- Frustration threshold detection with scaffolding mode

## Best Practices

- Questions should be genuine, not rhetorical
- Maintain warmth and collaboration (Socratic ≠ Interrogation)
- Acknowledge user effort and normalize difficulty
- Monitor mood and adjust tone accordingly
- Never abandon the method at the first sign of difficulty

## Multilingual Support

This skill is available in two languages:
- **English** (this version) — Root directory
- **German** — [docs/de/](docs/de/)

Choose the SKILL.md in the language you want Claude to use for Socratic dialogues. Claude will conduct the dialogue in the language of the loaded skill.

## Context

This skill was developed by **Hayal** to support pedagogical interactions and strategic decision-making in the context of public administration and education.

## Contributing

Contributions are welcome! Please don't hesitate to submit issues, feature requests, or pull requests.

Areas for potential improvement:
- Additional domain-specific adaptations
- Extended multilingual support
- Integration examples with specific educational platforms
- Evaluation metrics for Socratic dialogue quality

## License

MIT License — see [LICENSE](LICENSE) file for details.

## Author

**Hayal Oezkan**
Marketing and Communications / AI Specialist Group, City of Zurich Administration

GitHub: [@malkreide](https://github.com/malkreide)

## Acknowledgments

Based on the classical Socratic method and modern pedagogical research on:
- The Generation Effect (cognitive psychology)
- Maieutics (Socratic midwifery of ideas)
- Cognitive Behavioral Therapy (CBT) questioning techniques
- Dialectical thinking

---

*"I know that I know nothing."* — Socrates

---

<div align="center">

**Made with ❤️ in Zurich**

[LinkedIn](https://www.linkedin.com/in/hayaloezkan/) • [Documentation](docs/) • [Contributing](CONTRIBUTING.md)

</div>
