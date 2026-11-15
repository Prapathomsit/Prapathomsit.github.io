# Prapathomsit Attapakkanon · Portfolio

**Live site → https://prapathomsit.github.io**

Year-1 CEDT student at Chulalongkorn University, applying for a QA Automation Tester internship.

I built this site with an AI coding assistant (Claude Code). The AI wrote most of the code. My part was the QA part: deciding what "correct" means, then proving it.

## Why this matters for a QA role

- **Every claim traces back to evidence.** The numbers on the site come from real runs: the Playwright trace (5.156 s load), the live Google Sheet (12/12 passed) and the actual spec file. An early AI draft invented timings like "0.38s". Those were replaced with measured values.
- **The screenshots are reproduced, not mocked up.** Playwright scripts captured all four images from the real systems. One of them is a live reproduction of the TC-03 checkout bug.
- **Tested like a release.** Checked with Playwright on desktop and on a 390 px phone screen: no JavaScript errors, no horizontal overflow, and every link works. The checks were run again on the live URL after deploying.
- **AI makes the work faster. Testing keeps it honest.** That is how I'd use AI on a QA team: build quickly, then verify everything.

## What's on the site

- **Featured:** a Playwright + TypeScript E2E suite with CI and a live Google Sheets report
- **How I test:** 80/80 unit tests in Prakan (AI incident-report app, Biztania 2026), database permission tests for its officer portal, and a negative test plan for a pilot
- **Competitions:** NSC 2025 national award (Z.O.O), Biztania 2026 finalist, JUMP Thailand Hackathon 2026, UniHack 2026, KMITL Game Jam (top 20 of 300+), Nuutor Cup

## Featured project

[**playwright-ecommerce-e2e**](https://github.com/Prapathomsit/playwright-ecommerce-e2e): Playwright + TypeScript with the Page Object Model. It runs 4 tests × 3 browsers on GitHub Actions and streams the results to a [live Google Sheet](https://docs.google.com/spreadsheets/d/19KROjkgRaDWTIVBfifGJpQjuhYWc4qtKpqVOdnpXm80/edit?gid=0#gid=0).

## Contact

prapathomsit.work@gmail.com · [github.com/Prapathomsit](https://github.com/Prapathomsit)

<details>
<summary>Editing notes</summary>

Static single file with no build step. Preview locally with `python3 -m http.server 5220`.
Projects, links and screenshots are set in the arrays at the bottom of `index.html` (`PROJECTS`, `LINKS`, `SCREENSHOTS`). Push to `main` and GitHub Pages redeploys in about a minute.
</details>
