# homebrew-hgit

Homebrew tap for [hgit](https://github.com/VectorSophie/hgit) - version control
for TempleOS, shipped as a pre-loaded TempleOS disk image that runs under QEMU.

```sh
brew install VectorSophie/hgit/hgit
hgit --help
hgit            # boots the bundle in QEMU and loads hgit
```

Dependencies (`qemu`, `python@3`) are installed by Homebrew. The formula is
generated from the main repo (`tools/render-packaging.sh`); update it there.
