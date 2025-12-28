# Week 1

## Summary For 2025-12-28
**Concise Summary**

- **Total effort:** 2 h 46 m 5 s (≈9 966 s) recorded on a single machine (aryanshdevs‑pop) using VS Code (Linux) during Dec 27 18:30 – Dec 28 18:29 UTC (Asia/Kolkata).  
- **Human‑only edits:** ~1 764 additions and 1 575 deletions; no AI contributions.

### Time Allocation
| Area | Time | % of total |
|------|------|------------|
| Front‑end | 1 h 48 m | ~65 % |
| Avtaarmusic‑Backend | 58 m | ~35 % |
| **Languages** | | |
| JavaScript | 1 h 45 m | ~63 % |
| TypeScript | 56 m | ~34 % |
| Bash | 4 m | ~3 % |

### Development Effort by Dependency (≈12 % each)
- **lucide‑react** – 1 h 44 m 32 s (1.73 h, 12.63 %)  
- **react** – 1 h 44 m 32 s (≈12.6 %)  
- **apiClient** – 1 h 44 m 32 s (≈12.6 %)

### Other Notable Modules (≈5 % each)
- AuthContext – 0 h 46 m 33 s (5.63 %)  
- express – 0 h 45 m 14 s (5.47 %)  
- mongoose – 0 h 39 m 15 s (≈5 %)

### Execution‑Time Hotspots (runtime, % of total)
- **mongoose** – 2 355 s (≈39 m, 4.74 %)  
- **user.model** – 2 130 s (≈35 m, 4.29 %)  
- **song.model** – 1 979 s (≈33 m, 3.99 %)  
- **favourite.model** – 1 979 s (≈33 m, 3.99 %)  
- **axios** – 1 820 s (≈30 m, 3.66 %)  
- **FirebaseHelper** – 1 532 s (≈25 m, 3.09 %)

These six components together consume ~25 % of total runtime; the rest is spread across many smaller modules (each <1 %).

### Minor Runtime Contributors (≈0.05 % each)
- Various route files (wallet.routes, message.routes, etc.) and utility modules (fs, client‑s3, mins, s3.config, user.types) each run ~26‑30 s, representing a negligible share of total processing time.

**Overall picture:** The bulk of work was front‑end JavaScript development, with three core dependencies (lucide‑react, react, apiClient) accounting for ~30 % of effort. Runtime profiling shows a handful of data‑access modules (mongoose, model files) dominate execution time, while most route handlers and utilities consume only a tiny fraction. All activity was human‑generated.