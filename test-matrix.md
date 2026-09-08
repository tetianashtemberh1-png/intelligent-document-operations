# Test Matrix

| Case | Expected status | Evidence |
|---|---|---|
| Clean invoice | AUTO_READY | arithmetic reconciles |
| Exception invoice | Human review | mismatch + invalid date + high value + low confidence |
| Purchase order | AUTO_READY | structured record |
| Form | AUTO_READY | supported document |
| Invalid invoice | HTTP 400 | validation errors |
