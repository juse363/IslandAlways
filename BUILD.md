# Build instructions

The workflow `Build VisibleIsland (baseline)` is configured in `.github/workflows/build.yml`.

To start a build:
1. Open https://github.com/juse363/IslandAlways/actions
2. Select **Build VisibleIsland (baseline)**.
3. Choose **Run workflow** on the `main` branch.

If successful, download the `visibleisland-deb` artifact from the completed run.

This first pass builds the upstream VisibleIsland source without claiming iOS 27.2 compatibility. The upstream tweak targets older iOS versions; the package must not be installed on the target phone until injection compatibility and device behavior have been independently verified.
