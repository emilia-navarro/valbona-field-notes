# Data Provenance Template

Use this block in every file that contains operational, geographic, ecological, or cultural claims.

```md
## Data Provenance

- **Claim / dataset:**
- **Source:**
- **Source type:** official / academic / operator / field observation / community report / derived analysis
- **Last verified:** YYYY-MM-DD
- **Method:** direct source review / GPS track / DEM analysis / satellite imagery / interview / field photo / other
- **Confidence:** High / Medium / Low
- **Known limitations:**
- **Next verification step:**
```

## Confidence Labels

### High

Use for official, institutional, or directly reproducible sources.

Examples:

- official protected-area page;
- UNESCO listing;
- published operator timetable checked on a specific date;
- repository-owned GPX track with metadata.

### Medium

Use for reputable but non-official or endpoint-dependent data.

Examples:

- trekking guide metrics;
- OSM-derived coordinates;
- triangulated transfer times;
- local route descriptions.

### Low

Use for claims that are plausible but not yet measured.

Examples:

- “construction has increased visibly”;
- “guesthouse density appears higher”;
- “transfer usually aligns with ferry arrivals”;
- “snow often remains until mid-June”.
