# Albert Zorzolan

First-year business student at Babson College. I'm learning CS and math on the side and I'm interested in neuroscience and health tech. I build apps with AI coding tools.

## Projects

### Mendr: iOS app, live on the App Store
A morning check-in app. You log the night before and how you slept and feel, Mendr shows what tends to come before your better mornings, and you can check in with friends each day.

- Swift and SwiftUI, Apple Health, WHOOP and Oura connections, optional AI coach
- Version 1.1.0, October 2026
- [App Store](https://apps.apple.com/app/id6799245609) · the source code is private

### Kinwise: UnivaBio "AI for Human Health" hackathon, October 2026
Built with Neil Shah. A browser app that helps families notice what changes after an older parent starts a new medicine, and turns that into cited questions for the doctor. Everything runs in the browser on fictional data, and the optional AI model runs on your own device.

- TypeScript and Vite, on-device LLM over WebGPU, HL7 FHIR R4 export
- A rules engine over a cited knowledge base (427 medicines, 89 AGS Beers Criteria rules) computes every flag; the AI only rewords
- [Live demo](https://albertzorzolan.github.io/UnivaBioBabson/) · [Code](https://github.com/albertzorzolan/UnivaBioBabson/tree/medwatch-v2)
- A prototype. It hasn't been tested with patients, caregivers or clinicians.
