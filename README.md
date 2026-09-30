# Shep Shep Package Listing

[![Add to VCC](https://shep-shep.github.io/vpm/badges/add-to-vcc.svg)](https://shep-shep.github.io/vpm/) [![Buy me a coffee](https://shep-shep.github.io/vpm/badges/buy-me-a-coffee.svg)](https://shepshep.gumroad.com/coffee)

Free tools for VRChat creators, delivered through ALCOM or the VRChat Creator Companion.

**Add it:** open [shep-shep.github.io/vpm](https://shep-shep.github.io/vpm/) and press **Add to VCC**, or add `https://shep-shep.github.io/vpm/index.json` under Settings > Packages > Add Repository.

## Adding a package

Each package lives in its own public repository with a release workflow that attaches the package zip and `package.json` to each release. Add the repository to `githubRepos` in `source.json` and push to `main`. The Build Repo Listing workflow rebuilds the listing and this page.

After a new release, run Build Repo Listing again (Actions tab, or push to `main`) so the listing picks it up.

Shared README badges live in `Website/badges/`. They are shields.io badges with the text recoloured to `#121212`, because shields.io picks white text on orange.

Built from VRChat's [package listing template](https://github.com/vrchat-community/template-package-listing).
