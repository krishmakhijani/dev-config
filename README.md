Certainly, here's an extended version:

---

# dev-config

Welcome to the **dev-config** repository! This collection features configuration files tailored for macOS and Linux. Windows isn't part of the club here. The guides below will show you how to set up essential tools like Neovim, Tmux, Starship, and Visual Studio Code settings for a seamless development environment.

## Features

- **Neovim**: A modern, blazing-fast text editor with extensive plugin support.
- **Tmux**: Terminal multiplexer to efficiently manage multiple terminal sessions.
- **Starship**: A minimal, customizable, and fast shell prompt for any shell.
- **VS Code Settings**: Predefined settings to enhance your coding productivity.
- **Optional Tools**: Additional tools like `Fzf` and `Ripgrep` for better search.

## Screenshots

### VSCODE on macOS/Linux
![Neovim and Tmux macOS](https://github.com/krishmakhijani/dev-config/assets/112251957/90015796-f923-49a4-964e-6f3599112e3c)

### Starship and Tmux on macOS/Linux
![Neovim and Tmux Linux](https://github.com/krishmakhijani/dev-config/assets/112251957/2affd2f4-dd62-41a9-abab-eb6119cb8ed2)

### Starship Setup on macOS/Linux
![VSCode macOS](https://github.com/krishmakhijani/dev-config/assets/112251957/9b429a79-2d2a-472e-8dc1-503e3d3a276d)

### Neovim Setup on macOS/Linux
![VSCode Linux](https://github.com/krishmakhijani/dev-config/assets/112251957/5d1cfcb0-a2a4-4a3b-8d87-d4b79dbd09bd)

### Terminal Intellisense Overview
![System Setup Overview](https://github.com/krishmakhijani/dev-config/assets/112251957/9ef0fbbd-933b-4bd7-925d-22037d1d9286)

## Installation

### Neovim

1. **macOS**:
   - Install via Homebrew:
     ```bash
     brew install neovim
     ```
   - **Configuration**: Copy `init.vim` (Neovim's configuration file) to:
     ```bash
     mkdir -p ~/.config/nvim && cp path/to/your/init.vim ~/.config/nvim/
     ```

2. **Linux**:
   - Use apt or a similar package manager:
     ```bash
     sudo apt update && sudo apt install neovim
     ```
   - **Configuration**: Copy `init.vim` to:
     ```bash
     mkdir -p ~/.config/nvim && cp path/to/your/init.vim ~/.config/nvim/
     ```

### Tmux

1. **macOS**:
   - Install via Homebrew:
     ```bash
     brew install tmux
     ```
   - **Configuration**: Copy `.tmux.conf` to your home directory:
     ```bash
     cp path/to/.tmux.conf ~/
     ```

2. **Linux**:
   - Use apt or a similar package manager:
     ```bash
     sudo apt update && sudo apt install tmux
     ```
   - **Configuration**: Copy `.tmux.conf` to:
     ```bash
     cp path/to/.tmux.conf ~/
     ```

### Starship

1. **macOS**:
   - Install via Homebrew:
     ```bash
     brew install starship
     ```
   - **Configuration**: Add this to `.bashrc` or `.zshrc`:
     ```bash
     eval "$(starship init bash)"
     ```

2. **Linux**:
   - Install via the official Starship script:
     ```bash
     curl -sS https://starship.rs/install.sh | sh
     ```
   - **Configuration**: Add this to `.bashrc` or `.zshrc`:
     ```bash
     eval "$(starship init bash)"
     ```

### Visual Studio Code

1. **macOS**:
   - Download and install [VS Code](https://code.visualstudio.com/) directly or use Homebrew:
     ```bash
     brew install --cask visual-studio-code
     ```

2. **Linux**:
   - Download the `.deb` or `.rpm` installer package from the [VS Code website](https://code.visualstudio.com/), or:
   - Use the command line:
     ```bash
     sudo snap install --classic code
     ```

### Placing `settings.json`

1. **macOS**:
   - Open Finder and navigate to:
     ```bash
     ~/Library/Application Support/Code/User/
     ```
   - Place the `settings.json` file here.

2. **Linux**:
   - Navigate to:
     ```bash
     ~/.config/Code/User/
     ```
   - Place your `settings.json` file in this directory.

### Optional Tools

1. **Fzf (Fuzzy Finder)**:
   - Install using Homebrew:
     ```bash
     brew install fzf
     ```
   - Or with apt:
     ```bash
     sudo apt install fzf
     ```
   - **Integration**: Add the following to `.bashrc` or `.zshrc`:
     ```bash
     [ -f ~/.fzf.bash ] && source ~/.fzf.bash
     [ -f ~/.fzf.zsh ] && source ~/.fzf.zsh
     ```

2. **Ripgrep**:
   - Install via Homebrew:
     ```bash
     brew install ripgrep
     ```
   - Or via apt:
     ```bash
     sudo apt install ripgrep
     ```

3. **Node.js**:
   - Install with Homebrew:
     ```bash
     brew install node
     ```
   - Or with apt:
     ```bash
     sudo apt install nodejs
     ```



## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---