# oh-my-zsh joaoantoniomaruti oh-my-zsh personal theme
This is a personal theme for oh-my-zsh created by joaoantoniomaruti. It includes a custom prompt with git integration and an icon for indicating the stack type.

![JAMM Terminal Theme](./assets/screenshot.png)

## Inspiration
The theme is inspired by ubunly-zsh-theme.

### Features
The theme includes the following features:

### Git Integration
The prompt includes the current git branch and status, which is indicated by icons. The following icons are used:

 - ± indicates there are changes to be committed.
 - ✓ indicates there are no changes to commit.
 - ▴ indicates the branch is ahead of the remote.
 - ▾ indicates the branch is behind the remote.
 - ● indicates there are staged changes.
 - ● indicates there are unstaged changes.
 - ● indicates there are untracked files.

### Stack Icon
The prompt includes an icon that indicates the stack type. The following icons are used:

 -  indicates an Elixir stack.
 -  indicates a JavaScript stack.
 -  indicates a Dart stack.
 -  indicates a Vim stack.

### Usage
To use this theme, clone the repository and add the path to your .zshrc file:

```makefile
ZSH_THEME="path/to/oh-my-zsh-joaoantoniomaruti-theme/theme.zsh"
```

#### License
This theme is licensed under the MIT License.

---
_Developed by [João Maruti](https://github.com/joaoantoniomaruti)_
