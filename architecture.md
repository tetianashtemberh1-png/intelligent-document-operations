# Architecture

`Extracted Document Payload → Webhook → Normalize/Validate → Business Rules + Fingerprint → Downstream Record → Human Review Gate → Response`

Invalid payloads follow a controlled HTTP 400 branch. The tested reference begins after extraction and does not falsely claim OCR execution.
