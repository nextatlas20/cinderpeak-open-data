# Cinderpeak Open Data

Public deposit repository of the Cinderpeak Observatory field programmes.

## Layout

- `candidates/` — one dataset card per deposit awaiting publication review.
  The YAML front matter of a card is the authoritative record of that deposit:
  `dataset`, `steward`, `license`, `records`, `size_mb`, `period_start`,
  `period_end`, `redaction_status` and `checksum_verified`.
- `release-notes/` — release manifests, one file per release train.

## Working rules

Cards are never edited in place once a deposit has been reviewed; the release
desk works on the Publication Register board instead.
