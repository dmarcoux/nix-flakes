# <a href="https://github.com/dmarcoux/nix-flakes">dmarcoux/nix-flakes</a>

When contributing to open-source projects, I need to have a development
environment to avoid littering my computer with all kind of junk.

For open-source projects with a development environment which isn't
reproducible, I prefer to rely on [Nix](https://github.com/NixOS/nix)
[Flakes](https://nixos.wiki/wiki/Flakes). For all those projects, I store their
development environment setup with Nix Flakes in this Git repository. Each
directory is named after its project and contains the usual Nix Flakes files.
Eventually, I prefer to push this upstream, but it isn't always something
maintainers want.

## Usage

From within a project's Git repository, launch a development environment with:
```bash
nix develop ./path/to/this/repository/project_name/
```
