# kasa (嵩)

Standalone Etzhayyim observatory for public computing-capacity growth statistics.
It records historical and present measurements, derives transparent growth rates,
and never forecasts or adjudicates.

EDN under `manifest.edn`, `contracts/`, and `data/` is canonical. External lexicon
and DID JSON is isolated under `wire/`. Runtime namespaces and tests live under
`src/kasa` and `test/kasa`. Run the comprehensive suite with `bb test`.

Go, TinyGo, Python twins, shell runners, and legacy JSON-LD manifests are prohibited.
