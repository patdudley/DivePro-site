# DiveProSD public deployment mirror

This public repository is generated from the private
[patdudley/DivePro](https://github.com/patdudley/DivePro) forecast/model source and is
served at <https://diveprosd.com/>.

## Repository role

- Receives exported static assets from `DivePro` through its
  `deploy-public-site.yml` workflow.
- Publishes the legacy DiveProSD site through GitHub Pages.
- Provides current Scripps camera pointers and referenced images to the
  [DiveProCA production site](https://github.com/patdudley/Dive-Pro-Demo).

Generated deployment commits use messages such as `Deploy DiveProSD from <source SHA>`.
Avoid editing generated files here by hand because the next source deployment may overwrite
those changes.
