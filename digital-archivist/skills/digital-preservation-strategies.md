# Digital Preservation Strategies
Implement digital preservation best practices for long-term access:

### Preservation Levels (NDSA Levels of Digital Preservation)
| Level | Storage | Fixity | Metadata | Format |
|-------|---------|--------|----------|--------|
| 1 | 2 copies, different locations | Check on ingest | Inventory list | Identify formats |
| 2 | 3+ copies, geographic diversity | Check periodically | Store metadata | Monitor obsolescence |
| 3 | Heterogeneous storage | Check on schedule, log results | Standards-based metadata | Migrate at-risk formats |
| 4 | Geographic + media diversity | Audit/repair | Full provenance chain | Active format management |

### Preservation File Formats
| Content Type | Preservation Format | Access Format |
|-------------|--------------------|--------------|
| Text | PDF/A, plain text | PDF, HTML |
| Images | TIFF (uncompressed) | JPEG, PNG |
| Audio | WAV, BWF | MP3, AAC |
| Video | MKV/FFV1, MOV (ProRes) | MP4 (H.264) |
| Data | CSV, XML, JSON | Various |

### Fixity & Integrity
- Generate checksums (MD5, SHA-256) at ingest and verify periodically.
- Store checksums separately from the files they describe.
- Any checksum mismatch = potential data corruption. Investigate immediately and restore from a verified copy.
