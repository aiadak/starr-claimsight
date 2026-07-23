# === Starr ClaimSight — environment variables ===
# Add these in Vercel:  Project -> Settings -> Environment Variables
# (Do NOT commit real keys to GitHub.)

# Anthropic API key for the Catastrophic Claims agent (server-side only).
ANTHROPIC_API_KEY=sk-ant-your-key-here

# Optional. Defaults to claude-sonnet-5.
#   claude-haiku-4-5  -> cheaper / faster
#   claude-sonnet-5   -> balanced (default)
#   claude-opus-4-8   -> highest quality
ANTHROPIC_MODEL=claude-sonnet-5
