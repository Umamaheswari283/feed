Plan Generated Feb 24 2026 by Venkata

## Overview
Integrate Discord API team member data with a Google Sheet-based members-lite.csv file for use in the FeedPlayer application.

## Goals
- Use DISCORD_BOT_TOKEN from /docker/.env (fallback to /feed/.env).
- Remove redundant .env files from membersense backend.
- Integrate Discord handles with Github usernames using members-lite.csv.
- Enable public testing Discord channel.
- Ensure bot token remains active (investigate expiration issue).
- Enable Swiper list view from URL hash (ex: #list=modelteam).
- Confirm gallery view works with list=modelteam.

## Current Status
- Discord API backend exists in feed/membersense/backend.
- Frontend FeedPlayer is live at model.earth/feed.
- Some UI tasks completed.
- Bot key appears to expire after two days.
- Integration with Google Sheet members-lite.csv not fully completed.

## Proposed Implementation Steps
1. Review backend token configuration in docker/.env.
2. Consolidate environment variable usage.
3. Inspect Discord API token expiration cause.
4. Map Discord usernames to Github accounts via members-lite.csv.
5. Test Swiper and URL hash integration.
6. Test gallery view with #list=modelteam.
7. Activate test Discord channel for public testing.

## Expected Output
- Stable Discord API integration.
- Google Sheet to Discord handle mapping functional.
- Token persistence resolved.
- FeedPlayer list filtering working via URL hash.
- Cleaned backend configuration.
