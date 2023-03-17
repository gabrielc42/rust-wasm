[rust-wasm](https://rustwasm.github.io/docs/book/introduction.html#rust--and-webassembly-)

If you have trouble with `cargo generate` and `gcc.exe` installation not being found, the answer by Jose on this Stack Overflow post helped:
[MSYS2, pacman, and C:\msys64\mingw64\bin to PATH](https://stackoverflow.com/questions/61645963/cant-install-cargo-binutils-library-failed-to-find-tool-is-gcc-exe-installe)

When running `npm run start` and receiving ['digital envelope routine ... in /crypto/hash'](https://github.com/rustwasm/book/issues/273) error: required a [downgraded node.js version (16.19.1)](https://stackoverflow.com/questions/69692842/error-message-error0308010cdigital-envelope-routinesunsupported/69699772#69699772). Compiled after installing [`nvm`](https://github.com/coreybutler/nvm-windows), allowing switched node.js versions
