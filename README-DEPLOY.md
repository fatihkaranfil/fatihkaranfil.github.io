# Academic website redesign: deployment notes

This is an additive patch for the existing Beautiful Jekyll GitHub Pages repository, not a complete replacement.

## Files to add or replace
- Replace root `index.html` with the included file.
- Add `assets/css/academic.css`.
- Add root `research.md`.

## Deployment
1. Back up the existing repository or create a new branch.
2. Copy these three files into the matching paths in `fatihkaranfil/fatihkaranfil.github.io`.
3. Commit to a preview branch first and review the site with a local Jekyll build or a GitHub Pages preview workflow.
4. Merge to the publishing branch after reviewing the text, links and mobile display.

## Important
- Existing `themes.md`, `teaching.md`, `cv.html`, and CV PDF remain untouched.
- The homepage has its own CSS and does not change styling of legacy pages. This is a first-phase redesign; subsequent work should unify secondary pages with the new visual system.
- Verify academic titles, publication status, links, and the PDF CV before launch.
- The existing Google Analytics configuration appears legacy and should be reviewed separately.
- The GitHub repository could not be cloned in the build environment. These files were drafted from the publicly accessible repository listing and raw configuration/content. A full local Jekyll build has not been performed.


## Portrait and ministry policy work

1. Add your own licensed professional portrait at `assets/images/fatih-portrait.jpg` (portrait-oriented, ideally 1200 x 1500 px). The site displays a neutral placeholder until the photo is supplied.
2. Review the Ministry of Energy and Ministry of Industry and Mineral Resources descriptions. They intentionally avoid unverified claims about employment, formal appointments, project titles, or endorsements.
3. Replace the generic policy descriptions with confirmed project names, roles, dates, outcomes and public links. Do not publish confidential client or ministry information.
4. Review existing publication, CV, and biography information before deployment.
