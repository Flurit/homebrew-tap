# Flurit Homebrew tap

```bash
brew install Flurit/tap/applygate
```

Installs [applygate](https://github.com/Flurit/applygate), a deterministic local pre-apply gate for Terraform and OpenTofu, from the signed release archives. Homebrew checks each archive's sha256; the cosign signature on the release's `checksums.txt` is not checked by Homebrew (see the applygate README to verify it).

The formula is maintained in `packaging/homebrew/` of the applygate repository and copied here for each release: bump the version in the four URLs and the four sha256 values from the release's `checksums.txt`.
