# java-review — field test results

**Live results page → https://qgambit2.github.io/java-review-results/**

A multi-agent Java code-review swarm — independent specialist reviewers plus adversarial verification — tested on **7 real Apache & Halo pull requests it had never seen**.

- **Recall.** Two bugs that maintainers had already found and fixed were reintroduced by reverting their fix. Both were caught, and each survived a separate agent whose only job was to refute it against the code.
- **Precision / false positives.** Five real PRs reviewed exactly as submitted returned "looks good" on all five, with **zero false positives** — reproduced across two runs.

The page has the full breakdown: every finding, every verdict, the method, and the honest caveats (small sample; the clean PRs measure false positives more than recall — an existence result, not a benchmark).

The reviewer itself: **https://github.com/qgambit2/java-review**
