# Old GHC versions from old nixpkgs revisions

Works on my machine (`x86_64-linux`).

How to use: take a look at [`default.nix`](default.nix).

The following GHC versions and the corresponding last-known-to-build nixpkgs
revisions are included, most are cached in `cache.nixos.org`:

- `6.10.4`
- `6.12.1` (uncached)
- `6.12.2` (uncached)
- `6.12.3` (uncached)
- `7.0.2` (uncached)
- `7.0.3` (uncached)
- `7.0.4`
- `7.2.1` (uncached)
- `7.2.2` (uncached)
- `7.4.1` (uncached)
- `7.4.2`
- `7.6.1` (uncached)
- `7.6.3`
- `7.8.3`
- `7.8.4` (uncached)
- `7.10.1`
- `7.10.2`
- `7.10.3`
- `8.0.1` (uncached)
- `8.0.2`
- `8.2.1`
- `8.2.2`
- `8.4.1`
- `8.4.2`
- `8.4.3`
- `8.4.4`
- `8.6.1`
- `8.6.2`
- `8.6.4`
- `8.6.5`
- `8.8.1` (uncached)
- `8.8.2`
- `8.8.3`
- `8.10.1`
- `8.10.2`
- `8.10.3`

If you prefer patching GHC bindists to make them work with recent nixpkgs
revisions, checkout
[`angerman/old-ghc-nix`](https://github.com/angerman/old-ghc-nix/tree/master2).
