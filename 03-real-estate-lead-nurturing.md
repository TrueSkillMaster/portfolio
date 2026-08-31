# 03 · Real Estate AI Lead Nurturing

**Origin:** training build — business case: an Australian real-estate agent
**Role:** CRM automation & AI solutions architect

## Problem

The agent spends 30–60 minutes per lead: transcribe the call → write the follow-up → track the status.

## Solution

```
Call
  → auto-transcription
  → AI summary
  → lead profile enriched in Airtable
  → GPT drafts the follow-up email
  → human-in-the-loop: draft appears in Airtable for review
  → one field for edits → system rewrites and sends
  → notification with a link to the draft
  → status change in Airtable → triggers the next step
```

## Result

Routine lead handling reduced to a short review step. The human controls quality; the machine does the routine.

## Note on portability

This scenario was later moved from HubSpot-style logic to n8n in about four hours. Different nodes, same sequence — the point of documenting the flow rather than the tool.

`Airtable` `OpenAI` `Make` `Gmail`
