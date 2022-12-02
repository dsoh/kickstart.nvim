### Introduction

based off of kickstart.vim with custom shortcuts added and a few more addons such as
- lazygit
- hop (like easymotion)
- floatterm (terminal access within neovim)
- bufferline (better tabs)
- neotree (file browser)
- nvim-comment (comment out code)

### Custom Shortcuts

```lua
<leader> is set to spacebar

<leader>gg -- lazy git
<leader>` -- open terminal
<leader>? -- find in recently opened files
<leader>/ -- find in current buffer
<leader>sf -- search files
<leader>sg -- search grep
<leader><leader><space> -- find in existing buffers
<leader>o -- open Tree File viewer
<leader>j -- previous tab
<leader>k -- next tab
<leader><leader>h -- move window left
<leader><leader>l -- move window right
<leader><leader>j -- move window down
<leader><leader>k -- move window down
<leader><leadem>s -- jump to letter
<leader>c -- comment line or selected block

:Q -- quit all same as :qa!
```

### Requirements

ripgrep is required for grep search - https://github.com/BurntSushi/ripgrep

a nerd font is required for neo tree icons - https://www.nerdfonts.com/font-downloads

lazygit is required for <leader>gg - https://github.com/jesseduffield/lazygit


### Installation

```
cp init.lua ~/.config/nvim/
```
