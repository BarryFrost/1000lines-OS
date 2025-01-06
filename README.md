# 1000lines-OS
A practice and learning field about operating system implementation about 1000 line of codes  
Follow the [Operating System in 1,000 Lines](https://operating-system-in-1000-lines.vercel.app/en) tutorial to implement an OS using RISC-V ISA  
### Lab environment : qemu-system-riscv32
### Prerequisites
Install qemu(risc-v 32bit), llvm compiler(llvm clang lld), curl(download opensbi firmware)  
```console
user:~$ sudo apt update && sudo apt install -y qemu-system-riscv32 llvm clang lld curl
```
Download the compiled OpenSBI firmware
```console
user:~$ curl -LO https://github.com/qemu/qemu/raw/v8.0.4/pc-bios/opensbi-riscv32-generic-fw_dynamic.bin
```
# Reference
[Operating System in 1,000 Lines](https://operating-system-in-1000-lines.vercel.app/en)
[RISC-V supervisor binary interface firmware](https://github.com/qemu/qemu/raw/v8.0.4/pc-bios/opensbi-riscv32-generic-fw_dynamic.bin)
