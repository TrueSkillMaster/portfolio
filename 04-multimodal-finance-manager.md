# 04 · Multi-modal AI Finance Manager

**Origin:** training build
**Role:** AI integration architect & data engineer

## Problem

Manual expense entry is slow, inaccurate, and mostly doesn't happen.

## Solution — three input types, one system

| Input | Processing |
|---|---|
| Voice message | Whisper transcription → amount + category extraction |
| Photo of a receipt | Vision OCR → key fields parsed |
| Text | direct parsing |

Shared output: contextual auto-categorisation → strict JSON → Google Sheets row.

## Result

Any input format → a structured row. Zero manual entry.

## What it taught

Strict JSON output with a fixed schema is the difference between "works in the demo" and "works on the 400th receipt". This is where the *validate, don't throw* habit started.

`Make / n8n` `OpenAI Vision` `OpenAI Whisper` `Google Sheets`
