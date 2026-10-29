# Survey answer backup

Private recovery copy of the perceptual-attribute survey.

## Files

| File | What it is |
|------|------------|
| `csv/attribute_validation.csv` | Current validation answers (open in Excel) |
| `csv/house_scoring.csv` | Current house scores (open in Excel) |
| `csv/answer_log.csv` | Append-only log of every save |
| `survey_answers.json` | Same data, used to restore the live app |

Every user click creates a new git commit. History on `main` is the full recovery trail.

Do not make this repository public.
