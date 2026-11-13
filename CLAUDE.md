# AM Endurance: context for Claude Code

Jekyll site for AM Endurance: interactive Kumu knowledge maps on metal
additive manufacturing (powder bed fusion). Owner: Hamed Ghadimi.

Hosting: classic GitHub Pages, deployed from `main`. Jekyll version pinned by
the `github-pages` gem (currently 3.10.x). Theme: Minimal Mistakes via `remote_theme`.

Project Phoenix: staged site rebuild. The master plan lives in Hamed's
claude.ai Project; each session Hamed pastes a brief.

## Rules

- Work only on `phoenix`. Never commit to, push, or merge into `main`.
  Never force-push.
- Never change the visible body text of articles in `_posts/`. Front
  matter and non-visible markup change only when a brief says so.
- Use only plugins supported by GitHub Pages.
- Before deleting any file, list it and wait for confirmation.
- Explain changes briefly in plain language.
- After changes, run `bundle exec jekyll build` and report the result.
- One logical change per commit, with clear messages.
- Internal files (CLAUDE.md, README, LICENSE, Gemfile, etc.) must stay
  in the `exclude` list in _config.yml so they are not published.
- End each session with a concise summary Hamed can paste back.
- If any step needs Hamed's password or sudo, stop and give Hamed the
  exact command to run in the terminal.
- Stop any preview server you start before the session ends; Hamed runs
  his own previews.

## Site conventions (approved)

- Navigation: Maps (/maps/), About (/about/), Subscribe (LinkedIn
  newsletter: https://www.linkedin.com/newsletters/am-endurance-7325356841809375233/).
- Planned URLs: /maps/, /series/melt-pool/, /series/inspection/,
  /series/steels/, /about/, /about/project/. Article permalinks never
  change (except an approved typo fix, always with a redirect).
- Topics, exactly one per map in `categories`: Feedstock, Process
  Physics, Defects, Materials & Microstructure, Post-Processing,
  Inspection & Characterization.
- Tags, controlled list only: l-pbf, eb-pbf, plus material family
  (e.g. stainless-steel, ti-6al-4v).
- Title convention: "[Topic] in Metal Additive Manufacturing
  ([Process]) — [Subtitle]", plus a `short_title` field. Use EB-PBF,
  never EBM.
- Front-matter fields for maps: title, short_title, excerpt,
  categories, tags, series, series_order, kumu_url, pdf_url,
  header (overlay_image, teaser, og_image), last_modified_at.
