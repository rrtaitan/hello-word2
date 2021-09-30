# hello-word2
This is a test.
When building a specific release branch, you should check the rust version in ci/rust-version.sh and if necessary, install that version by running:
$ rustup install VERSION
On Linux systems you may need to install libssl-dev, pkg-config, zlib1g-dev, etc. On Ubuntu:
$ sudo apt-get update
$ sudo apt-get install libssl-dev libudev-dev pkg-config zlib1g-dev llvm clang make
