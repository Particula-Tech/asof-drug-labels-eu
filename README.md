# As-of Drug Labels: EU corpus

The English Annex I (summary of product characteristics) of EU centrally authorised products as the European Commission's Union Register carries them, as a git history: one commit per Commission decision whose English Annex I was converted, one folder `<inn>/<EMEA-H-C-nnnnnn>/` per product with `product.json` and one Markdown file per QRD section, one sentence per line. Commit dates are the Commission decision date, never an approval or Official Journal date; the trailers `Source-Id`, `Source-Version`, `Effective-Date`, `Decision-Number`, `Source-URL` and `Source-SHA256` name each commit's source file and `Text-Fidelity` its conversion rule.

Wording is intended to be unchanged; automated conversion from PDF can introduce errors (tables, superscripts, column order, dropped lines). The source file pinned by URL and SHA-256 in each commit is authoritative; where this copy differs from the Annex I PDF published by the European Commission in the Union Register, the official text prevails.

Source: European Commission, Union Register of medicinal products, and the European Medicines Agency (EMA); © European Union, 1995-2026; the Commission content is reused under Commission Decision 2011/833/EU and CC BY 4.0, EMA content with acknowledgement under the EMA legal notice; neither endorses this project. Changes: converted from PDF to Markdown and split into QRD sections. Any rights a marketing authorisation holder may have in the Annex I wording are not licensed by this project and stay with the holder.

Scope, record window, limits and the tools that build this repository are at https://github.com/Particula-Tech/asof-drug-labels; this repository carries no counts or dates of its own.

See `NOTICE.md` for licence terms, the rights-holder and corrections contact, trade marks and the warranty disclaimer. Not medical advice.
