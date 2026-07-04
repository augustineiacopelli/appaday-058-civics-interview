# AppADay 058 — Civics Interview Practice

A practice tool for the civics portion of the U.S. naturalization interview, built directly on the official USCIS civics questions and answers. Two test versions are included. The 2008 test draws ten questions at random from a bank of 91 (of the official 100), and passes at six correct. The 2025 test, which USCIS began administering to anyone who files Form N-400 on or after October 20, 2025, draws twenty questions at random from a bank of 120 (of the official 128), and passes at twelve correct. Both banks intentionally exclude officeholder-dependent and state-specific questions, such as the current President, Governor, Senators, Representative, and state capital, since those answers change over time or depend on where the applicant lives and would go stale inside a fixed quiz.

Each session follows the real interview's stopping rule rather than running a fixed length. The 2008 test session ends the moment the applicant reaches six correct answers or five incorrect ones; the 2025 test session ends at twelve correct or nine incorrect, matching the thresholds USCIS actually uses. Every answer reveals the official USCIS-published response regardless of what was chosen.

A session that ends with any missed questions shows a review list on the results screen, each missed question paired with its official answer, so the tool doubles as a study aid rather than just a scorecard. The start screen also reports how many sessions have been completed and the best result achieved on that device, tracked separately for the 2008 and 2025 modes using localStorage, so a 6-of-10 result and a 12-of-20 result are never conflated. A text-size toggle in the header (A+ / A-) increases type size across the whole interface, since this test's real audience skews toward older applicants and English learners.

The closing screen is styled as a federal notice, with a stamped verdict of Requirement Met or Requirement Not Met.

Built as vanilla HTML, CSS, and JavaScript with no frameworks or build step. Fonts load from Google Fonts CDN (PT Serif, IBM Plex Mono). No API keys and no external network calls; the only persisted state is the per-device session count and best score, stored in localStorage. Includes an on-page disclaimer that this is an independent study aid and not produced, reviewed, or endorsed by USCIS or the Department of Homeland Security.

Category: Games (G)
Live at: https://augustineiacopelli.github.io/appaday-058-civics-interview/
