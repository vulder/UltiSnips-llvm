# UltiSnips for LLVM

# Installation

Adaptations to the c/cpp snippets to target the llvm style guide.

```vim
  let g:UltiSnipsSnippetsDir="~/.vim/UltiSnips"
```

```bash
  cd ~/.vim
  git clone https://github.com/vulder/UltiSnips-llvm.git UltiSnips
```

## Extra commands
|Command   | Description            |
|----------|------------------------|
| hcom     | create header comment
| cbl      | class block comment
| sep      | create llvm separator
| bsep     | block separator
| ifndef   | adapted style
| ns       | adapted style
| dyn/idy  | dyn_cast/if dyn_cast
| isa/iis  | isa/if isa
