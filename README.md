# MCQs001 — V6

A static, mobile-first MBBS MCQ study app built from the supplied 12,004-question workbook.

## V6
- Brand: MCQs001
- Header identity: Rama-001 + EQB
- Homepage copy updated to the personal/student style requested.
- Removed the old global Review tab.
- Removed chapter day-streak display and the separate chapter Analytics button.
- Subject → chapter screen now shows a compact chapter list; each chapter expands on tap.
- Expanded chapter gives the four main study choices: All, Unanswered, Wrong, Saved.
- Accuracy is compact secondary information.
- Added green Answers mode for rapid revision with answers already revealed.
- Answers supports subject + chapter selection and chapter-wise answers-seen coverage.
- Added Review Unseen First / Continue behaviour.
- Home replaces the old second mock action with Answers; Mock remains in bottom navigation.
- Preserves the existing `mbbs_state_v2` local storage key so existing progress/bookmarks are retained.
- Copy-to-clipboard uses Clipboard API with a browser fallback.
- Added clickable `Feedback: sairama.exe` Instagram link.
- Added V6 PWA manifest/service worker and keeps the personalized icon set.

## Source
Questions are from the supplied JNMC Electronic Question Bank (EQB) workbook. The app is a personal study interface and is not presented as an official JNMC product.

Deploy as a static site to Vercel/Netlify. No build command is required.
