# Convert Your Recipe to a Skill Using AI

You do not need to fill in the template manually.
You can use any AI assistant (Claude, ChatGPT, Gemini) to convert your recipe into the skill format in under a minute.

---

## Step 1 — Copy this prompt

Copy everything in the box below and paste it into Claude, ChatGPT, or any AI assistant.

```
I want to contribute a recipe to a community cooking skills library.
Please convert my recipe into the skill format below.

Here is my recipe:
[PASTE YOUR RECIPE HERE — any format: ingredients and steps, a rough description, a dish you cook from memory, or a recipe passed down from family]

Please follow this format exactly:

---
name: [dish-name-in-lowercase-hyphenated]
cuisine: [e.g. Cantonese, Japanese, Italian, South Asian, Southeast Asian, Western, Fusion]
contributor: [Your name or GitHub handle]
description: >
  One or two sentences describing this dish and when to use this skill.
---

# [Dish Name]

*Contributed by [Your name] — [one sentence about your connection to this dish]*

---

## About this dish
2–3 sentences: where it comes from, why it is worth making at home, what makes it special.

---

## At a glance

| | |
|---|---|
| **Serves** | |
| **Active time** | |
| **Total time** | |
| **Difficulty** | Beginner / Intermediate / Confident |
| **Main technique** | |
| **Dietary notes** | |

---

## Ingredients

**Main ingredients:**
- ingredient — quantity (note if essential or optional)

**For the sauce / marinade / seasoning:** (if applicable)
- ingredient — quantity

**To finish / garnish:** (optional)
- ingredient — quantity

**Substitutions:**
Note any common substitutions here.

---

## Method

Numbered steps in chronological order. At each key step, include a sensory cue —
what the cook should see, hear, smell, or feel — not just how many minutes.

1.
2.
3.

---

## Taste like a chef

Guide the cook to taste and adjust before serving. Be specific to this dish:
- Salt or seasoning check
- Acid or brightness check
- Texture check
- Finishing touch

---

## Make it yours

2–3 practical variations or personalisation ideas.

---

## The next day

How to store leftovers and how long they keep.
One idea for transforming leftovers into a second meal rather than just reheating.

---

## Food safety note (include only if relevant)

Any raw meat, seafood, egg, or reheating considerations for this dish.

---

## Contributor notes (optional)

Anything else: the story behind the dish, a tip learned the hard way, a pairing suggestion, a seasonal note.
```

---

## Step 2 — Paste your recipe

Replace `[PASTE YOUR RECIPE HERE]` with your recipe in any format:

- A rough list of ingredients and steps
- A dish you cook entirely from memory — just describe it
- A recipe a family member taught you
- A photo of a handwritten recipe card (describe it in text)
- A recipe clipped from a magazine or book (paraphrase it in your own words)

The AI will fill in the structure, add sensory cues to the method, suggest substitutions, and write the *Taste like a chef* section.

---

## Step 3 — Review and make it yours

Read through the output. Check:

- [ ] The method matches how you actually cook it
- [ ] The quantities look right
- [ ] The *Taste like a chef* section reflects the dish
- [ ] The contributor note sounds like you

Edit anything that does not feel right. **This is your recipe — the AI is just formatting it.**

---

## Step 4 — Submit your recipe

1. [Fork this repo](https://github.com/cyronchan/skills-for-home-chefs/fork)
2. Create a new file at: `skills/recipes/[cuisine]/[your-dish-name]/SKILL.md`
3. Paste your converted skill into that file
4. Add a line for your dish in [skills/recipes/README.md](../skills/recipes/README.md)
5. Open a Pull Request with a short description of the dish

See [CONTRIBUTING.md](../CONTRIBUTING.md) for full details on folder naming and standards.

---

## Before and after example

### What you paste to the AI

> My mum's braised pork belly. Brown the pork, then braise with soy sauce, dark soy, oyster sauce, sugar, garlic, and a bit of water for about an hour until soft. Serve over rice.

### What the AI produces

A complete `SKILL.md` with:
- A warm introduction and cultural context for the dish
- An at-a-glance table with timing and difficulty
- A full ingredient list with quantities, what is essential vs optional, and substitutions
- A step-by-step method with sensory cues: *"the pork should be deeply lacquered and pull apart with gentle pressure from a spoon"*
- A *Taste like a chef* section checking salt balance, sweetness, and sauce reduction
- Storage and next-day transformation ideas
- A contributor note for you to personalise

---

*The goal is to lower the barrier to zero. If you can describe a dish, you can contribute a skill.*
