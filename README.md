# Neovim Configuration Flake

Neovim configuration flake (ft. nixvim).

[Screenshot](./screenshots/neovim.png)

# Features

|                            |                                          |
|----------------------------|------------------------------------------|
| Highlights                 | `treesitter`                             |
| Buffers                    | `bufferline`                             |
| Explorer                   | `nvim-tree`                              |
| Find                       | `telescope`                              |
| Icons                      | `web-devicons`                           |
| Colorscheme                | `nord`                                   |
| LSP                        | `nixd` `pyright` `rust-analyzer`         |
| Formatting                 | `nixfmt` `black` `isort` `rustfmt`       |
| Completions                | `nvim-cmp`                               |

# Usage

```
$ nix run github:sotormd/neovim
```

For use in another flake, add `neovim.url = "github:sotormd/neovim";` to your inputs.

This provides `neovim.packages.x86_64-linux.default` and `neovim.packages.aarch64-linux.default`.
