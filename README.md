Command prompt

winget install cmake
winget install patch

cargo add rquickjs-sys@1.7.0
cargo add librocksdb-sys@0.8.0
cargo add watch
cargo build
cargo run | cargo watch -x run
