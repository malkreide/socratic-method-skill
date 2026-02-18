# Usage Guide: Socratic Method Skill

This guide provides detailed information on effectively using the Socratic Method Skill with Claude.

## Installation Methods

### Method 1: Claude.ai Projects (Recommended)

1. Open your Claude.ai project
2. Navigate to **Project Settings** → **Skills**
3. Click **"Add Custom Skill"**
4. Upload the `SKILL.md` file from this repository
5. The skill will automatically activate based on user interactions

### Method 2: Claude Desktop / API

Include the skill content in your system prompts or custom instructions when initializing conversations.

## Activation Triggers

The skill activates automatically when users express the following:

### Learning Intent
- "Explain X to me"
- "Help me understand Y"
- "I don't understand how Z works"
- "Explain the concept of..."

### Problem-Solving Need
- "I'm stuck on this problem"
- "How do I solve..."
- "I can't figure out..."

### Critical Thinking
- "What should I do about..."
- "Is this approach correct?"
- "What's the best way to..."

### Conceptual Understanding
- "What does X mean?"
- "Define Y"
- "How would you describe..."

## Operating Modes

The skill adapts to four different contexts:

### 1. Pedagogical Mode (Default)

**Best for:** Academic learning, conceptual understanding, skill development

**Characteristics:**
- Collaborative tone
- Patient guidance
- Step-by-step discovery
- Pattern recognition

**Example Interaction:**
```
User: "What is the quadratic formula?"
Claude: "Good question. Let's build it together. What form does a quadratic equation take?"
User: "ax² + bx + c = 0"
Claude: "Exactly. And what are we trying to solve for?"
User: "The value of x"
Claude: "Right. Do you know any methods for solving for x in this type of equation?"
```

### 2. Therapeutic Mode (CBT-Based)

**Best for:** Cognitive restructuring, challenging negative thoughts, emotional processing

**Characteristics:**
- Empathetic validation
- Evidence testing
- Alternative perspectives
- Gentle challenging

**Example Interaction:**
```
User: "I always fail at everything"
Claude: "That sounds like a painful thought. When you say 'always', can you think of recent situations where you didn't fail?"
User: "Well, I finished my project last week..."
Claude: "That's interesting. So you successfully completed your project. Does that fit with 'always failing'?"
User: "I guess not..."
Claude: "What might be a more accurate description of your experience?"
```

### 3. Legal/Analytical Mode

**Best for:** Logical reasoning, rule interpretation, edge-case analysis

**Characteristics:**
- Rigorous questioning
- Hypothetical scenarios
- Logical consistency tests
- Reductio ad absurdum

**Example Interaction:**
```
User: "The contract says delivery must be 'reasonable'"
Claude: "What do you think 'reasonable' means in this context?"
User: "Within a normal timeframe"
Claude: "Let's test that. If delivery of a book takes 6 months, is that reasonable?"
User: "No, that's too long"
Claude: "What about 2 days?"
User: "That's reasonable"
Claude: "So we have 2 days as reasonable and 6 months as unreasonable. Where would you draw the line and why?"
```

### 4. Coaching/Strategic Mode

**Best for:** Business decisions, management challenges, strategic planning

**Characteristics:**
- Professional tone
- Consequence analysis
- Root cause investigation
- Future-oriented thinking

**Example Interaction:**
```
User: "I think we should cut the marketing budget"
Claude: "What's driving this decision?"
User: "We need to save money"
Claude: "I see. What impact would cutting marketing have on revenue?"
User: "It could reduce sales..."
Claude: "So we'd save on marketing but potentially lose revenue. How do those two compare in your projections?"
User: "I haven't calculated that yet"
Claude: "What would you need to know to make this decision confidently?"
```

## Question Types and When to Use Them

### 1. Clarification Questions
**Purpose:** Make vague concepts concrete
**Use when:** Users employ abstract or ambiguous terms
**Examples:**
- "What exactly do you mean by 'success'?"
- "Can you give me a specific example?"
- "Are you using 'fair' in the legal or colloquial sense?"

### 2. Assumption Probes
**Purpose:** Uncover hidden premises
**Use when:** The user's argument relies on unstated beliefs
**Examples:**
- "You seem to assume that X causes Y. What makes you think that?"
- "Why did you choose this framework over others?"
- "What would need to be true for this to work?"

### 3. Evidence Questions
**Purpose:** Test the foundation of claims
**Use when:** Users make assertions without support
**Examples:**
- "How do you know that's true?"
- "What evidence supports this view?"
- "Is there data that contradicts this?"

### 4. Perspective Questions
**Purpose:** Encourage cognitive flexibility
**Use when:** Users are stuck in a single viewpoint
**Examples:**
- "How would your competitor see this situation?"
- "What would a critic say about your approach?"
- "If you were in their position, how would you see it?"

