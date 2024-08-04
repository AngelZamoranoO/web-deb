---
title: markmap para practica nueva herramienta
markmap:
  colorFreezeLevel: 2
  initialExpandLevel: 5 
  duration: 1000
  maxWidth: 100
  initialExpandLevel: -1
  
---
<!-- esto es un comentario
color
Type: string | string[], default: d3.schemeCategory10

A list of colors to use as the branch and circle colors for each node.

If none is provided, d3.schemeCategory10 will be used.

colorFreezeLevel
Type: number, default: 0

Freeze color at the specified level of branches, i.e. all child branches will use the color of their ancestor node at the freeze level.

0 for no freezing at all.

duration
Type: number, default: 500

The animation duration when folding/unfolding a node.

maxWidth
Type: number, default: 0

The max width of each node content. 0 for no limit.

initialExpandLevel
Type: number, default: -1

The maximum level of nodes to expand on initial render.

-1 for expanding all levels.

extraJs
Type: string[], default: none

A list of JavaScript URLs. This is useful to add more features like Katex plugins.

extraCss
Type: string[], default: none

A list of CSS URLs. This is useful to add more features like Katex plugins.

zoom
Type: boolean, default: true

Whether to allow zooming the markmap.

pan
Type: boolean, default: true

Whether to allow panning the markmap.

htmlParser
Type: object

Pass options to the internal HTML parser, for example to override the default selectors for elements to display.


 -->
## links 
- Texto normal <!-- markmap: foldAll-->
  - [Texto enlace](https://www.google.com) 
    - otro nivel de aquello y puedo escribir una leve descripcion
    - la wea pulenta
    - esto es un comentario <!-- esto es un comentario del programa-->
  - se concadena otra rama
  - [x] agrego un check box
- [markmap](https://markmap.js.org/)
- [mi github](https://github.com/AngelZamoranoO/web-deb)

## Related Projects <!-- markmap: fold-->

- [coc-markmap](https://github.com/gera2ld/coc-markmap) for Neovim
- [markmap-vscode](https://marketplace.visualstudio.com/items?itemName=gera2ld.markmap-vscode) for VSCode
- [eaf-markmap](https://github.com/emacs-eaf/eaf-markmap) for Emacs


## Features 

Note that if blocks and lists appear at the same level, the lists will be ignored.

### Lists

- **strong** ~~del~~ *italic* ==highlight==
- `inline code`
- [x] checkbox
- Katex: $x = {-b \pm \sqrt{b^2-4ac} \over 2a}$ <!-- markmap: fold -->
  - [More Katex Examples](#?d=gist:af76a4c245b302206b16aec503dbe07b:katex.md)
- Now we can wrap very very very very long text based on `maxWidth` option

### Blocks

```js
console.log('hello, JavaScript')
```

| Products | Price |
|-|-|
| Apple | 4 |
| Banana | 2 |

## agrego otro nivel desde este parametro
- que es hermosa esta herramienta
  - increible aprender sobre este tema
  - otro tema o topico

 

