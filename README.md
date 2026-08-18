# Abdullahi Idris Usman — Personal Academic Website

Source for my personal academic website, built on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template (forked from [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/)) and hosted on GitHub Pages.

Live site: https://abdullahiusmanidris.github.io

**Note:** for this URL to work, this repository must be named exactly `AbdullahiUsmanIdris.github.io` on GitHub (Settings → General → Repository name). GitHub Pages serves a repo named `<username>.github.io` at the domain root; any other repo name is served at `https://<username>.github.io/<repo-name>/` instead.

## Contents

- `_pages/about.md` — homepage / bio / research interests
- `_pages/cv.md` — full CV (education, experience, publications, awards, skills)
- `_publications/` — journal articles and manuscripts
- `_portfolio/` — selected engineering and research projects
- `_teaching/` — teaching and tutoring experience
- `_posts/` — blog updates on research and the PhD application process
- `_data/navigation.yml` — top navigation menu
- `_config.yml` — site-wide configuration (name, bio, social/academic links)

## Running locally

1. Install Ruby, Bundler, and Node.js.
2. `bundle install` to install dependencies (delete `Gemfile.lock` and retry if you hit resolver errors).
3. `bundle exec jekyll serve -l -H localhost` and open `http://localhost:4000`.

Jekyll auto-rebuilds on changes to Markdown/HTML content; changes to `_config.yml` require restarting the server.

## Updating content

- Add a new publication: create a Markdown file in `_publications/` following the front matter of an existing entry.
- Add a new project: create a Markdown file in `_portfolio/`.
- Add a new blog post: create a file in `_posts/` named `YYYY-MM-DD-title.md`.
- Update the CV: edit `_pages/cv.md` directly.

## License

Site content is © Abdullahi Idris Usman. Template code is MIT-licensed via [Academic Pages](https://github.com/academicpages/academicpages.github.io); see `LICENSE`.
