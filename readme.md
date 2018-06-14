# VKO vim configuration

Advanced VIM Configuration for FullStack Developers, for now it's supporting.
- Backend: Ruby on Rails, Python and Elixir.
- Front-end: React
- Ops: Docker, Nginx, Ansible.

Only tested with Neovim.

# Mappings

## Leaders
| key       | Description |
| -         | -           |
| `<space>` | Leader      |
| `;`       | FuzzyFinder |
| `,`       | Files       |
| `s`       | Windows     |
| `t`       | Tabs        |
| `z`       | Foldings    |
| `m`       | Bookmarks    |

## Miscellaneous
| key           | Mode          | Action                                       |
| -             | -             | -                                            |
| `Reload`      | Command       | Reload vimrc                                 |
| `<Leader>a`   | Normal        | Align paragraph                              |
| `<Leader>,`   | Normal        | Remove all spaces EOL                        |
| `<Leader>ow`  | Normal        | Overwrite word                               |
| `<Leader>saw` | Normal/visual | Replace all occurences under cursor          |
| `<Leader>w`   | Normal        | Save current file                            |
| `<Leader>d`   | Normal/Visual | Duplicate line/selected                      |
| `!`           | Normal        | Start an external Command with a single bang |
| `s`           | visual        | Replace within selected area                 |
| `gp`          | Normal        | Select last paste                            |
| `Y`           | Normal        | Copy until the end of line                   |
| `q`           | Normal        | Quit                                         |
| `g;`          | visual        | Jump to last edited location                 |
| `g,`          | visual        | Jump to next edited location                 |
| `<Ctrl>r`     | insert        | Open resgister content                       |
| `gc<motion>`  | Normal/visual | Toggle comments                              |
| `/`           | Normal        | Easy motion                                  |
| `W!!`         | Command       | Save with sudo                               |
| `<Leader>;`   | Normal        | Toggle tag bar                               |
| `<Leader>l`   | Normal        | Toggle tag bar                               |

## Macro
| `Q` | Normal | Record  |
| `M` | Normal | Execute |

## Windows
| key                | Mode   | Action                  |
| -                  | -      | -                       |
| `<Window>v`        | Normal | Split tab horizontaly   |
| `<Window>g`        | Normal | Split tab verticaly     |
| `<Window>c`        | Normal | Close                   |
| `<Window>co`       | Normal | Close other             |
| `<Window>b`        | Normal | Back to previous buffer |
| `<Window>r`        | Normal | Rotate                  |
| `<Window>z`        | Normal | Zoom toggle             |
| `Arrows`           | Normal | Resize                  |

## Tabs
| key       | Mode   | Action       |
| -         | -      | -            |
| `<Tabs>t` | Normal | Open new tab |
| `<Tabs>l` | Normal | Next tab     |
| `<Tabs>h` | Normal | Prev tab     |

## Files
| key         | Mode   | Action                                |
| -           | -      | -                                     |
| `<Files>du` | Normal | Duplicate current file                |
| `<Files>de` | Normal | Delete current file                   |
| `<Files>m`  | Normal | Move/Rename current file              |
| `<Files>y`  | Normal | Copy file-path to clipboard(relative) |
| `<Files>Y`  | Normal | Copy file-path to clipboard(absolute) |

## Sidebar
| key        | Mode     | Action                               |
| -          | -        | -                                    |
| `<Files>e` | Normal   | Toggle file explorer                 |
| `<Files>a` | Normal   | Toggle file explorer on current file |
| `w`        | NerdTree | Toggle window size                   |
| `N`        | NerdTree | Create new file or directy           |

## FuzzyFinder
| key              | Mode   | Action                |
| -                | -      | -                     |
| `<FuzzyFinder>f` | Normal | Files                 |
| `<FuzzyFinder>w` | Normal | Opened Windows        |
| `<FuzzyFinder>g` | Normal | Search text all       |
| `<FuzzyFinder>t` | Normal | Tags                  |
| `<FuzzyFinder>T` | Normal | Tags(Current Buffer)  |
| `<FuzzyFinder>c` | Normal | Commits(current file) |
| `<FuzzyFinder>b` | Normal | Buffers               |
| `<FuzzyFinder>/` | Normal | Lines(current buffer) |
| `<FuzzyFinder>m` | Normal | Marks                 |

## Find and Replace(Far)
| key                        | Mode    | Action                            |
| -                          | -       | -                                 |
| `:Far <from> <to> <files>` | Command | Open "find & replace" console     |
| `t`                        | Far     | Toggle the match above the cursor |
| `:Fardo`                   | Far     | Do the replacement                |
| `:F <pattern>`             | Command | find all                          |

## Ctags
| key       | Mode   | Action           |
| -         | -      | -                |
| `<ctrl>]` | Normal | Go to definition |
| `UpdateTags` | Command | UpdateTags |

