# Ritual V3 catalog health

Published scorecards and catalog records evaluated 20 Nov 2026, 11:05 AM ET. Draft checks are excluded. Source: DX catalog, scorecard definitions, and per-entity check results for the Ritual V3 account.

> **Two programs are overdue, and two checks block entire ladders**
>
> OpenTelemetry migration is 112 days past due at 6.1% complete, and critical CVE remediation is 14 days past due with 18 entities still outside the critical SLA. Separately, documentation has not placed a single service on Bronze because two README command checks fail all 79 services, and Entity ownership cannot reach Silver because the Slack-team check fails all 459 in-scope entities.

## Headline metrics

- **Catalog entities:** 691
- **Checks passing:** 48.9%
- **Entities with no owner:** 66.6%
- **Services fully green:** 0

11,198 published check results across 677 scored entities: 5,476 pass, 395 warn, 5,327 fail. Every result executed in the last 2.1 hours (median 1.2 hours), matching the 2-hour evaluation frequency. Exemptions in force: 0.

## Health KPIs and coverage

The catalog is integration-fed and recently evaluated. Coverage is wide. Completeness is not.

- 518 of 691 entities were created via API.
- Services were all touched in the last 30 days.
- Team records and repository descriptions were not complete.

## Check results by population

- **Services:** 7/33 checks pass
- **Repositories:** 17/31 checks pass
- **Teams:** 17/19 checks pass
- **APIs:** 0/6 checks pass
- **Resources:** 14/29 checks pass

Top failing groups from the source view:

- Repositories and APIs are almost entirely red.
- Team ownership coverage is incomplete.
- Service documentation checks are universally failing.

## Team ownership

- **Owned by a team:** 33%
- **No owner:** 67%
- Owner teams on the entity record: none
- No entity has a user owner
- 75 of 79 services are owned
- All 373 API endpoints are unowned

## Entity detail snapshot

| Entity type   | Records | Owned | Description blank | On a scorecard | Stale signal |
|---|---:|---:|---:|---:|---|
| API endpoint  | 373 | 0  | 0   | 373 | 355 last updated 90-180 days ago |
| Repository    | 163 | 82 | 163 | 163 | 81 last updated 180-365 days ago |
| Service       | 79  | 75 | 3   | 79  | All updated in the last 30 days |
| Team          | 55  | 55 | 55  | 55  | 51 last updated more than a year ago |

## Notes

- This page is recreated from the referenced canvas so you have a visible editable copy.
- If you want, I can also generate this as a polished DX-styled PDF or a shareable HTML page.
