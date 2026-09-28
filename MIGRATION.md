# AUR merge request — submitted, awaiting review

Replacement published: https://aur.archlinux.org/packages/pen-dev-appimage

Version 1.2.14-1 is live under maintainer `mathix`. Both architecture builds
passed locally and in GitHub Actions. Desktop UI launch has not been tested.
The maintainer confirmed submission of the merge request on 2026-09-28.
Acceptance has not yet been verified.

- Request page: https://aur.archlinux.org/pkgbase/pencil-dev-appimage/request
- Type: merge
- Target package: `pen-dev-appimage`

## Request text

Upstream Pencil has been renamed to Pen (https://www.pen.dev/downloads).
The official releases are now published at
https://github.com/highagency/pen-desktop-releases.

Please merge pencil-dev-appimage into pen-dev-appimage, preserving votes and comments.
The replacement packages the same application's official AppImage under
its new name, supports x86_64 and aarch64, and includes automated release updates.
It provides/conflicts with pencil-dev and retains a pencil-dev command alias.

Replacement: https://aur.archlinux.org/packages/pen-dev-appimage
Packaging and CI: https://github.com/mathix420/pen-dev-appimage

## After acceptance

Verify that the old listing has been removed and redirects/references point to
the replacement. This retires the old package; do not submit a redundant deletion
request. If the merge is rejected, review the package maintainer's response before
requesting a separate deletion.
