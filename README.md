# Calque

Offline MS Office translator for macOS — runs entirely on Apple Silicon, no documents leave your Mac.

**Status:** in active development, targeting the Mac App Store.

→ [calque.kleptsov.com](https://dkleptsov.github.io/calque/)

## What it is

Calque opens `.docx`, `.xlsx`, and `.pptx` files, translates the text in place,
and writes back a fully formatted Office document — preserving styles, tables,
images, and headers/footers. Translation happens on-device using a quantised
local LLM (Hy-MT 1.5, 1.25-bit). Network is never used at inference time.

## Why

Cloud translators (DeepL, Google Translate, ChatGPT) upload entire documents
to remote servers. For contracts, financials, medical records, and any
PII-bearing material, that's a non-starter. Calque runs the model locally.

## Distribution

Mac App Store, sandboxed and notarised. Apple Silicon (M1+) only.

## License

MIT — see [LICENSE](./LICENSE).
