### Windows: 

1. A suitable IDE. It could be JetBrains IDEs, VS Code by Microsoft, or NeoVim
	1. Requirements for VS Code: [[1.1 VS Code]]
	2. Requirements for NeoVim: [[1.2 NeoVim]]
2. MinGW or Cygwin. Any should be fine as long as you install MSYS2 ( for C)
### MacOS:
1. XCode or Command Line Tools
	- Install: ``xcode-select --install``
2. Homebrew
	- Install: ``/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"``
3. GCC or LLVM Clang ( for compiling )
	- ``brew install gcc``
			OR
	- ``brew install llvm``
4. NeoVim or VS Code
	1. VS Code: [[1.1 VS Code]]
	2. NeoVim: [[1.2 NeoVim]]
5. CMake ( optional )
	- Install: ``brew install cmake``

### Linux:

1. GCC or Clang ( Clang recommended )
	- Ubuntu: ``sudo apt install clang build-essential -y``
	- Arch: ``sudo pacman -S gcc clang``
	- Fedora: ``sudo dnf install gcc clang``
2. CMake ( optional )
	- Ubuntu: ``sudo apt install cmake``
	- Arch: ``sudo pacman -S cmake``
	- Fedora: ``sudo dnf install cmake``
1. NeoVim or VS Code
	1. VS Code: [[1.1 VS Code]]
	2. NeoVim: [[1.2 NeoVim]]
