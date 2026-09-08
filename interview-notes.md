# Interview Notes

I built a document-operations workflow that accepts extracted business-document data, validates it, checks invoice arithmetic and operational rules, generates a deterministic fingerprint, creates a downstream-ready record, and routes exceptions to human review. The tested workflow starts after extraction so the portfolio does not falsely claim OCR that was not executed.
