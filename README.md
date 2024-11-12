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
