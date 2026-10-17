# Corrections

- 2026-10-08: Commit 56344ba appended registry entry #433 (chipmath) with correct, byte-exact content, but landed under an erroneous Copilot-generated commit message ("Update print statement from 'Hello' to 'Goodbye'"). The intended message was "registry: #433 chipmath". This note corrects the record.
- 2026-10-17: Registry entries #375-#646 were spliced with drifted field names (url/shipped, then number/pages, 4 entries with built only), so the catalog rendered href="undefined" and every "Open app" link since #375 (Oct 6) 404'd. Normalized all entries to n/name/slug/subject/one_liner/repo/live/created_at and made the renderer tolerate the drifted fields. App sites themselves were never down.
