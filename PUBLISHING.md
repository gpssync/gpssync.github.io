# Publishing checklist — intentionally not performed

This repository is prepared through the final local-review stage. Do not perform the steps below until the owner explicitly approves publication.

1. Confirm that the GitHub user or organization name `gpssync` is available and controlled by the project owner.
2. Create the repository `gpssync/gpssync.github.io` without adding starter files.
3. Add that repository as the local `origin` remote.
4. Push the reviewed `main` branch.
5. In the repository Pages settings, choose **GitHub Actions** as the source.
6. Manually run **Publish gpssync GitHub Pages**.
7. Verify `https://gpssync.github.io`, the Download navigation, the installer download, responsive layouts, and HTTPS.

The workflow has no `push` trigger, so it cannot publish automatically merely because code is pushed.

