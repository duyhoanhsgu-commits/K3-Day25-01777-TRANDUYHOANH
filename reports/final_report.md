# Day 10 Reliability Final Report

## Metrics Summary

| Metric | Value |
|---|---:|
| total_requests | 300 |
| availability | 0.99 |
| error_rate | 0.01 |
| latency_p50_ms | 269.19 |
| latency_p95_ms | 313.59 |
| latency_p99_ms | 317.83 |
| fallback_success_rate | 0.9565 |
| cache_hit_rate | 0.6133 |
| circuit_open_count | 9 |
| recovery_time_ms | 2320.638418197632 |
| estimated_cost | 0.048668 |
| estimated_cost_saved | 0.184 |

## Chaos Scenarios

| Scenario | Status |
|---|---|
| primary_timeout_100 | pass |
| primary_flaky_50 | pass |
| all_healthy | pass |

## Analysis TODO(student)

Explain what failed, why the fallback path worked or did not work, and what you would change before production.