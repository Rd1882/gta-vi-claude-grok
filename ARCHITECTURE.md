# Detailed System Architecture

## Data Flow

1. **Scout (Grok Bot)** runs scheduled or on-demand research.
2. Brief is delivered to user (chat / notification).
3. User (or automation) pastes top idea into Claude with a prompt from `claude-prompts/`.
4. Claude outputs script / site code / ad copy.
5. User films, clips, or deploys.
6. Distribution via X clipping feature, YouTube, etc.
7. Feedback loop: high-performing content ideas are noted back to Scout for more of the same.

## Key Integrations

- Grok Bot ↔ X (native search and posting research)
- Claude ↔ Claude Code / Claude.ai Projects (Skills for voice)
- Optional: GitHub for storing scripts, sites, asset packs
- Optional: Notion / Drive for content calendar (connect if needed)

## Daily Routine (set on the Scout bot)

- 9 AM EST: Opportunity Brief
  - Top 5 ideas
  - Trending questions
  - New assets / GitHub finds
  - Monetization angle of the day

This keeps the research layer always-on while Claude handles the creative and build heavy lifting.
