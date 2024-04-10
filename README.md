 I use these dotfiles to set up my environment on my Linux and macOS machines by providing custom configurations for various software applications. The directory structure is messy and in need of cleaning, which I will do at some point. Sorry about that. 

## Features

- Customized configurations for various software applications, including:
  - Vim
  - NeoVim (NVChad and OVIWrite)
  - Yabai (MacOS only)
  - skhd (MacOS only)
  - Sketchybar (MacOS only)
- Easy-to-understand organization and setup instructions
- Compatibility with both Linux and macOS environments

## Vim, NeoVim and OVIWrite

- I use Vim, NeoVim and OVIWrite
- My vimrc is mostly legacy - I keep it here for old time's sake. Most of my writing is done on [OVIWrite](https://github.com/MiragianCycle/OVIWrite), a personalized Integrated Writing Environment built using LazyVim
- I code using the base config found on NVChad
- I have both OVIWrite and NVChad running on my systems, using aliases to switch between the two depending on if I am writing or coding 

## Emacs 

- Try as I might, I can't stop myself from using Emacs. Org-mode, particularly, is a huge draw. This is my first emacs config and really not something you should use. 


## Usage

To use these dotfiles, simply follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/dotfiles.git
   ```

2. Navigate to the cloned repository:

   ```bash
   cd dotfiles
   ```

3. Review the available dotfiles and configurations in the repository.

4. Copy the desired dotfiles to your home directory (`~`) or symlink them:

   ```bash
   ln -s /path/to/dotfiles/.vimrc ~/.vimrc
   ln -s /path/to/dotfiles/.config/nvim/init.vim ~/.config/nvim/init.vim
   # Add additional instructions for macOS exclusive dotfiles
   ```

5. Enjoy your personalized setup!

## Disclaimer

Please note that while I have made every effort to ensure the quality and accuracy of these dotfiles, it's essential to exercise caution and not blindly run code obtained from the internet. Make sure to review the code and configurations carefully before applying them to your system.

## No Liability

By using these dotfiles, you acknowledge and agree that I shall not be liable for any damages or liabilities arising from the use of these dotfiles. Use them at your own risk.

## Contribution

If you have any suggestions for improvements or additional configurations, feel free to open an issue or submit a pull request. Your feedback and contributions are highly appreciated! 🚀

## License

This project is licensed under the [MIT License](LICENSE).

