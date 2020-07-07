# Mini OS

To get started install the following
- cargo xbuild (cargo install cargo-xbuild)
- bootloader (cargo install bootimage)
- rustup component add llvm-tools-preview

To run, run the command
- cargo bootimage
- qemu-system-x86_64 -drive format=raw,file=target/x86_64-mini_os/debug/bootimage-mini_os.bin