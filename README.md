## MiragianCycle's Dotfiles   (and macOS  too!)

This repo holds the magic that makes my writing environment awesome across all my Unix-based systems (i.e. Linux and MacOS)

### What's in the box?  

* **Unix General (Linux, MacOS etc.):** Got configs for your everyday heroes - Vim and NeoVim   (if you use both).
* **MacOS Exclusives:**  This is where things get fancy! Yabai keeps my windows in check  (WindowManager for the win!), skhd helps with super speedy keyboard shortcuts  (bye-bye repetitive tasks!), and there's even a place for SketchyBar customizations   (optional, but fun for customizing your Mac).

**Remember:** These are my preferences, but feel free to mix it up to fit your coding style. 

**ALSO REMEMBER**: Never ever blindly copy code from the internet. Please take the time to look over the code and use it judiciously. 

### Setting Up  

There are two ways to begin:

**1. Manual Mode (DIY style):**

* Grab this repo with `git clone`.
*  the files and see what tickles your fancy.
*  **For Unix folks:** Move or link  (like `.vimrc`) to their rightful spots in your home directory.
*  **For macOS folks:** Same thing! Move the config files (e.g., `.yabai`) to their home in your home directory. For SketchyBar, follow their instructions and toss your custom app catalogs in the `Applications` directory  (optional, but pretty neat!).
* **Important Note!**  Don't just copy-paste blindly - understand what each config does first  . 


###  Peek Under the Hood  

Here's a quick tour of what's inside:

* `.vimrc`: The main course - my Vim configuration.
*  **(Optional)** `.vim` directory: Extra Vim goodies like plugins and snippets (yum!).
*  **(Optional)** `.nvim` directory: NeoVim-specific configs (if you're rocking both Vim and NeoVim).
* `macOS` directory: All the macOS goodness.
    * `.yabai`:  Yabai window manager configuration.
    * `.skhd`:  Keyboard shortcut magic with skhd.


### Make it Yours  

While these configs are my jam, feel free to personalize them!  The key is to understand what each setting does before you go wild  .

**Pro-Tip:** Create a folder like `~/.dotfiles-local` to store your customizations  (this way, updates won't overwrite them).


### Copyright  ©️

This repo is rocking the MIT License: [https://choosealicense.com/licenses/mit/](https://choosealicense.com/licenses/mit/). Basically, feel free to use and share as you see fit  (with attribution, please! ).


### Bonus Round   

Here are some resources that might be helpful:

* Awesome Dotfiles: [https://github.com/awesomedotfiles/awesome-dotfiles](https://github.com/awesomedotfiles/awesome-dotfiles)
* How to Create a Dotfiles Repository: [https://www.digitalocean.com/community/tutorials/how-to-create-a-dotfiles-repository](https://www.digitalocean.com/community/tutorials/how-to-create-a-dotfiles-repository)

**Disclaimer**
The author of this repository is not liable for any damages or unintended consequences arising from the use of these dotfiles. While every effort has been made to ensure the functionality and stability of these configurations, it is understood that they may not be compatible with all systems or user preferences. Users are advised to proceed with caution and to back up their existing configurations before implementing any changes.
