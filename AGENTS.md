# Agent guidance

This Home Assistant integration replays historical entity states to simulate presence. It can turn configured lights, covers, media players, switches, and other entities on or off. Read the README before changing the selected entities, history window, restore behavior, or service options; preserve the documented behavior for multiple simulation switches.

GitHub Actions run Home Assistant hassfest and HACS validation. No local test suite or validation script is tracked. Use those checks when available and report when only source inspection was possible. Do not start or stop a simulation or call its services against a live Home Assistant instance as validation; that changes real entity state and requires explicit authorization.
