# An Operating System in under 1000 lines
The goal of this project was for me to learn the inside of a small operating system, and the basics of the RISC-V architecture.
## Installation
To run this program you need a couple of dependencies.  
### Ubuntu:
```
sudo apt update && sudo apt install -y clang llvm lld qemu-system-riscv32 curl
curl -LO https://github.com/qemu/qemu/raw/v8.0.4/pc-bios/opensbi-riscv32-generic-fw_dynamic.bin
```
### macOS:
```
brew install llvm lld qemu
export PATH="$PATH:$(brew --prefix)/opt/llvm/bin"
which llvm-objcopy
/opt/homebrew/opt/llvm/bin/llvm-objcopy
```
## Execution
to run, all you need to do is :
```
chmod +x run.sh
./run.sh
```