## Multiple Cursor
| key       | Mode   | Action                |
| -         | -      | -                     |
| `<ctrl>n` | Normal | select next occurence |
| `<ctrl>p` | Normal | Undo Selection        |
| `<ctrl>x` | Normal | Skip current          |

## Bookmarks
| key            | Mode   | Action                           |
| -              | -      | -                                |
| `<Bookmarks>m` | Normal | Toggle bookmarks in current line |
| `<Bookmarks>n` | Normal | Jump to next bookmark            |
| `<Bookmarks>p` | Normal | Jump to prev bookmark            |
| `<Bookmarks>a` | Normal | show list of all bookmarks       |
| `<Bookmarks>x` | Normal | remove all bookmarks             |

## Foldings
| key             | Mode   | Action                                            |
| -               | -      | -                                                 |
| `<Foldings>a`   | Normal | toggle fold current level                         |
| `<Foldings>r`   | Normal | Recues folding by opening one more level of folds |
| `<Foldings>R`   | Normal | Open all folds                                    |
| `<Foldings>Mza` | Normal | Close the others                                  |

## Git
| key | Mode | Action |
|-|-|-|

## Snippets
| key         | Mode   | Action               |
| -           | -      | -                    |
| `<Leader>s` | Normal | create a new snippet |

## Tabularize
| key          | Mode          | Action               |
| -            | -             | -                    |
| `<Leader>tt` | Normal/visual | tabularize by custom |
| `<Leader>t=` | Normal/visual | tabularize by =      |
| `<Leader>t:` | Normal/visual | tabularize by :      |

## Text Objects
| key   | Mode   | Action            |
| -     | -      | -                 |
| `e`   | Normal | entire file       |
| `_`   | Normal | underscore        |
| `r`   | Normal | ruby block        |
| `=/-` | Normal | erb               |
| `i`   | Normal | indentation level |
| `f`   | Normal | function          |

# Languages/Frameworks

## Ruby
| Key              | Mode   | Action                                                |
| -                | -      | -                                                     |
| `,#`             | Normal | ruby string interpolation #{}                         |
| `]m`             | Normal | To edit start of next method definition               |
| `]M`             | Normal | To go to end of next method definition                |
| `[m`             | Normal | To start of previous method definition                |
| `[M`             | Normal | To end of previous method definition                  |
| `<Learder>rap`   | Normal | Add params to method                                  |
| `<Learder>rit`   | Normal | Remove declaration of the variable and use the result |
| `<Learder>rcpc`  | Normal | From if one line to multiline                         |
| `<Learder>rec`   | Normal | Extract Constant                                      |
| `<Learder>rel`   | Normal | Extract let                                           |
| `<Learder>relv`  | Normal | To local variable                                     |
| `<Learder>rrlv`  | Normal | Rename local variable                                 |
| `<Learder>rriv`  | Normal | Rename instance variable

### Ruby On Rails
| key   | Mode    | Action                  |
| -     | -       | -                       |
| `gf`  | Normal  | goto                    |
| `:A`  | Command | Alternate file          |
| `:AS` | Command | Alternate file in split |
| `:R`  | Command | Related file            |
| `:RS` | Command | Related file in split   |

## Elixir
| key            | Mode    | Action                                                              |
|-|-|-|

## Go
| key            | Mode    | Action                                                              |
|-|-|-|

## Clojure
| key            | Mode    | Action                                                              |
|-|-|-|

## Python
| key            | Mode    | Action                                                              |
|-|-|-|

## Javascript
| key            | Mode    | Action                                                              |
| -              | -       | -                                                                   |
| `:ImportJSFix` | Command | Import any missing modules and remove any modules that are not used |
| `:JsDoc`       | Command | Generate JSDoc for the function

### React
| key | Mode | Action |
|-|-|-|

## CSS
| key            | Mode    | Action                                                              |
|-|-|-|

## HTML/JSX
| key          | Mode    | Action                                |
| -            | -       | -                                     |
| `Ctrl+y + ,` | Command | Expand emmet sequence                 |
| `Ctrl+y + ,` | visual  | Wrap selected tag with emmet sequence |
| `<c-y>d`     | insert  | Balance a Tag Inward                  |
| `<c-y>D`     | insert  | Balance a Tag Outward                 |
| `<c-y>n`     | insert  | Go to the Next Edit Point             |
| `<c-y>N`     | insert  | Go to the Previous Edit Point         |

# Required
- https://github.com/BurntSushi/ripgrep
- https://github.com/junegunn/vim-plug
- http://ctags.sourceforge.net
- https://github.com/junegunn/fzf

# How to install
```
$ cd ~/.config
$ mv nvim nvim-bk
$ git clone git@github.com:AlexVKO/VimKO.git nvim

And then inside neovim run :PlugInstall
```

Inspired by:
  - https://github.com/rafi/vim-config
