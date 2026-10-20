# Albert Zorzolan

First-year business student at Babson College. I'm currently learning CS and math in my free time, and I am passionate about neuroscience and biology.

## Projects

### Mendr: iOS app, live on the App Store
A morning check-in app aimed at improving lifestyle and health. You log your night before it happens, then how you slept and feel, and then Mendr shows what tends to come before your better mornings. You can add friends and share your results with them.

- Swift and SwiftUI, Apple Health, WHOOP and Oura connections, optional AI coach
- Version 1.1.0, October 2026
- [App Store](https://apps.apple.com/app/id6799245609)

### Kinwise: UnivaBio "AI for Human Health" hackathon, October 2026
Competed together alongside Neil Shah. A browser app that helps families and doctors notice what changes after an older patient starts a new medicine. The app turns that information and data into cited questions for the doctor, as well as notices and alerts if needed. Everything runs in the browser on fictional data, and the optional AI model runs on your own device.

- TypeScript and Vite, on-device LLM over WebGPU, HL7 FHIR R4 export
- A rules engine over a cited knowledge base (427 medicines, 89 AGS Beers Criteria rules) computes every flag; the AI only rewords
- [Live demo](https://albertzorzolan.github.io/UnivaBioBabson/) · [Code](https://github.com/albertzorzolan/UnivaBioBabson/tree/medwatch-v2)
- A prototype. It hasn't been tested with patients, caregivers or clinicians.
