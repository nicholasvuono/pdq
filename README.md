# pdq ⚡

a JavaScript engine that's pretty damn quick

## Install Odin (Linux)

Install LLVM and Clang if they aren't already

```
sudo apt install llvm
sudo apt install clang
```

Clone Odin Repository

```
git clone https://github.com/odin-lang/Odin
```

Build the Odin Compiler

```
cd Odin
make
```

Add Compiler to PATH

```
nano ~/.profile
export PATH=$PATH:$HOME/Odin
source ~/.profile
```

NOTE: you can allso add it to ~/.bashrc instead
