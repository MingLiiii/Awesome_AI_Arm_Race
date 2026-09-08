# 🤝 Contributing

Thank you for helping improve this reading guide. We welcome relevant papers, corrections, and verified links.

## 📚 Trusted BibTeX only

**We do not accept BibTeX entries generated, reconstructed, or completed by AI tools, including entries produced through AI-assisted search.** An AI tool's claim that a citation has been verified is not a substitute for an original export.

For research papers, submit BibTeX **exported directly from one of these trusted sources**:

- **Google Scholar** — use the paper's citation export.
- **The publisher's official website** — use its BibTeX citation export.
- **arXiv** — use the paper's BibTeX citation export.

Preserve the exported bibliographic fields. Do not ask an AI tool to fill in missing authors, dates, venues, DOIs, or arXiv identifiers. If an export appears incomplete or incorrect, flag the issue and provide the source for maintainers to check; do not silently rewrite the record. If no trusted export is available, contact the maintainers before proposing a bibliography addition.

## 🔗 Submit links separately

Provide the **paper link separately from the BibTeX block**, even when the exported entry already contains a `url` or `doi` field. Also provide the page from which the BibTeX was exported so maintainers can check its origin.

- **BibTeX source:** the Google Scholar record, publisher citation page, or arXiv record used for the export.
- **Paper:** a verified DOI landing page, publisher page, arXiv page, official proceedings page, or OpenReview record.
- **Code / Project (optional):** a separately labeled official repository or project page.

Match the title and authors before submitting any link. If the online title has changed, explain how you confirmed that it is another version of the same work. Do not provide guessed URLs or AI-generated links.

## 📨 Contribution format

Include the proposed reading-list category, the original BibTeX export, and the links as separate items in your issue or pull request:

````markdown
### Paper and category
Title: [paper title]
Category: [proposed Part / category]

### Original BibTeX export
```bibtex
% Paste the BibTeX exported directly from Google Scholar,
% the publisher's official website, or arXiv here.
```

### Links
- BibTeX source: [URL of the record used for the export]
- Paper: [verified paper URL]
- Code / Project (optional): [official URL]

### Notes (optional)
[Explain any title/version differences or metadata concerns.]
````

## 🗂️ Collection scope and README format

`main.bib` remains the source of truth for **which works belong in the collection**. New works must be reviewed and included in the survey bibliography before they are added to the README. Providing a trusted export does not automatically establish that a paper is in scope.

For corrections, identify the paper by title and its BibTeX key, retained in an HTML comment above each README entry. Keep each reference in one main category, sorted by year (newest first), then title. Keep institutional records separate from research papers.

Once approved, use the existing README display format:

```markdown
<!-- bib:existing_citation_key -->
- **[Paper title](https://verified-primary-source/paper)**  
  `2026` · Venue · First-author surname et al.
```

Use the actual year and venue. Omit “et al.” for a single author. For institutional records, use `Official record` as the label and retain the institutional author. Keep the bibliography's publication status unless the source record has been checked and the bibliography intentionally updated.

Do not add unsupported summaries, generated ratings, invented publication metadata, or unverified code/project links. If an existing link cannot be confirmed, flag it rather than guessing a replacement.

This is a Markdown reading-list repository. No build step, dependency installation, or link-checking script is required.
