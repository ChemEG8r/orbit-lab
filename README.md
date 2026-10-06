# Orbit Lab

Chapter 9 Earth-Sun-Moon study practice for VJ: all 25 vocabulary terms
(with definitions corrected and sharpened where the worksheet was thin),
Earth facts (23.5° tilt, Polaris, what causes seasons, eclipse types),
and the moon — including PICTURE questions where the app draws a phase
and asks which one it is, plus sequence questions. The study sheet shows
all 8 phases in correct order (the cycle ends waning CRESCENT — the
worksheet had "waning gibbous" twice).

15 random questions per quiz from a 55-question bank, multiple choice +
forgiving fill-in-the-blank, instant grading with a one-line "why",
per-quiz miss detail in history, cross-device sync via /api/scores
(Cloudflare Pages Function + Workers KV bound as SCORES).

Deploy: `npx wrangler pages deploy . --project-name orbit-lab --branch main`
(needs `CLOUDFLARE_API_TOKEN` and `CLOUDFLARE_ACCOUNT_ID`).
