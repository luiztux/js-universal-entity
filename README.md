# Universal Entity Format

The open, forever-compatible file format that will replace 99 % of websites.

`.entity` = one tiny file (< 5 KB) you send by WhatsApp, AirDrop, QR code, NFC…  
The receiver taps → instantly sees a beautiful, always-up-to-date card (menu, schedule, prices, booking, payment)  
No app needed. No website. No SEO. No hosting.

This is the JPG of digital entities.

## Why now?
- 2025–2028: Apple, Google and Microsoft are each creating their own closed formats  
- We are building the open one — royalty-free, community-driven, future-proof

 Goal: become the vCard of the 2030s — but live, rich and transacional.

 Repo layers
- `schema/` → the official JSON Schema (v1 coming soon)  
- `examples/` → real .entity files you can send today  
- `viewer/` → 15 KB PWA that opens any .entity file (drag & drop)

 Try it now
1. Download examples/pizzaria-italia.entity  
2. Open https://js-universal-entity.github.io/viewer  
3. Drag the file → magic

 Roadmap
- v1.0 → binary header (8 bytes magic) for true native detection  
- 2026? → Rust/WASM parser < 300 lines  
- 2027? → submit Internet-Draft @ IETF  
- 2030? → natively opened by iOS, Android and Windows file managers

License: MIT

Made with love in Brazil
