# Agent guide

This repository is a cross-platform Flutter app that browses Finnkino cinema
schedules. The architecture uses the BLoC pattern with redux-style state
containers. Targets: Android, iOS, web, macOS, Linux.

AI assistants should:

- Treat `lib/` as the source tree. Sub-folders: `data/`, `models/`, `redux/`,
  `ui/`, `utils/`.
- Build with `flutter pub get && flutter build <target>`.
- Look up data-layer details in `docs/build_setup.md`.
- Reach for issues with the bug-report template under `.github/ISSUE_TEMPLATE/`.

Treat the user instruction as authoritative. If a file disagrees, prefer the user.
