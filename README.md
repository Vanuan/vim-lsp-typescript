# vim-lsp-typescript

Sets up [vim-lsp](https://github.com/prabirshrestha/vim-lsp) for TypeScript and JavaScript.

## Installing

Install typescript language server using [npm](https://www.npmjs.com):

```
npm install -g typescript typescript-language-server
```

Install the vim plugins:

```viml
" Dependencies
Plug 'prabirshrestha/async.vim'
Plug 'prabirshrestha/vim-lsp'

Plug 'ryanolsonx/vim-lsp-typescript'
```

## Usage

In order for the typescript language server to pick up your project, you must have either a `tsconfig.json` or a `jsconfig.json`. For a JavaScript project, you can simply have an empty jsconfig.json to get full intelligent support from vim-lsp.

## License

MIT
