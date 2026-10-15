# PDFCraft-IN

PDFCraft-IN is an independent fork of the open-source [PdfCraft](https://github.com/storytold/pdfcraft) project, focused on document redaction workflows used in India.

## Changes in this fork

- Detects PAN, Aadhaar, GSTIN, Indian mobile numbers, UPI IDs, IFSC codes, Indian passport numbers, voter IDs, and CINs.
- Retains email, payment-card, and IP-address detection.
- Adds **Redact a PDF → Find text and redact → Patterns → All India-sensitive data**, which marks every supported sensitive identifier in one pass.

Always review marked regions before choosing **Apply redactions** and saving the document. Applying redactions permanently removes the selected content.

## Upstream and licensing

This repository contains modifications to PdfCraft. PdfCraft remains the upstream project; see its repository for the complete application, documentation, and development history.

PDFCraft-IN is distributed under the upstream dual licence: MIT OR Apache-2.0. The upstream copyright notices, licences, and required third-party notices are retained in [LICENSE-MIT](LICENSE-MIT), [LICENSE-APACHE](LICENSE-APACHE), and [NOTICE](NOTICE).

## Independence and provenance

PDFCraft-IN is independently maintained. Its interface assets and documentation use only contributor-created or appropriately licensed material. The repository retains third-party notices where licences require them.
