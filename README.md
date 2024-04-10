## MiragianCycle's Dotfiles

This repository contains the configuration files (dotfiles) used to personalize my development environment across various Unix-based systems and macOS. 

### Welcome!

Since there's been some interest in how I set up my development environment, I decided to document it. This repository serves as a reference point for my configurations and hopefully, a useful starting point for others.

### What's Included?

This repository primarily focuses on two areas:

* **Unix-based Systems:** Configurations for ubiquitous tools like Vim and NeoVim.
* **macOS:** Configurations for window management (Yabai), keyboard shortcuts (skhd), and potentially SketchyBar (optional).

**Note:** The specific dotfiles included will depend on the tools you use and your personal preferences.


### Getting Started

There are two main ways to utilize these dotfiles:

**1. Manual Installation:**

* Clone this repository to your desired location.
* Review the included dotfiles and customize them as needed.
*  **Unix-based Systems:**
    *  Move or link the relevant dotfiles (e.g., `.vimrc`) to their corresponding locations in your home directory.
*  **macOS:**
    *  Move or link the relevant configuration files (e.g., `.yabai`) to their corresponding locations in your home directory. 
    *  (**Optional**) If using SketchyBar, follow their installation instructions and place your custom application catalogs within the `Applications` directory. 
*  **Important:**  Ensure you understand the configurations before blindly copying them. 

**2. Dotfiles Manager (Recommended):**

Consider using a dotfiles manager like [https://github.com/thoughtbot/dotfiles](https://github.com/thoughtbot/dotfiles) to simplify installation and management. 


### Configuration Overview

The repository is structured as follows:

* `.vimrc`: Primary configuration file for Vim.
*  **Optional:** `.vim` directory: Additional Vim configuration files (plugins, snippets etc.).
*  **Optional:** `.nvim` directory: Configuration files specific to NeoVim (if you use both).
* `macOS` directory: Contains configuration files specific to macOS.
    * `.yabai`: Configuration file for the Yabai window manager.
    * `.skhd`: Configuration file for keyboard shortcuts with skhd.
    * `Applications` (Optional): Directory for storing SketchyBar application catalogs.


### Customization

While these configurations reflect my preferences, feel free to customize them! It's important to understand what each configuration does before blindly copying. 

**Pro Tip:** Create a directory like `~/.dotfiles-local` to store your own customizations that won't be overwritten during updates.


### License

This repository is licensed under the MIT License: [https://choosealicense.com/licenses/mit/](https://choosealicense.com/licenses/mit/). 

### Resources

Here are some resources that you might find helpful:

* Awesome Dotfiles: [https://github.com/awesomedotfiles/awesome-dotfiles](https://github.com/awesomedotfiles/awesome-dotfiles)
* How to Create a Dotfiles Repository: [https://www.digitalocean.com/community/tutorials/how-to-create-a-dotfiles-repository](https://www.digitalocean.com/community/tutorials/how-to-create-a-dotfiles-repository)


I hope this README provides a clear overview of my dotfiles repository. Feel free to reach out if you have any questions!
