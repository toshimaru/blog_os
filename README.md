# Writing an OS in Rust

resource: <https://os.phil-opp.com/>

## Build

```console
$ cargo build --target thumbv7em-none-eabihf
```

### for MacOS

```console
$ cargo rustc -- -C link-args="-e __start -static -nostartfiles"
```

## `target x86_64-blog_os.json`

```console
$ cargo build --target x86_64-blog_os.json
```

### How to enable the `nightly` feature

```console
$ rustup install nightly
$ rustup override set nightly
```
