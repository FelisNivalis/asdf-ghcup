# asdf-ghcup

## Requirements

- [ghcup](https://www.haskell.org/ghcup/)

## Supported Tools

Here is a list of all supported tools:

### [cabal](https://www.haskell.org/cabal/)

> Cabal is a system for building and packaging Haskell libraries and programs.
> It defines a common interface for package authors and distributors to easily
> build their applications in a portable way. Cabal is part of a larger
> infrastructure for distributing, organizing, and cataloging Haskell libraries
> and programs.

```
asdf plugin add cabal https://github.com/sestrella/asdf-ghcup.git
```

### [ghc](https://www.haskell.org/ghc/)

> GHC is a state-of-the-art, open source, compiler and interactive environment
> for the functional language Haskell.

```
asdf plugin add ghc https://github.com/sestrella/asdf-ghcup.git
```

### [hls](https://github.com/haskell/haskell-language-server)

> Official haskell ide support via language server (LSP). Successor of ghcide &
> haskell-ide-engine.

```
asdf plugin add hls https://github.com/sestrella/asdf-ghcup.git
```

### [stack](https://docs.haskellstack.org/en/stable/README/)

> Stack is a cross-platform program for developing Haskell projects. It is
> aimed at Haskellers both new and experienced.

```
asdf plugin stack hls https://github.com/sestrella/asdf-ghcup.git
```
