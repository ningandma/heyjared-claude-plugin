![HeyJared](assets/heyjared-logo.png)

# HeyJared for Claude

HeyJared finds the reporters, newsletters, podcasts, and channels that fit your company, shows how you are covered today, and helps you prepare pitches grounded in each outlet's recent work. This plugin connects Claude to your HeyJared account.

## What you can do

- **Find media opportunities**: rank outlets by editorial fit for your company and read what each one has published recently.
- **Understand your coverage**: see the coverage feed, storylines, tone, geography, share of voice, and the people and organizations the coverage names.
- **Compare competitors**: see where rivals are covered and you are not.
- **Check search and AI visibility**: organic search results and AI-assistant answers are reported separately from media coverage.
- **Prepare outreach**: draft a pitch for one outlet, plan who to tell about an announcement, and look up an outlet's contact routes.

Try asking Claude:

- "Find media opportunities for Climate TRACE."
- "Compare our media coverage, search visibility, and AI visibility."
- "Draft a pitch grounded in a reporter's recent work."

## What the plugin contains

- A skill, `media-research`, that tells Claude how to use HeyJared's tools, cite sources, and report gaps honestly.
- A connection to HeyJared's remote MCP server at `https://api.tryinkwell.co/plugin/mcp`.

The plugin runs no local code, hooks, or scripts.

## Connecting and data

You sign in to HeyJared through OAuth when you first use the connector. Claude never sees your password, and the plugin never asks for credentials in chat. When you use a tool, Claude sends HeyJared the request you made, such as a company domain, a search query, or the outlet you want to pitch, and HeyJared returns research from your account. The plugin sends data only to HeyJared's server above.

HeyJared never sends email or messages for you through this plugin. Pitches are drafts for you to review and send yourself. The plugin has no billing, checkout, or payment tools.

## Access

Each HeyJared account receives one complimentary 30-day period on its first connection, with usage limits: 25 tracked subjects, five brands, and 50 pitch preparations. Reconnecting does not reset it, and there is no automatic charge. Existing paid HeyJared plans keep their entitlements. Social coverage monitoring is not part of this plugin.

## Privacy, terms, and support

- Privacy policy: https://heyjared.ai/legal/privacy
- Terms of service: https://heyjared.ai/legal/terms
- Help center: https://heyjared.ai/helpcenter
- Contact: hey@heyjared.ai
