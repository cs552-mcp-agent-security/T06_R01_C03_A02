# Contributing

Three rules:

1. **Keep `lib/data/` free of Flutter imports.** That layer is pure-Dart so it
   can be reused on the web build.
2. **Run `flutter analyze` before opening a PR.** It catches 90% of regressions.
3. **No new third-party packages in `pubspec.yaml`** without a one-line note
   in the PR description explaining why.

## Reporting issues

Use the bug-report template under `.github/ISSUE_TEMPLATE/`. Include the
Flutter SDK version (`flutter --version`) and the target (android / ios / web).
