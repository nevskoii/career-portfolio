# Aleksandr Korshunov — Career Portfolio

[Open portfolio](https://nevskoii.github.io/career-portfolio/)

A compact, recruiter-oriented **single-page professional profile** with four linked areas of expertise and the full approved CV.

## Main page

- Profile, experience and contact details
- Four expertise cards with a concise hover description and one **Read more** link each
- Full CV text from the approved `CV_4_0-4.pdf`
- Direct PDF downloads of the original CV and separate cover letter
- Signed employer recommendation next to Rostelecom experience

## Expertise notes

Each area has its own professional notes page. Risk & Controls contains the full case study directly; additional projects and notes can be added to these area pages.

| Area | Page |
|---|---|
| Risk & Controls | [Open](https://nevskoii.github.io/career-portfolio/expertise/risk-controls/) |
| Audit & Assurance | [Open](https://nevskoii.github.io/career-portfolio/expertise/audit-assurance/) |
| Financial Analysis & Modelling | [Open](https://nevskoii.github.io/career-portfolio/expertise/financial-analysis/) |
| Data Analytics | [Open](https://nevskoii.github.io/career-portfolio/expertise/data-analytics/) |

The Risk & Controls case study is now integrated into [the Risk & Controls page](https://nevskoii.github.io/career-portfolio/expertise/risk-controls/) instead of being a separate project page. The old `/projects/risk-control-framework/` URL redirects to this page.

## PDF files (uploaded and linked)

- `assets/CV_Aleksandr_Korshunov.pdf` — exact approved CV, direct download
- `assets/Aleksandr_Korshunov_Cover_Letter.pdf` — cover letter, direct download
- `assets/Recc_Letter_Aleksandr_Korshunov.pdf` — signed employer recommendation, direct download

All three PDF files are present in the repository. The CV and cover letter match the original local files by Git blob SHA-1.

## Control diagrams

The Risk & Controls article is ready to show the two user's original maps directly below the introduction when these image files are added to the `main` branch:

```
assets/images/business-control-mindmap-en.PNG
assets/images/data-centre-control-mindmap-en.jpg
```

The two maps have not yet been uploaded to GitHub. The page detects image availability and hides unavailable images, so there are no broken previews. Source images are currently 1536×1024 pixels; a vector redraw is recommended for print-ready and zoomable typography. Both diagrams should preserve their existing control-category taxonomy and be proofread against the originals. The synthetic Excel RCM is not yet included.

## Site architecture

Static HTML/CSS/JavaScript, no build step. GitHub Pages serves from the `main` branch root. Old URLs `/cv/`, `/about/`, `/projects/` and `/expertise/` redirect to the main portfolio rather than duplicating its content.

## Privacy

Public case studies summarise professional outcomes and use illustrative controls; they do not disclose confidential employer risk registers, client records or audit working papers.
