# 05 · Form → Make → AI → Email / PDF

**Origin:** client — a fractional marketing director, UK (first engagement of five)
**Role:** Make automation developer
**Platform:** Upwork · two milestones

## Problem

Jotform sent email and name as nested arrays; Make threw `BundleValidationError` and could not send the personalised email. The AI-generated score in the report was **always 75/100**, whatever the answers.

## Milestone 1

- **Diagnosis:** Jotform hides values behind technical labels in an array structure
- Custom functions to extract a clean email string and first name
- HTML formatting (`<br>`) so the email renders correctly
- **Trigger re-architected:** 15-minute polling → webhook (instant, and it removed a duplicate-run problem the polling had created)
- Loom video as proof of work after the fix

## Milestone 2

- **Prompt engineering:** real scoring logic with variable mapping — the model stopped returning a fixed score
- **Email system:** final email formatted with personal data
- **PDF automation:** generated PDF with name, personal score and a CTA button to the booking calendar
- **Design:** client's PDF template implemented (he does design himself — price adjusted down accordingly)
- **Next stage discussed:** GoHighLevel integration — booking → funnel → automated sequence

## Done without being asked

| Action | Why it mattered |
|---|---|
| Proposed webhook instead of polling | Polling caused duplicates — found and fixed unprompted |
| Reduced the price when the client took design on himself | Honest adjustment |
| Built the PDF mock-up in Photoshop | Initiative outside scope |
| Offered GHL support when the client mentioned GHL | Led to milestones 3, 4 and 5 |

`Make` `Jotform` `OpenAI` `CloudConvert` `Gmail` `GoHighLevel`
