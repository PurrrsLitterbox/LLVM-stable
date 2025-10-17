# Kaleidoscope Clang

Stable release, check release page below or simply curl [latestlink.txt](https://raw.githubusercontent.com/PurrrsLitterbox/LLVM-stable/refs/heads/main/latestlink.txt) file from your script to download latest release.

# Installation

```bash
mkdir $HOME/.kaleidoscope
tar -xf clang.tar.zst -C $HOME/.kaleidoscope
echo "export PATH=$HOME/.kaleidoscope/bin:$PATH" >> ~/.bashrc
source $HOME/.bashrc
clang --version
``` 

# Features

==> Minimal LLVM 21.1.3 targeting 'AArch64', 'ARM', and 'X86'

==> GLibC version 2.35

==> Shipped with binutils version 2.44

==> Stripped binaries

==> Download size 244MB

==> Compressed tar archive with zstd

==> Build LLVM Polly & LLD

==> Build with ThinLTO + PGO
