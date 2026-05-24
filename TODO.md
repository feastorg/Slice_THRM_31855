# TODO

## Pass 1 — CI Pipeline

- [x] Pipeline added and passing (all jobs green)
- [x] DRC: PASS
- [x] ERC: PASS
- [x] Fab: PASS
- [x] gen-kibot-index: PASS
- [x] deploy-pages: PASS

## Pass 2 — Pre-Fab Review

- [ ] Verify BOM completeness and sourcing
- [ ] Confirm board outline and mounting holes
- [ ] Footprint verification against datasheets
- [ ] Design review sign-off

## Notes

- Firmware uses `max6675.h` library but hardware schematic uses MAX31855K — update firmware to use `Adafruit_MAX31855` or verify pin-compatibility and document
- Fill in `docs/architecture.md` (currently template placeholders)
