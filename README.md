# Neovim Configuration Flake

Neovim configuration flake (ft. nixvim).

# Usage

```
$ nix run github:sotormd/neovim
```

For use in another flake, add `neovim.url = "github:sotormd/neovim";` to your inputs.

This provides `neovim.packages.x86_64-linux.default` and `neovim.packages.aarch64-linux.default`.
