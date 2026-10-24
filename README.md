# East Valley School Ratings Feed

Public JSON override feed for the East Valley School Map Android app.

The app reads `ratings.json` and applies valid 1–10 values to matching school names. Missing schools keep their embedded ratings; `null` removes a rating.

```json
{
  "schemaVersion": 1,
  "updatedAt": "2026-10-25",
  "source": "GreatSchools profile verification",
  "ratings": {
    "Cecil Shamley School": 4
  }
}
```

GreatSchools 1–10 rating data may be subject to licensing and attribution requirements. Verify usage rights before adding or redistributing ratings.
