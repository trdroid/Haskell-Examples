**Working interactively with Glasgow Haskell Compiler (GHC)**

Start GHC's interactive mode

```sh
$ ghcii.sh
GHCi, version 8.0.1: http://www.haskell.org/ghc/  :? for help
Prelude>
```

To change the prompt to "ghci> ", do the following

```sh
Prelude> :set prompt "ghci> "
ghci>
```

To avoid doing this every time GHCi is run, save the command *:set prompt "ghci> "* in a file called .ghci in the home directory.

