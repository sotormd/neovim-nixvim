# Neovim Configuration Flake

Neovim configuration flake (ft. nixvim).

![Screenshot](./screenshots/neovim.png)

# Features

|                            |                                          |
|----------------------------|------------------------------------------|
| Highlights                 | `treesitter`                             |
| Buffers                    | `bufferline`                             |
| Explorer                   | `nvim-tree`                              |
| Find                       | `telescope`                              |
| Icons                      | `web-devicons`                           |
| Colorscheme                | `nord`                                   |
| Languages                  | `nix` `python` `rust` `go` `haskell`     |
| Completions                | `nvim-cmp`                               |

# Usage

```console
$ nix run github:sotormd/neovim-nixvim
```

For use in another flake, add this to your inputs:
- `neovim.url = "github:sotormd/neovim-nixvim";`

This provides the following packages:
- `neovim.packages.x86_64-linux.default`
- `neovim.packages.aarch64-linux.default`
