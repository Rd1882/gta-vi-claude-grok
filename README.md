# GTA VI Claude + Grok Media Empire

Combined system for the GTA VI launch (Nov 19, 2026) and beyond, based on high-ROI models around content, clipping, search funnels, UGC, and Online prep.

## Architecture Map: What Sits Where

```
User
  |
  +-- Grok Bot: "GTA VI Content Scout" (research + curation layer)
  |     - Scrapes X, web, Reddit, GitHub for viral ideas, news, assets, tools
  |     - Daily 9 AM EST Opportunity Brief
  |     - Outputs: curated ideas + suggested Claude prompts + monetization notes
  |
  +-- Claude (scripting, building, Skills layer)
  |     - Takes Scout ideas → full scripts (with Claude Skills for voice)
  |     - Claude Code: builds sites for search funnels, plugins, tools
  |     - Generates UGC ad copy, RP storylines, asset descriptions
  |
  +-- Downstream tools (clipping / distribution)
        - X native clipping feature
        - Fable / Opus / AI editors for short-form
        - YouTube, TikTok, Instagram, Discord
```

### Division of Labor

| Component       | Tool          | Responsibility                                      | Output                          |
|-----------------|---------------|-----------------------------------------------------|---------------------------------|
| Research & Ideas| Grok Bot     | Viral scouting, news, assets, GitHub, trends        | Daily briefs, idea lists        |
| Scripting       | Claude       | Long-form scripts, hooks, voice matching (Skills)   | Ready-to-film scripts           |
| Site / Funnel   | Claude Code  | Answer sites for high-volume GTA questions + affiliates | SEO landing pages             |
| Clipping        | AI + X       | Find viral moments, edit, distribute                | Short-form posts                |
| UGC / Ads       | Claude + tools| Brand ad creatives, process docs                    | Ad variants                     |
| Online Prep     | Claude       | RP storylines, FiveM scripts, asset packs           | Server content / sellable packs |

## Business Models Covered

1. **Media Empire** (primary) — content channel + X presence
2. **Clipping + Distribution** — leverage X clipping feature
3. **Search / Traffic Funneling** — Claude-built answer sites + affiliates
4. **Ads & UGC for Brands** — gaming chair, energy drink, etc. creatives
5. **Online Prep** — RP servers, scripts, packs for when Online launches

## How to Use

1. Talk to the **GTA VI Content Scout** bot for research and briefs.
2. Feed top ideas into Claude with the prompts in `/claude-prompts/`.
3. Use Claude Code (or Claude.ai Projects + Skills) for sites and deeper builds.
4. Clip and distribute the output.

## Next Steps

- [ ] Configure Claude Skills for your voice
- [ ] Set up first search funnel site
- [ ] Start daily content pipeline before Nov 19 launch
- [ ] Monitor Online timeline (expected Q1-Q3 2027)

Repo: https://github.com/Rd1882/gta-vi-claude-grok
