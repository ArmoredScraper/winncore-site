# Release Transparency

| Version | Date | SHA256 | Sig | SBOM |
|--------:|------|--------|-----|------|
| v0.1.0  | TBA  | TBA    | TBA | releases/v0.1.0.spdx.json |

## Verify
```bash
VER=v0.1.0
curl -O https://www.winncore.com/releases/winncore-$VER.tar.gz
curl -O https://www.winncore.com/releases/winncore-$VER.tar.gz.sig
curl -s https://www.winncore.com/.well-known/pgp.txt | gpg --import
gpg --verify winncore-$VER.tar.gz.sig winncore-$VER.tar.gz
sha256sum winncore-$VER.tar.gz
```
