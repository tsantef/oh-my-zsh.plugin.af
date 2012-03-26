# AppFog CLI Autocompletion

## Installation for Oh-my-ZSH

1) Install Oh-my-ZSH

2) Clone this repo into ~/.oh-my-zsh/custom/plugins

    git clone git@github.com:tsantef/oh-my-zsh.plugin.af.git ~/.oh-my-zsh/custom/plugins/af

3) add pf to your plugins list in the .zshrc file

    plugins=(git af)

4) Restart your shell or open a new terminal window.


## Installation without Oh-my-ZSH

1) Copy the _af file into ~/.zsh/completions

2) Add the completion path to the fpath setting in the ~/.zshrc 

    # Add Custom Completion Scripts
    fpath=(~/.zsh/completions $fpath)

3) Add or verify that the complition initalization lines below are in the ~/.zshrc file

    # compsys initialization
    autoload -U compinit
    compinit

4) Restart your shell or open a new terminal window.