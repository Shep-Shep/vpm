# Shep Shep Package Listing

Free tools for VRChat creators, delivered through ALCOM or the VRChat Creator Companion.

**Add it:** open [shep-shep.github.io/vpm](https://shep-shep.github.io/vpm/) and press **Add to VCC**, or add `https://shep-shep.github.io/vpm/index.json` under Settings > Packages > Add Repository.

## Adding a package

Each package lives in its own public repository with a release workflow that attaches the package zip and `package.json` to each release. Add the repository to `githubRepos` in `source.json` and push to `main`. The Build Repo Listing workflow rebuilds the listing and this page.

After a new release, run Build Repo Listing again (Actions tab, or push to `main`) so the listing picks it up.

Built from VRChat's [package listing template](https://github.com/vrchat-community/template-package-listing).
