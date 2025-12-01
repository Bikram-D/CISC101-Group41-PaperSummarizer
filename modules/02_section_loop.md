Changelog (2025-11-30): Added summary_level variable and conditional behavior.
## **Module 2: Section Loop**
- For each section with respect to `summary_level`:
  - If `summary_level = "short"` → generate 1–2 sentence summary.
  - If `summary_level = "detailed"` → generate a short paragraph plus a bullet list of 3–5 key points.
  - Enforce ≤100 words for summaries (bullet lists excluded).
  - Check constraints (length, clarity, order).
  - Store structured output for rendering.
