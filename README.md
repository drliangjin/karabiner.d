# :musical_keyboard: Karabiner-Elements Configuration :musical_keyboard:
*Created with* :heart: *by Dr Liang Jin*

## :rocket: Quick Start
```bash
bash -c "$(curl -fsSL https://raw.githubusercontent.com/drliangjin/karabiner.d/master/tools/install)"
```
- - -

<p align="center"><img src="/assets/images/davy_jones.jpg" alt="davy_jones"/></p>
<p align="center">
  <b><a href="#introduction">Introduction</a></b>
  |
  <b><a href="#features">Features</a></b>
  |
  <b><a href="#installation">Installation</a></b>
  |
  <b><a href="#resources">Resources</a></b>  
  |
  <b><a href="#features">FAQ</a></b>  
</p>

- - -

## :scroll: Introduction

This is my configuration for [Karabiner-Elements](https://pqrs.org/osx/karabiner/), a powerful and low-level keyboard manipulation tool. **Karabiner** is one of the main reasons I choose to stay with macOS while there are too many troubles to implement the same/similar layout in GNU/Linux distributions (I really tried...maybe later...).

## :sparkles: Features

### Modifiers

| From                    | To                      | Press Alone                   | Device         |
|-------------------------|-------------------------|-------------------------------|----------------|
| <kbd> Ctrl </kbd>       | <kbd> Hyper </kbd>      | <kbd> F17 </kbd>              | -              |
| <kbd> Command </kbd>    | <kbd> Option/Alt </kbd> | <kbd> F18 </kbd>              | Apple Keyboard |
| <kbd> Option/Alt </kbd> | <kbd> Command </kbd>    | <kbd> F19 </kbd>              | Apple Keyboard |
| <kbd> Caps Lock </kbd>  | <kbd> Ctrl </kbd>       | <kbd> ESC </kbd>              | -              |
| <kbd> Enter </kbd>      | <kbd> Ctrl </kbd>       | <kbd> Enter </kbd>            | -              |
| <kbd> Shift </kbd>      | <kbd> Shift </kbd>      | <kbd> ( </kbd> <kbd> ) </kbd> | -              |

### Switchers (mimic Ubuntu Unity)

| From                    | To                      | Press Alone                   | Device         |
|-------------------------|-------------------------|-------------------------------|----------------|
| <kbd> Command </kbd> `+` <kbd> Tab </kbd>   | <kbd> Option/Alt </kbd> `+` <kbd> Tab </kbd> | - | - |
| <kbd> Shift </kbd> `+` <kbd> Command </kbd> `+` <kbd> Tab </kbd>   | <kbd> Shift </kbd> `+` <kbd> Option/Alt </kbd> `+` <kbd> Tab </kbd> | - | - |

### Launchers (mimic Ubuntu Unity)

### Dash (mimic Ubuntu Unity)

### Editing (mimic Emacs)

| Key                              | From   | To (key_code)  | Function  |
|----------------------------------|--------|----------------|-----------------|
| <kbd> Ctrl </kbd> <kbd> g </kbd> | `NA`   |  | Cancel |
| <kbd> Ctrl </kbd> <kbd> w </kbd> |        |       | Cut                |
| <kbd> Ctrl </kbd> <kbd> y </kbd> |        |       | Paste                |
| <kbd> Ctrl </kbd> <kbd> / </kbd> |        |       | Undo                |
| <kbd> Ctrl </kbd> <kbd> s </kbd> |        |      | Find                |
| <kbd> Ctrl </kbd> <kbd> d </kbd> | `NA`   |  | Forward Delete Char   |
| <kbd> Ctrl </kbd> <kbd> h </kbd> | `NA`   |   | Backward Delete Char                |
| <kbd> Ctrl </kbd> <kbd> k </kbd> | `NA`   |   | Forward Kill Line                |
| <kbd> Ctrl </kbd> <kbd> u </kbd> | `NA`   |  | Backward Kill Line                |
| <kbd> Ctrl </kbd> <kbd> f </kbd> |        |          | Forward Move Char                |
| <kbd> Ctrl </kbd> <kbd> b </kbd> |        |           | Backward Move Char                |
| <kbd> Ctrl </kbd> <kbd> n </kbd> |        |           | Next Line                |
| <kbd> Ctrl </kbd> <kbd> p </kbd> |        |           | Previous Line                |
| <kbd> Ctrl </kbd> <kbd> a </kbd> |        |               | Begining of Line             |
| <kbd> Ctrl </kbd> <kbd> e </kbd> |        |                 | End of Line                |
| <kbd> Ctrl </kbd> <kbd> v </kbd> |        |             | Next Page                |
| <kbd> Ctrl </kbd> <kbd> i </kbd> |        |                   | Indent        |
| <kbd> Option/Alt </kbd> <kbd> g </kbd> |        |        | NA                |
| <kbd> Option/Alt </kbd> <kbd> w </kbd> |        |        | Copy                |
| <kbd> Option/Alt </kbd> <kbd> y </kbd> |        |        | NA                |
| <kbd> Option/Alt </kbd> <kbd> / </kbd> |        |        | Redo                |
| <kbd> Option/Alt </kbd> <kbd> d </kbd> |        |                 | Forward Kill Word        |
| <kbd> Option/Alt </kbd> <kbd> h </kbd> |        |                 | Backward Kill Word        |
| <kbd> Option/Alt </kbd> <kbd> k </kbd> |        |                 | Forward Copy Line                |
| <kbd> Option/Alt </kbd> <kbd> u </kbd> |        |                 | Backward Copy Line                |
| <kbd> Option/Alt </kbd> <kbd> f </kbd> |        |    | Forward Move Word               |
| <kbd> Option/Alt </kbd> <kbd> b </kbd> |        |    | Backward Move Word                |
| <kbd> Option/Alt </kbd> <kbd> n </kbd> |        |    | NA                |
| <kbd> Option/Alt </kbd> <kbd> p </kbd> |        |      | NA                |
| <kbd> Option/Alt </kbd> <kbd> a </kbd> |        |           | NA             |
| <kbd> Option/Alt </kbd> <kbd> e </kbd> |        |           | NA                |
| <kbd> Option/Alt </kbd> <kbd> v </kbd> |        |      | Previous Page                |
| <kbd> Option/Alt </kbd> <kbd> i </kbd> |        |            | NA |

### File (mimic Emacs)
| From                    | To                      | Press Alone                   | Device         |
|-------------------------|-------------------------|-------------------------------|----------------|
| <kbd> Ctrl </kbd> <kbd> z </kbd>`+` <kbd>  </kbd>   | <kbd> Option/Alt </kbd> `+` <kbd> Tab </kbd> | - | - |
| <kbd> Ctrl </kbd> <kbd> z </kbd>`+` <kbd> Tab </kbd>   | <kbd> Option/Alt </kbd> `+` <kbd> Tab </kbd> | - | - |
## :hammer_and_wrench: Installation
```bash
brew cask install karabiner-elements
```

## :loudspeaker: Updates

## :construction: Development
### TODO
- [ ] macOS workspace shortcuts (`ctrl left_arrow` & `ctrl right_arrow`, `ctrl #`)
- [ ] macOS dock shortcuts (`ctrl F3`, then left_arrow or right_arrow to move, `return` to open an item)
- [ ] implement <kbd> Tab </kbd> as a modifier when hold down
- [ ] <kbd> Ctrl </kbd> + <kbd> j </kbd> and <kbd> Ctrl </kbd> + <kbd> m </kbd>
- [ ] Cycle clipboard history using <kbd> Option/Alt </kbd> + <kbd> y </kbd>
- [x] delete to kill/cut (select text and cut, for words and lines)
- [x] `undo` (<kbd> Ctrl </kbd> + <kbd> / </kbd> ) and redo (<kbd> Option/Alt </kbd> + <kbd> / </kbd> )
- [ ] implement `to_if_held_down` and `to_after_key_up`, see complex modifications [example](https://github.com/pqrs-org/KE-complex_modifications/blob/8f48a175795e1e737a6885068d729cb4586114a4/docs/json/example_halt.json)
- [ ] implement virtual modifiers using `set_variable` and `variable_if`, see [virtual-modifier from pqrs.org](https://pqrs.org/osx/karabiner/json.html#virtual-modifier)
## :medal_military: Acknowledgement

## :open_book: Resources
- [Text System Defaults and Key Bindings](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/EventOverview/TextDefaultsBindings/TextDefaultsBindings.html#//apple_ref/doc/uid/20000468-CJBDEADF) from Apple Developer
- [Cocoa Text System](http://www.hcs.harvard.edu/~jrus/site/cocoa-text.html) by Jacob Rus
- [Selector](http://www.hcs.harvard.edu/~jrus/site/selectors.html) by Jacob Rus
- [Default Mac OS X System Key Bindings](http://www.hcs.harvard.edu/~jrus/site/system-bindings.html)
- [A short article about emacs keybindings in macOS](https://jblevins.org/log/kbd)
- [ttscoff's KeyBindings](https://github.com/ttscoff/KeyBindings)
- [Emacs Keybindings Everywhere in Mac OS X](http://lelf.lu/posts/emacs-keybindings-mac-os-x.html) by lelf
- [Ukelele](http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=ukelele)
- [Mac OS X: Keybinding DefaultKeyBinding.dict Problems](http://xahlee.info/kbd/osx_keybinding_problems.html) by Xah Lee

## :raising_hand_woman: FAQ
