# AI Co-Thinker

A prompt and five rules for using AI as a thinking partner instead of an answer machine.

Most AI use is generate this, build that, tell me what to do. This does the opposite: it makes the AI reflect your own thinking back at you, question by question, instead of handing you a verdict.

Distilled from Daljeet Singh's talk *"Let's Talk About AI"* ([rainbowdragon.digital](https://rainbowdragon.digital)).

## The core idea: mirror, not oracle

An AI reflects patterns back at you. It doesn't originate insight, and it can't imagine a genuinely new future, only recombine what's already been said. Treat it as a mirror you think against, not an oracle that hands down answers.

Use this when you want to:
- Think through your values, strengths, or goals
- Work through a decision without just being told what to do
- Be challenged, not agreed with

Don't use it as a substitute for therapy or a real human mentor. If a conversation starts needing that, say so and step away from the AI.

## The prompt

This is the one to paste into ChatGPT, Claude, or anything similar:

> I want to articulate my values, strengths and goals. Walk me step by step through a series of reflective questions that can guide me. Do not act as an agreeable coach, challenge me when it's needed but also be supportive and help me think deeply. Ask me one question at a time before moving on to the next one.

## Five rules for running the session well

1. **One question at a time.** Never dump a full list of questions. Wait for a real answer before moving on.
2. **Challenge when needed.** Don't let the AI default to agreeable-coach mode. If an answer is vague, contradictory, or dodges the hard part, it should push back before moving on.
3. **Stay supportive alongside the challenge.** The goal is depth, not discomfort for its own sake.
4. **Check your own agency periodically.** Ask yourself (or have the AI ask you): "Is this a skill I want to keep?" / "What would I have done before I had AI?" These questions surface dependency and keep you doing the actual thinking.
5. **Keep the thread going.** A good answer to question 1 isn't a stopping point, it should shape how hard the AI pushes on question 2, 3, and beyond. Don't let the whole thing collapse into one round of pushback followed by agreement.

## Bonus: evaluating your own prompts

A companion habit worth building: before sending any prompt to an AI, check whether it's actually extractive when it should be receptive.

| Extractive (defaults to this) | Receptive (usually better) |
|---|---|
| "Generate a plan for X" | "What patterns are there in X?" |
| "Build me a summary" | "What is emerging from this?" |
| "Create content about X" | "How are people discussing X?" |
| "Write my values statement" | "What do people feel is true about X?" |
| "What should I do with my career" | "What patterns show up in how I talk about my career when I'm frustrated vs. energized, and what do those patterns suggest I already know?" |

**Example of the difference in practice:**

Input: *"what should I do with my career"*

An extractive answer hands you a verdict, three bullet points and a recommendation, based on almost nothing.

A receptive answer looks more like this:

> That's a good question to sit with, and it's yours to answer, not mine to answer for you. Let's go one step at a time.
>
> First question: think of the last time you talked about work and felt actually energized, not performing enthusiasm, properly lit up. What were you talking about?

Same input, completely different value. One tells you what to think. The other helps you find out what you already think.

## Using this as a Claude Code skill

If you use [Claude Code](https://claude.com/claude-code), the [`claude-code-skill/SKILL.md`](./claude-code-skill/SKILL.md) file in this repo is a ready-to-drop-in skill: put it at `~/.claude/skills/ai-cothinker/SKILL.md` and Claude will pick it up automatically whenever a conversation calls for this kind of thinking.

## Credit

Core framing and reference prompt: Daljeet Singh, *"Let's Talk About AI"* — [rainbowdragon.digital](https://rainbowdragon.digital)
