# Fire Service Mental Health Research

A working library of research on suicide and mental health in the fire service, collected as groundwork for a future ExpectFire study.

## Contents

- `papers/` holds copies of source documents.
- `REFERENCES.md` is an annotated bibliography of related work, with DOIs or links.

## Coverage

`REFERENCES.md` currently has 26 entries, grouped by topic:

| Topic | What it covers |
| --- | --- |
| Surveillance and mortality | Florida counts, NIOSH proportionate mortality, New York cohort rates, Ruderman white papers |
| Prevalence | Ideation, plans, and attempts: reviews, meta-analysis, and national surveys |
| Risk factors and mechanisms | Alcohol, PTSD, social disconnectedness, wildland firefighters, critical incident exposure |
| Subgroups | Volunteer vs. career, retired, and women firefighters |
| Lethal means safety | Firefighter and EMS firearm storage, plus adjacent military trials |
| Peer support and prevention programs | Training evaluations and cross-sectional peer support findings |
| Culture and care | Occupationally competent care |

Known gaps (no firefighter study found): peer support trials with suicide outcomes, before and after retirement cohorts, and sleep or shift work as a pathway to risk. The last section of `REFERENCES.md` lists the next searches.

## Papers

| File | Source |
| --- | --- |
| `papers/Florida_Fire_Service_Suicide_Data_Final_June2026.pdf` | O'Dare K, Winch A, Beidel DC, et al. *Suicide Deaths among Florida Fire Service Personnel, January 1, 1999 through March 1, 2026.* UCF RESTORES, June 2026. [Original](https://ucfrestores.com/wp-content/uploads/sites/61/2026/06/Florida_Fire_Service_Suicide_Data_Final-June2026.pdf) |

Preprints under a CC BY license (not the final published versions, so cite the journal article):

| File | Source |
| --- | --- |
| `papers/preprints/Park_2019_Korean_firefighters_ideation_preprint.pdf` | Park H, et al. Research Square preprint of the *BMC Psychiatry* 2019 article. doi:[10.21203/rs.2.12082/v2](https://doi.org/10.21203/rs.2.12082/v2) |
| `papers/preprints/Gallyer_2018_alcohol_SI_preprint.docx` | Gallyer AJ, et al. PsyArXiv author manuscript (Word file) of the *J Affect Disord* 2018 article. doi:[10.31234/osf.io/f4unb](https://doi.org/10.31234/osf.io/f4unb) |

## PDFs still to add

Publisher sites block scripted downloads, so these need to be saved by hand from a browser and dropped into `papers/` (see "Adding research"). The first three are open access under Creative Commons licenses and can be redistributed:

- Vigil 2021, *West J Emerg Med* (CC BY): [PMC7972356](https://pmc.ncbi.nlm.nih.gov/articles/PMC7972356/)
- Tahernejad 2026, *Public Health in Practice* (CC BY-NC-ND): [PMC12776000](https://pmc.ncbi.nlm.nih.gov/articles/PMC12776000/)
- Kim 2025, *Eur J Psychotraumatol* (CC BY-NC): [PMC12210409](https://pmc.ncbi.nlm.nih.gov/articles/PMC12210409/)

Free to read but with no redistribution license (link only, do not commit): Stanley 2024 ([PMC10689572](https://pmc.ncbi.nlm.nih.gov/articles/PMC10689572/)), Career vs. volunteer 2021 ([PMC9195594](https://pmc.ncbi.nlm.nih.gov/articles/PMC9195594/)), Wagner 2021 ([Griffith repository](http://hdl.handle.net/10072/401266)).

Paywalled: the remaining entries in `REFERENCES.md`. Get these through a library or the authors, and check the license before committing a copy.

## Notes on use

- The documents in `papers/` belong to their authors and publishers. They are kept here for reference. Cite the original source, not this repo.
- Most figures in this field are counts, not rates, and study designs differ (surveillance counts, proportionate mortality, cohort SMRs, convenience-sample surveys). Do not compare numbers across studies without checking the denominator and sample.
- Entries in `REFERENCES.md` are marked by how they were checked. Verify against the original paper before quoting any figure in a publication.

## Adding research

1. Put the PDF in `papers/` (open-access or permitted copies only) using `Author_Year_ShortTitle.pdf`.
2. Add an entry to `REFERENCES.md` with full citation, DOI or URL, design, sample, and a one-line takeaway.
3. Commit with a message naming the paper.
