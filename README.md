# DH Lab

Course website for the **DH Lab**, the hands-on companion to
[Introduction to Digital Humanities](https://dhbern.github.io/introduction-to-dh/) at the
University of Bern (Walter Benjamin Kolleg / Digital Humanities).

Co-taught by Tobias Hodel, Elena Spadini and Francesco Beretta, with guest sessions by Stephen
Hart, Adrian Demleitner and Ismail Prada Ziegler.

🌐 <https://dhbern.github.io/dh-lab/>

|                      |                                                                                                                           |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| Semester             | Autumn Semester 2026 (HS 2026)                                                                                            |
| Time                 | Tuesdays, 14:00–17:15 (sharp)                                                                                             |
| Room                 | Unitobler, Lerchenweg 36, F-123                                                                                           |
| First / last session | 15 September 2026 / 15 December 2026                                                                                      |
| Companion course     | [Introduction to DH](https://dhbern.github.io/introduction-to-dh/) ([repo](https://github.com/DHBern/introduction-to-dh)) |
| Course materials     | [ILIAS](https://ilias.unibe.ch/ilias.php?baseClass=ilrepositorygui&cmdNode=yv:ng&cmdClass=ilObjCourseGUI&ref_id=3733960)  |

The Lab is where the practical part of the MA Major and MA Minor in Digital Humanities happens:
command line, Git, SQLite, ontologies, APIs, TEI, Omeka, notebooks, OpenRefine, eScriptorium and
multimodal LLMs — plus the programme's introductions, consultations and final-year
presentations.

## Structure

```
contents/
  home.qmd             what the Lab is, organisation, joint weekly programme
  syllabus.qmd         all 14 sessions
  sessions/NN.qmd      one page per session
  assignment.qmd       workflow assignment (presentation + write-up)
  resources.qmd        toolbox
  blog.qmd             student workflow write-ups
  posts/               student contributions
  about.qmd            teaching team, licence, related sites
  bibliography.bib     readings (currently a placeholder)
```

## Local development

Requires [Quarto](https://quarto.org/docs/get-started/).

```bash
quarto preview      # live preview
quarto render       # build to _site/
npm install         # dev tooling (prettier, husky, commitizen)
npm run format      # format sources
```

## Deployment

Pushing to `main` triggers `.github/workflows/quarto-publish.yml`, which lints, renders,
optimises, checks for dead links and deploys to GitHub Pages.

## Contributing

Corrections and better tools are welcome — open an
[issue](https://github.com/DHBern/dh-lab/issues/new/choose) or a pull request. See
[CONTRIBUTING.md](CONTRIBUTING.md) and the [Code of Conduct](CODE_OF_CONDUCT.md).

## Licence

- Text and teaching materials: [CC BY-SA 4.0](LICENSE-CCBYSA.md)
- Code: [AGPL-3.0](LICENSE-AGPL.md)
