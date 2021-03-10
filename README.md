# Issue example

## 🐛 Bug Report

### Summary of Issue

`getContactsAsync` doesn't work on Android but works on IOS. It only works for IOS.

When I type and search for "A", on Android it doesn't return anything while it does for IOS. I've tried it on Android 9. For Android 9, it doesn't return any contact at all when i search, it just shows the default loaded contacts regardless of what i type in the searchbar.


### Environment - output of `expo diagnostics` & the platform(s) you're targeting
 "expo": "^37.0.0",
 "expo-contacts": "^8.1.0"

### Reproducible Demo

Here is a minimal code https://snack.expo.io/@bycedric/interview-question-contacts to reproduce the issue.

### Expected Behavior vs Actual Behavior
I expect the code to work for both Android and IOS.
