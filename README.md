# Awesome BQN
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

If you have any libraries or projects that you'd like to be put on here,
feel free to issue a pull request!  I'm also active on the `#bqn` channel
on [The APL Farm](https://discord.gg/2x6r6VgAmY) discord.  My username on 
there is `Brian E` if you want to ask me anything.


## IDE/Editors
- [beacon](https://github.com/x86y/beacon), native BQN IDE/REPL
- [bqn-vscode plugin](https://github.com/mk12/bqn-vscode), 
  for those that need a web browser to edit code.
- `vim(1)`, see [here](https://mlochbaum.github.io/BQN/editors/index.html#vim)
- `neovim(1)`, see the [`nvim-bqn`](https://git.sr.ht/~detegr/nvim-bqn) plugin.
- `emacs(1)`, see the [BQN major mode](https://github.com/museoa/bqn-mode).
- [bqnlsp](https://git.sr.ht/~detegr/bqnlsp), an 
  [LSP](https://microsoft.github.io/language-server-protocol/) for BQN. Requires rust.
- [tree-sitter-bqn](https://github.com/shnarazk/tree-sitter-bqn), BQN support for 
  [tree-sitter](https://tree-sitter.github.io/tree-sitter/).
- [bqn-fmt](https://github.com/slotThe/bqn-fmt), a formatter for
  word-based symbol entry. Requires Rust.

## Libraries
- Marshall Lochbaum's [bqn-libs](https://github.com/mlochbaum/bqn-libs), including:
  - [big integers](https://github.com/mlochbaum/bqn-libs/blob/master/bigint.bqn)
  - [big natural numbers](https://github.com/mlochbaum/bqn-libs/blob/master/bignat.bqn)
  - [CSV parser](https://github.com/mlochbaum/bqn-libs/blob/master/csv.bqn)
  - [datetime handler](https://github.com/mlochbaum/bqn-libs/blob/master/datetime.bqn)
  - [hashmaps](https://github.com/mlochbaum/bqn-libs/blob/master/hashmap.bqn)
  - [json parsing](https://github.com/mlochbaum/bqn-libs/blob/master/json.bqn)
  - [matrix math](https://github.com/mlochbaum/bqn-libs/blob/master/matrix.bqn)
  - [Nelder-Mead's simplex method](https://github.com/mlochbaum/bqn-libs/blob/master/min.bqn)
  - [perlin noise generator](https://github.com/mlochbaum/bqn-libs/blob/master/perlin.bqn)
  - [polynomial functions](https://github.com/mlochbaum/bqn-libs/blob/master/polynomial.bqn)
  - [prime numbers](https://github.com/mlochbaum/bqn-libs/blob/master/primes.bqn)
  - [square roots](https://github.com/mlochbaum/bqn-libs/blob/master/roots.bqn)
  - [string functions](https://github.com/mlochbaum/bqn-libs/blob/master/strings.bqn)
  - [xml parsing](https://github.com/mlochbaum/bqn-libs/blob/master/xml.bqn)
- Lochbaum's [BQNoise](https://github.com/mlochbaum/BQNoise) for
  "audio synthesis and processing."
- frasiyav's [BQN-Gnuplot](https://github.com/frasiyav/BQN-Gnuplot), a wrapper
  for GnuPlot
- frasiyav's [BQN-grad](https://github.com/frasiyav/BQN-grad), backpropogation
  library
- MysticalUnicat's [ga_bqn](https://github.com/MysticalUnicat/ga_bqn), geometric
  algebra libraries for BQN
- bddean's [BQNprop](https://github.com/bddean/BQNprop), another backpropogation
  library
- calebowens' [bqn-web-framework](https://github.com/calebowens/bqn-web-framework),
  requires rust
- dlozeve's [bqn-graphics](https://github.com/dlozeve/bqn-graphics), tools for
  generating [PNM](https://netpbm.sourceforge.net/doc/pnm.html) images
- ap29600's [PNM image library](https://github.com/ap29600/bqn-image)
- razetime's [bqn-unit](https://github.com/razetime/bqn-unit), BQN unit testing
- icendoan's [bqn-bindings](https://github.com/icendoan/bqn-bindings),
  miscellaneous bindings for useful C libraries from BQN. Currently some of C stdlib,
  [cURL](https://curl.se/), and [Jansson JSON](https://jansson.readthedocs.io/en/latest/).
- Brian ED's [rayed-bqn](https://github.com/Brian-ED/rayed-bqn),
  wrapper of [raylib-bqn](https://github.com/Brian-ED/raylib-bqn),
  useful for making windowed applications. It includes the bqn-only mini-libraries:
  - [Game-related math including Vector, Matrix, and Quaternions](https://github.com/brian-ED/rayed-bqn/blob/master/src/math.bqn)
  - [Low-level operations](https://github.com/brian-ED/rayed-bqn/blob/master/src/low.bqn)
- Brian ED's [raylib-bqn](https://github.com/Brian-ED/raylib-bqn), [raylib](https://github.com/raysan5/raylib) bindings.
- Brian ED's [bqn-socket](https://github.com/Brian-ED/bqn-socket/) library. Only tested on
  Linux Mint at the moment.
- Brian ED's [c-header-to-bqn-ffi](https://github.com/Brian-ED/c-header-to-bqn-ffi)
- Alex Dikelsky's [bqn-modular-arith](https://github.com/AlexDikelsky/bqn-modular-arith),
  functions for working with modular arithmetic in BQN.
- dlozeve's [bqn-curl](https://github.com/dlozeve/bqn-curl), [curl](https://curl.se) bindings.
- dlozeve's [bqn-npy](https://github.com/dlozeve/bqn-npy), for reading
  and writing arrays to files in the Numpy NPY format.
- dlozeve's
  [bqn-safetensors](https://github.com/dlozeve/bqn-safetensors), for
  reading and writing arrays to files in the safetensors format.
- Solid's [totp](https://github.com/slotThe/totp),
  a [TOTP](https://datatracker.ietf.org/doc/html/rfc6238) generator.
- GamingKing2436's [bqn-zip](https://github.com/GamingKing2436/bqn-zip), for reading 
  and writing zip files.
- panadestein's [bqn-mpi](https://codeberg.org/panadestein/bqn-mpi), for parallel programming
	  with the Message Passing Interface (MPI).
- panadestein's [bqn-einsum](https://codeberg.org/panadestein/bqn-einsum/src/branch/main), for Einstein summation.
- xenia's [bless](https://github.com/xeniagda/bless), a simple curses-like library for BQN.

## Neat projects
- Detegr's [bqed](https://github.com/Detegr/bqed), a text editor written with a modified
  version of CBQN

## Special thanks
Special thanks to [Parker](<https://codeberg.org/parker>) for being the original creator of Awesome BQN and maintaining it for over 2 and a half years!
