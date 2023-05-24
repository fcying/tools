#### My Favorite Tools

#### binary (download from [Releases](https://github.com/fcying/tools/releases))
* [tig static](https://github.com/jonas/tig)
* [universal-ctags static](https://github.com/universal-ctags/ctags)
* [astyle static](https://astyle.sourceforge.net/)
* [ccls static](https://github.com/MaskRay/ccls)
* [clangd with rpath lib](https://github.com/clangd/clangd)
* [clang-format static](https://github.com/llvm/llvm-project)
* [winscp](https://winscp.net)
* [putty](https://www.chiark.greenend.org.uk/~sgtatham/putty)
* [MobaXterm](https://mobaxterm.mobatek.net/)
* [make 3.8.2](https://ftp.gnu.org/gnu/make)
* [openjdk](https://openjdk.java.net)
* [llvm](https://github.com/llvm/llvm-project)</BR>
    llvm project msvc build option
    ```
    VC++ compiler toolset version: 14.29

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

#### openjdk-7 build options
```
os: ubuntu 14.04
apt-get update
apt-get install -y openjdk-7-jdk build-essential wget ant zip fastjar gawk cpio xsltproc libcups2-dev libfreetype6-dev libfontconfig1-dev libasound2-dev libpcsclite-dev libsctp-dev libxinerama-dev libxcomposite-dev libxrender-dev libxtst-dev
wget -Ojdk7.tgz https://launchpad.net/ubuntu/+archive/primary/+sourcefiles/openjdk-7/7u211-2.6.17-0ubuntu0.1/openjdk-7_7u211-2.6.17.orig.tar.gz
tar xzvf jdk7.tgz
cd openjdk*
./configure --prefix=/opt/jdk_1.7.0_201 --with-jdk-home=/usr/lib/jvm/java-7-openjdk-amd64 --disable-tests --disable-docs --disable-bootstrap --disable-bootstrap-tools --without-rhino --disable-system-kerberos --disable-system-jpeg --disable-system-png --disable-system-gif --disable-system-lcms --disable-system-gtk --disable-system-gio --disable-system-gconf --disable-compile-against-syscalls
make -j && make install
```

