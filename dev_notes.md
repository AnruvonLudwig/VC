# CV Page — Dev Notes

Tracking the *code* side of the CV build (not content). Update as things land.

## Done

- [x] `index.html` skeleton with sections: About, Education, Experience, Skills, Projects, Contact
- [x] Colour Themes (dark/light via `prefers-color-scheme`)
- [x] `.project-card` layout + `.project-link` status styling (`status-public` / `status-private` / `status-pending`) using `color-mix()`
- [x] `.skills-group` layout for split skill categories

## To do — structure / functionality

- [ ] Decide `Coming Soon` nav item — what it links to and update `href`
- [ ] Create `Home.html`
- [ ] Education section add Year 1 modules/subjects or leave 
- [ ] Manual dark/light toggle (currently auto-only via `prefers-color-scheme`)
  - add `data-theme` attribute handling on `<html>`
  - add `[data-theme="dark"]` / `[data-theme="light"]` override blocks in `styleGlobal.css` (comment already left as a marker)
  - small JS: read/write toggle state (localStorage), set attribute on load 

## To do — polish / QA

- [ ] Test responsiveness at mobile widths (`.cv-wrap`, `.cv-entry-heading` wrap, `.projects-list` grid)
- [ ] Verify keyboard focus states are visible (nav links, project links)
- [ ] Confirm `aria-current="page"` logic still correct once more pages/nav items are added

## To do — deployment

- [ ] Decide final file paths 