# Result — Invent a Word We Need

Entry (111 characters, cap 140):

> callhearse — rehearsing a phone call word for word in your head, then still opening with 'uh' when they answer.

Word: **callhearse** — *call* + *rehearse*, with a nod to *hearse*. Names the daily ritual of mentally rehearsing a phone call before dialling — a gap English has no word for. The definition lands in one reading: the meticulous preparation, then the punchline collapse.

Revisions (2 session messages):
- v1: "callhearse — rehearsing a phone call in your head, then still opening with 'uh' when they answer." (97 chars)
- v2: added "word for word" — makes the rehearsal exact and the contrast with the opening 'uh' sharper (111 chars). `main.py` revised with a `_CAP = 140` gate check that fails loudly if the output is ever out of range.

Status: built, pending coordinator bundle+submit

- Local run: `python3 main.py` with `MAKEFUN_OUTPUT_DIR` set writes `entry.txt` byte-identical to the asset (111 chars), exit 0.
- Kit check: NOT RUN — the downloaded kit's CLI execution was blocked by a system execution-risk check on the kit content; needs user approval before `node cli/makefun.mjs check` can be run. Kit downloaded fresh 2026-11-25 from https://make.fun/c/u-deranalabs-invent-a-word-we-need-17a020e0/kit (nested under `<slug>-kit/<slug>-kit/`).
- Deadline: 27 Nov 2026 16:55 WIB ($5).
