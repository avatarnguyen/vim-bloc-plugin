# vim-bloc-plugin

This plugin was designed improve the flutter bloc developer experience using vim as editor.


## Installation

### You need to set you ssh key on github to able this plugin clone some files

Assuming you are using vim-plug as plugin manager, you can just put it in yout init.vim

```bash
Plug 'eliasreis54/vim-bloc-plugin', {'branch': 'main'}
```
run `PlugInstall` and you must source your .vimrc

## Usage

After your already installed the plugin, it enable a two new commands

```bash
:Bloc <BlocName> <DestinationFolder>
```

- BlocName: Is the name will be used to generate all bloc files and classes
    - **This name must be a CamelCase**
- DestinationFolder: Is the path to generate the files, like: `lib/posts`
    - **Don't start with `/`**


```bash
:Cubit <CubitName> <DestinationFolder>
```

- CubitName: Is the name will be used to generate all cubit files and classes
    - **This name must be a CamelCase**
- DestinationFolder: Is the path to generate the files, like: `lib/posts`
    - **Don't start with `/`**

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)
