---
"react-native-reanimated-carousel": patch
---

Settle on the nearest page when a `snapMode="page"` drag is released at rest, instead of springing back to the starting page.
- Flicks, and a flick back toward the starting page, behave as before.
