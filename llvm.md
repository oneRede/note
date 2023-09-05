# LLVM

## 编译项目

### llvm
1. dep: cmake、make、gcc、g++、python、ninja
2. cmd: cmake -S ../llvm-project/llvm -B build -G Ninja -DLLVM_ENABLE_PROJECTS="clang" -DCMAKE_INSTALL_PREFIX=/path_install
3. cmd: ninja && ninja install