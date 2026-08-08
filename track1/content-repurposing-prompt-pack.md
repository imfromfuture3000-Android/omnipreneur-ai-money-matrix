# Content Matrix AI – Prompt Library (v1.0)

Copy-paste ready prompts optimized for Claude 3.5 / GPT-4o.

## Master System Prompt
You are Content Matrix AI, an elite content strategist and repurposing engine. Your sole job is to transform one high-quality long-form piece into a complete multi-platform content matrix that maximizes reach, engagement, and conversion while preserving the original voice and accuracy. Always output structured, ready-to-publish assets. Never invent facts. Prefer concrete numbers, stories, and frameworks from the source.

## Prompt 1: Full Content Matrix Generator
```
SOURCE CONTENT:
[PASTE TRANSCRIPT OR TEXT HERE]

TARGET AUDIENCE: [Creators / Solopreneurs / Finance beginners / etc.]
TONE: [Educational / Conversational / Authoritative]

Generate a complete Content Matrix with the following sections:

1. 5 Viral Hooks (ranked by predicted retention)
2. YouTube Shorts / TikTok / Reels scripts (5 pieces, 30–60s each, with on-screen text suggestions)
3. X/Twitter Thread (10 tweets max, numbered, strong first and last tweet)
4. LinkedIn Post + Carousel outline (7–9 slides)
5. Email Newsletter version (subject line + body, 400–600 words)
6. Notion Database entry fields: Title variations (3), SEO keywords, Tags, Viral Score (1–10), Key Takeaways (bullet list)
7. One CTA recommendation optimized for list-building or product sale

Format cleanly with markdown headings.
```

## Prompt 2: Hook Factory
```
From this content: [paste]
Generate 12 scroll-stopping hooks for Shorts/Reels. 
Categories: Curiosity, Contrarian, Story, Data, Pain-Agitation, Transformation.
Each hook under 12 words. Rank top 5 with reason.
```

## Prompt 3: Thread Architect
```
Turn this long-form into a high-engagement X thread.
Rules: First tweet must stop the scroll. Each tweet 1–2 sentences max. Use line breaks. End with clear CTA and question. Include 1–2 relevant emojis max.
Source: [paste]
```

## Prompt 4: SEO Title + Thumbnail Text Generator
```
Generate 8 YouTube titles (under 60 chars) + matching thumbnail text ideas (3–5 words, high contrast) for this content. Prioritize search + click-through.
Source: [paste]
```

## Prompt 5: Notion Database Formatter
```
Convert the following content summary into a structured Notion-ready JSON that I can paste into a database property or use with Notion API:
{
  "title": "",
  "hooks": [],
  "platforms": {"shorts": [], "thread": "", "linkedin": "", "email": ""},
  "seo_keywords": [],
  "viral_score": 0,
  "cta": ""
}
Source summary: [paste]
```

## Bonus: Platform-Specific Tone Adjusters
- Shorts: Punchy, visual, pattern interrupt every 3s
- LinkedIn: Professional insight + personal story
- Email: Conversational + value first
- X: Concise + opinionated

Use these prompts as the foundation for the full SaaS “recipes” feature.