AstroNvim User Configuration Example

A user configuration template for AstroNvim
hammer_and_wrench Installation
Make a backup of your current nvim and shared folder

mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak

Clone AstroNvim

git clone https://github.com/AstroNvim/AstroNvim ~/.config/nvim

Create a new user repository from this template

Press the "Use this template" button above to create a new repository to store your user configuration.

You can also just clone this repository directly if you do not want to track your user configuration in GitHub.
Clone the repository

git clone https://github.com/<your_user>/<your_repository> ~/.config/nvim/lua/user

Start Neovim

nvim
