# ZTK Business Edition v3.0 - Ultimate Edition

An ISO C11 compliant, multi-threaded text user interface (TUI) operating layer featuring DeepSeek AI integration, text-based games, terminal browsing, and disk management utilities.

## Features
* 🤖 **ZewAI Bot:** Powered by DeepSeek API for smart terminal assistance.
* 🎮 **Built-in Games:** Snake, Tetris, Pong, and Space Invaders.
* 🌐 **Terminal Browser:** Links/Lynx-style text web browsing.
* 💾 **Disk Management:** Direct mount, format, and partition controls.
* ⚙️ **Self-Modifying:** Modify and recompile code from within the running system.

## Compilation & Usage

### Linux & macOS
Ensure you have the `ncurses` development libraries installed:
```bash
# Ubuntu/Debian
sudo apt install libncurses5-dev libncursesw5-dev

# Compile
gcc -std=c11 -Wall -Wextra -o ztk ztk.c -lpthread -lncurses

# Run
./ztk --ai-token YOUR_DEEPSEEK_TOKEN
```

### Windows
```bash
gcc -std=c11 -Wall -Wextra -o ztk ztk.c -lpthread
./ztk
```

## License
Distributed under the MIT License. See `LICENSE` for more information.

