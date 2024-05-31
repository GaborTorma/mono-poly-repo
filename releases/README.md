## Folder of packages published on GitHub Packages or not published

### Add a release with `git submodule`

`git submodule add {{repo-url}} {{releases/release-name}}`

#### Example:

Add `git@github.com:GaborTorma/mpr-release1.git` release to `releases/release1` folder:

```bash
git submodule add git@github.com:GaborTorma/release1.git releases/release1
```

#### Example with specific branch:

Add `git@github.com:GaborTorma/mpr-release1.git` release `dev` to `releases/release1` folder:

```bash
git submodule add --branch dev git@github.com:GaborTorma/release1.git releases/release1
```

### Add to the poly-repo-manager

```bash
git add .gitmodules releases/release-name
git commit -m "releases(add): release-name"
```

#### Example:

Add `releases/release1` to the poly-repo-manager:

```bash
git add .gitmodules releases/release1
git commit -m "releases(add): release1"
```

<span style="color:orange"> ⚠️ **Avoid ignore message!**</span>
