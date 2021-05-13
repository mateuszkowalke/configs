# configs

remember to add:

:CocConfig

{
  "languageserver": {
    "golang": {
      "command": "gopls",
      "rootPatterns": ["go.mod", ".vim/", ".git/", ".hg/"],
      "filetypes": ["go"]
    }
  }
}

:help vim-go

:help coc-nvim
