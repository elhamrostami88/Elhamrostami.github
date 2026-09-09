# Adaptation notes — Aref Einizade

This project preserves the Quarto structure, visual system (`styles.scss`), responsive layout, navbar/search, generated publication/news/team/teaching cards, SEO schema, and GitHub Pages workflow of the supplied website, while replacing the identity and academic content with Aref Einizade's public information.

## Public sources used

- Current website: https://arefeinizade.github.io/
- Current CV linked from that website: https://arefeinizade.github.io/img/Job_CV_Aref_EINIZADE.pdf
- ORCID shown in public scholarly indexes: https://orcid.org/0000-0002-8546-7261
- DBLP: https://dblp.org/pid/299/0292.html
- GitHub: https://github.com/ArefEinizade2
- LinkedIn: https://fr.linkedin.com/in/aref-einizade-4793b785

## Important choices

- Aref's portrait and CV are linked to their current public URLs rather than copied into the repository.
- Jhony-specific course notes, lecture PDFs, job-opening PDF, portrait, and CV were removed to avoid misattribution.
- The Teaching page retains the same card-based design but uses Aref's documented teaching activities.
- The Team page retains the same framework but only lists supervision records explicitly present on Aref's public website. No current group members were invented.
- Publications include Aref-related records already present in the supplied Jhony bibliography plus the older publication list from Aref's current website.

## Recommended manual checks before deployment

1. Replace the Google Scholar search link in `_quarto.yml` and `publications/index.qmd` with Aref's exact Scholar profile URL if desired.
2. Confirm the preferred office/postal address for the portrait card.
3. Add current students/team members to `_data/people.json` when available.
4. Add DOI/code/project links to older publications in `_bibliography/papers.bib` as desired.
5. If you want the portrait and CV self-hosted, download them into `assets/images/` and `assets/pdf/` and update the links.
