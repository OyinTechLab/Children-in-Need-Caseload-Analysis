# Data Source Note

The dataset used in this project is an **anonymized extract of real local authority data**, structured to match the UK Department for Education (DfE) Children in Need (CIN) census, covering 8 Leicestershire districts.

No raw source file is published in this repo, and the working `Person Id` field is a non-identifying reference generated for this analysis rather than any real-world identifier. This follows standard practice for children's social care data, given the sensitivity of the population involved, and matches the small-cell suppression approach applied throughout the dashboard (see [`../docs/Methodology.docx`](../docs/Methodology.docx)).

If you'd like to inspect the field structure without the underlying records, see the cleaned Excel workbook in [`../excel/`](../excel/), which documents the schema used, or the exact column list in the methodology notes.
