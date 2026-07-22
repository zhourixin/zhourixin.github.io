# Rixin Zhou's academic homepage

This repository contains the source for [zhourixin.github.io](https://zhourixin.github.io), built with Jekyll and the Academic Pages theme.

## Where to update personal information

- `_config.yml`: site title, sidebar profile, avatar, email, and social links.
- `_pages/about.md`: homepage introduction, research interests, and highlighted work.
- `_pages/cv.md`: current affiliation, education, and academic profile links.
- `_pages/projects.md`: project descriptions and links.
- `_pages/publications.md`: publications landing page.
- `_publications/`: one Markdown file per publication.
- `_data/navigation.yml`: top navigation.
- `images/profile.jpg`: sidebar and social-preview image.

The current site uses information supplied by the owner or verified from public GitHub repositories, paper pages, ORCID, and OpenReview. Before adding a title, Google Scholar profile, LinkedIn profile, or downloadable CV, verify those details and then update `_config.yml` and the relevant page.

## Preview locally

Install Ruby and Bundler, then run:

```bash
bundle install
bundle exec jekyll serve
```

Open <http://localhost:4000>. GitHub Pages rebuilds the public site after commits are pushed to `master`.

## Theme attribution

The site is based on [Academic Pages](https://github.com/academicpages/academicpages.github.io), itself derived from [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes). See `LICENSE` for the theme license.
