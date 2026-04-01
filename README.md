[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# Vybegineer Test Results

Standardized head-to-head testing of vibe coding tools. Same prompt, every tool, real data.

**"One Prompt, Everybody Knows the Rules."**

## What This Is

Every vibe coding tool gets the same prompt. We track everything: credits consumed, dollar cost, time to output, code quality, and whether the result actually works. Results are published openly so non-technical founders can make informed decisions about which tools to use — and which to avoid.

## Scoring Rubric (/30)

Each test is scored across 6 dimensions, 5 points each:

| Dimension | What It Measures |
|-----------|-----------------|
| **Renders** | Does the output render without errors? Visual accuracy vs. prompt intent. |
| **Functions** | Do interactive elements work? Auth, payments, persistence — does it actually function? |
| **Code Quality** | Clean structure, maintainability, no obvious anti-patterns or dead code. |
| **Cost Efficiency** | Credits and dollars consumed relative to output quality. Hidden costs surfaced. |
| **Time Efficiency** | Total time from prompt submission to working deployment. Includes iteration cycles. |
| **Security** | Authentication handling, input validation, dependency hygiene, secret management. |

**Total: /30.** Methodology, prompt library, and full scoring criteria at [vybegineer.com/methodology](https://vybegineer.com/methodology).

## Repository Structure

```
test-results/
├── prompts/          # Standardized test prompts (categorized)
├── results/          # Raw test outputs by tool and date
├── screenshots/      # Visual captures of each test output
├── scores/           # Scored rubrics (JSON)
└── analysis/         # Cross-tool comparisons and trends
```

## Tools Tested

Cursor, v0, Lovable, Bolt, Replit, Windsurf, Emergent, Google AI Studio — and more as the ecosystem evolves.

## How Results Are Published

All test results are published openly in this repository. Raw code, screenshots, scores, and cost data — nothing is hidden. If a tool fails, the data shows it.

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
