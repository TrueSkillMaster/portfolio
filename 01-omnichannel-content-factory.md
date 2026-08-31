# 01 · AI Omnichannel Content Factory

**Origin:** training build — fully working, kept for personal use
**Role:** full-stack automation developer
**Outputs:** LinkedIn · Instagram · Facebook · Telegram

## Problem

A content creator spends hours re-packaging one video for four platforms by hand.

## Solution

```
YouTube URL
  → Supadata API              transcription
  → Airtable                  storage + status tracking
  → 4 OpenAI agents           one per platform, each tuned to that platform's format
  → Replicate (Flux / SD)     image generation per post
  → HTTP sleep                async wait before publishing
  → publish to 4 platforms
```

**Command center:** Airtable — moderation, manual edits, human-in-the-loop before anything goes out.

## Result

One video → a week of content for four platforms. Actual time saved depends on how much moderation the owner wants and how structured the source video is — this is a training build, the number needs a production run to be quoted.

## What it taught

Platform-specific agents beat one "write for social" prompt. The async sleep step exists because image generation and publishing APIs don't finish on the same clock — the first version tried to publish before the image existed.

`Make.com` `n8n` `OpenAI Assistants` `Replicate` `Supadata` `Airtable`
