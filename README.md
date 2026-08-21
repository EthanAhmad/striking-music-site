# ARCHIVED — striking-music.com moved

This static GitHub Pages site was **retired on 2026-08-20**. Since
**2026-08-19**, `striking-music.com` is served by the Flask `public_app` in
the private **lesson-automation** repo (nginx + gunicorn on the droplet),
which also owns the SMS consent form and its server-side TCPA consent
records.

- Design/architecture: `docs/PUBLIC_SURFACE_VISION.md` in that repo
- The DNS cutover record: `docs/PUBLIC_SURFACE_P3_RUNBOOK.md`
- All legacy URLs here (`/*.html`) 301-redirect to clean paths on the live
  site.

This repo is kept read-only as history. The final served state is commit
`aaf499e`.
