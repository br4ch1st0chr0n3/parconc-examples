# Parallel and Concurrent Programming in Haskell. Code

This is the sample code to accompany the book Parallel and Concurrent Programming in Haskell (Simon Marlow, O'Reilly 2013).

There are two types of packages: 

1. For ones from [ghc-8.10.7](ghc-8.10.7/), I managed to enable HLS via [GHCup](https://www.haskell.org/ghcup/).
    * You can build everything there with `stack`:
        ```sh
        cd ghc-8.10.7
        stack build
        ```
    * To run a specific `exe`, use, e.g. `stack exec parmonad-exe`. See [package.yaml](ghc-8.10.7/package.yaml) for the list of available executables

2. Packages from [ghc-old](ghc-old) are quite outdated. I hope they still can be run by following the instructions from the original readme and the book