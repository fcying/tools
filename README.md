#### My Favorite Tools

#### binary (download from releases)
* [tig](https://github.com/jonas/tig)
* [universal-ctags](https://github.com/universal-ctags/ctags)
* [winscp](https://winscp.net)
* [putty](https://www.chiark.greenend.org.uk/~sgtatham/putty)
* [MobaXterm](https://mobaxterm.mobatek.net/)
* [ccls](https://github.com/MaskRay/ccls)
* [clangd](https://github.com/clangd/clangd)
* [llvm](https://github.com/llvm/llvm-project)</BR>
    llvm project msvc build option
    ```
    VC++ compiler toolset version: 14.16

    cd /d c:\llvm
    cmake -Hllvm -BRelease -G Ninja -DCMAKE_BUILD_TYPE=Release -DCMAKE_C_COMPILER=cl -DCMAKE_CXX_COMPILER=cl -DLLVM_TARGETS_TO_BUILD=X86 -DLLVM_ENABLE_PROJECTS=clang
    ninja -C Release clangFormat clangFrontendTool clangIndex clangTooling clang
    ```


#### mirror
* [ghproxy](https://ghproxy.com)


#### link
* [ripgrep](https://github.com/BurntSushi/ripgrep)
* [neovim](https://github.com/neovim/neovim)
* [nvim_config](https://github.com/fcying/dotvim)

