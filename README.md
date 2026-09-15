# alpr-pwa-cdn

Public download mirror for the **Pardava ALPR PWA** — fallback source for the
model / runtime chunks when the primary HuggingFace origin is unreachable.

- `models/chunks/` — ONNX model chunks (plate detector / OCR / vehicle VHF)
- `vendor/ort/chunks/` — ONNX Runtime WebAssembly chunks

Files are served with `Access-Control-Allow-Origin: *` via
`raw.githubusercontent.com` and `cdn.jsdelivr.net`.
