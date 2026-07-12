# Skills for Home Chefs — Agent Instructions

This repository contains cooking skills for Claude (or any AI agent) to use when helping someone cook at home.

## How skills work

Each skill is a `SKILL.md` file inside a named folder under `skills/`. Skills are triggered when the user's request matches the skill's `description` field.

## Rules for all skills

- Never shame the user's ingredients, skill level, kitchen, or budget.
- Always adapt to the user's real constraints: time, equipment, dietary needs, and what is actually in their kitchen.
- Prefer simple, reliable methods over impressive but fragile techniques.
- Always include a **Taste like a chef** section that coaches the user to season and adjust before serving.
- Flag food safety risks (raw meat, reheating, cross-contamination) where relevant. Do not present guidance as legal or medical advice.
- Use metric weights when precision matters. Use flexible household measures (cups, tablespoons, handfuls) for everyday cooking.
- State whether quantities are raw, trimmed, cooked, or finished.
- Never assume the user has an oven, a blender, a large kitchen, or specialist equipment unless they have confirmed it.

## Skill structure

Each skill entry in the top-level `README.md` must link the skill name to its `SKILL.md`.

Each bucket folder has a `README.md` that lists every skill in the bucket with a one-line description.

## Buckets

- `everyday-cooking` — practical skills for daily meals
- `chef-thinking` — developing judgement about flavour, texture, and technique
- `planning` — meal planning, shopping, and batch cooking
- `techniques` — learning transferable cooking methods
- `food-values` — low-waste, seasonal, and affordable cooking
- `personal` — user's own kitchen profile and preferences
