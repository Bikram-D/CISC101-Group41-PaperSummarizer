Changelog (2025-11-30): Added evidence_mode and section warning messages.
## **Module 3: Guardrails**
- Strict Evidence Mode: If `evidence_mode = "strict"`
    - Only include claims, equations, and results from the text.
    - If insufficient detail: output → “The source text does not provide enough detail to summarize this section in strict evidence mode.”
- Section Warning Messages:
    -  If missing/empty section → “Section skipped: no usable text was provided.”
    -  If section too short (<50 words) → “Section very short: summary may be incomplete.”
