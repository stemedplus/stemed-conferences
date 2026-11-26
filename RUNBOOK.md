# Runbook: Conferences

This board uses the shared STEMEd+ pipeline. For how every board works and the common fixes, see the [stemedplus-theme runbook](https://github.com/stemedplus/stemedplus-theme/blob/main/RUNBOOK.md).

| | |
|---|---|
| **Site** | stemedplus.github.io/stemed-conferences |
| **Repository** | stemedplus/stemed-conferences |
| **Updates** | Daily at 10:23 UTC, on push, and by hand (`update.yml`) |
| **Listings** | One YAML file per conference series in `conferences/`, checked against `schema/conference.schema.json` |
| **Check / build** | `python -m stemed_conferences --validate`, then `python -m stemed_conferences --out output` |
| **Add or fix** | **Suggest a conference** and **Update a conference** issue forms |

**Routine check:** the site footer's "For maintainers" box lists files to re-check: any not checked in 180 days, and any meeting with announced (not official) dates starting within 120 days. Check those each month.

Past meetings drop off and past deadlines are marked automatically. The date each meeting was first listed carries over for the RSS feed.

_Written November 2026. Review with the yearly December review._
