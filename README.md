# Behavioural Segmentation — a Claude skill

Replaces "who our users are" with **"what our users do, and what each kind needs next"**. It produces 2–4 named, measurable segments that change real decisions.

It's a **framework skill**: project-agnostic, with no company, product or personal data. It works on any product.

## What it helps with

| Task | Example prompt |
|---|---|
| Build segments | "Our personas don't predict anything. Build behaviour-based segments." |
| Intent | "How do I account for low-intent traffic in our funnel?" |
| Success | "Define success per segment for our product." |
| Tracking | "What do we need to track to keep these segments alive?" |

## Install

### Claude Code — as a personal skill

```bash
git clone https://github.com/apkolota/behavioural-segmentation-skill.git ~/.claude/skills/behavioural-segmentation
```

Claude loads it automatically when the topic comes up, or you can call it with `/behavioural-segmentation`.

### Claude.ai

Download `behavioural-segmentation.zip` from `dist/` (or [Releases](../../releases)) and upload it in **Settings → Capabilities → Skills**.

## Structure

```
SKILL.md                 # when to use, the flow, principles, default deliverable
references/
├── playbook.md          # step-by-step guidance with decision points
├── templates.md         # fill-in templates for every output
├── contexts.md          # adapting by product type, data, time and team
└── anti-patterns.md     # how this work goes wrong
```

## Related

Part of a set of product design skills: [senior-product-designer-skill](https://github.com/apkolota/senior-product-designer-skill) · [product-designer-skill](https://github.com/apkolota/product-designer-skill)

## License

MIT
