# Networking 101- System Design

_Study session `c3e7b3a31cc0` · started 2026-10-23 02:01 UTC · saved 2026-10-23 06:16 UTC_

## At a glance

- **Questions answered:** 8 (4 correct, 3 of them by override)
- **Concepts studied:** 5
- **Strong:** 1 · **Recovered:** 3 · **Still shaky:** 1
- **Up next:** Timeouts and Retries

## Topics studied

| Concept | Asked | Correct | Where it stands |
| --- | --- | --- | --- |
| OSI Model | 2 | 1 | Recovered |
| gRPC | 2 | 1 | Recovered |
| Load Balancing | 2 | 1 | Recovered |
| Content Delivery Network (CDN) | 1 | 1 | Strong |
| Timeouts and Retries | 1 | 0 | Still shaky |

## Where I'm strong

- **Content Delivery Network (CDN)** — correct, first try

## Where I struggled

### Still open

- **Timeouts and Retries** — missed 1 of 1
  - _Question:_ Explain the failure handling strategy known as Timeouts and Retries, including the key mechanisms used to prevent the system from being overwhelmed during retries.
  - _What was missing:_ The student expressed points 2, 3, and 4 clearly. However, point 1 is missing: the student does not explain that requests have time limits and that exceeding the limit causes them to be treated as failed. The student mentions 'waiting some time and then retrying a request that previously failed' but does not address the timeout mechanism that determines when a request is considered failed in the…

### Worked through

- **OSI Model** — missed once, then got it right
- **gRPC** — missed once, then got it right
- **Load Balancing** — missed once, then got it right
