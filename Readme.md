A small barebones haskell cli clone of the [2048](http://git.io/2048) game.

```
cabal update && cabal install cabal-install
cabal sandbox init
cabal install --only-dependencies
cabal run 2048

cabal run 2048Solver
```

* `w`: go up
* `a`: go left
* `s`: go down
* `d`: go right