### 5. Implication Questions
**Purpose:** Follow logic to conclusions
**Use when:** Testing consistency and consequences
**Examples:**
- "If we apply this rule universally, what happens?"
- "What are the long-term consequences?"
- "If this is true, what else must be true?"

### 6. Meta-Questions
**Purpose:** Reflect on the exploration itself
**Use when:** The dialogue needs redirection
**Examples:**
- "Why do you think I asked that question?"
- "Are we asking the right question here?"
- "What assumptions does this question make?"

## Advanced Techniques

### The Socratic Reversal
When users ask a question, ask them what *they* think first:

```
User: "What is the capital of France?"
Claude: "What do you think?"
User: "I'm not sure... Paris?"
Claude: "What makes you think that?"
```

### Pattern Induction
Build a sequence that users can extend:

```
Claude: "Let's look at a pattern: 2+2=4, 3+3=6, 4+4=8. What's happening?"
User: "The number is being doubled"
Claude: "Right. So what would 5+5 be?"
```

### Counterexample Method
Present cases where the user's definition fails:

```
User: "Courage is perseverance"
Claude: "Is foolish perseverance courage? If someone persists in a harmful endeavor, is that courageous?"
```

### Consequence Analysis
Explore what follows from a position:

```
User: "All taxes are theft"
Claude: "If taxes are theft and theft is always wrong, should we have no taxes?"
User: "Well, we need some for roads..."
Claude: "So if we need some taxes, how does that fit with 'all taxes are theft'?"
```

## Handling Common Challenges

### User says: "Just tell me the answer!"

**Response:**
```
"I understand you want a quick answer. I'm asking questions because research shows you'll understand and remember better when you discover it yourself. Would you like to try one more question with me, or should I explain it directly this time?"
```

### User becomes frustrated

**Signs to watch for:**
- "I don't know!"
- Shortened responses
- Expressions of confusion or distress

**Action:**
1. Validate: "This is challenging. Many people find this counterintuitive."
2. Scaffold: Provide a hint or smaller step
3. Offer choice: "Would you like me to give you more guidance, or try a different approach?"

### User gives up

**Response:**
```
"I can see you're feeling stuck. Let me provide some structure: [brief hint or framework]. What do you think now?"
```

### Infinite Regress

**Avoid asking "Why?" repeatedly without variation**

Bad:
```
User: "Because X"
Claude: "Why?"
User: "Because Y"
Claude: "Why?"
```

Good:
```
User: "Because X"
Claude: "What makes X the cause?"
User: "Because Y"
Claude: "How would you test whether Y actually causes X?"
```

## Best Practices

### Do:
✅ Ask ONE question at a time
✅ Restate the user's position to show understanding
✅ Use softeners: "I'm curious...", "Help me understand..."
✅ Validate effort: "You're thinking deeply about this"
✅ Wait for the user's response before proceeding
✅ Monitor mood and adjust tone

### Don't:
❌ Give direct answers when asked
❌ Ask rhetorical questions
❌ Generate the answer then ask if users agree
❌ Abandon the method at the first sign of difficulty
❌ Ask multiple questions in one turn
❌ Use an aggressive or interrogating tone

## Measuring Success

A successful Socratic dialogue shows:

1. **User output > Claude output** — Users do most of the talking
2. **Progressive understanding** — User responses become more sophisticated
3. **Self-correction** — Users notice and correct their own errors
4. **Transfer** — Users apply insights to new problems
5. **Ownership** — Users express the conclusion in their own words

## Domain-Specific Tips

### For Mathematics
- Use patterns and sequences
- Encourage visualization
- Build from concrete to abstract
- Let learners discover formulas

### For Writing/Literature
- Anchor in textual evidence
- Compare interpretations
- Explore author choices
- Connect to personal experience

### For Natural Sciences
- Start with observation
- Form hypotheses
- Test predictions
- Examine evidence

### For Business/Strategy
- Focus on consequences
- Identify assumptions
- Test against edge cases
- Consider stakeholder perspectives

## Troubleshooting

### "The skill doesn't activate"

Make sure you're using trigger phrases like:
- "Help me understand..."
- "Explain to me..."
- "I don't understand..."

### "Claude keeps lecturing"

Try explicitly saying:
- "Don't tell me the answer, help me figure it out"
- "Use the Socratic method"
- "Guide me with questions"

### "Questions feel too aggressive"

The skill includes tone management. If this happens, please report it as a bug.

## Getting Help

If you encounter issues:
1. Check this usage guide
2. Review the example dialogues in SKILL.md
3. Open an issue on GitHub
4. Join the discussions section

---

**Remember:** The goal is not to demonstrate your knowledge, but to guide users in discovering their own.
