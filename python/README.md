# {{name}}
{{description}} written in Rust

## Installation
### Linux, x86_64
 * Go to CI in GitLab
 * Click latest pipeline
 * select build job
 * download the binary in the artifacts (in sidebar)

### Other
 * Get [Cargo](https://doc.rust-lang.org/cargo/) set up
 * Run `cargo build --release`
 * You will find your binary in `target/release/{{title}}`
 * Move that binary whereever you like.

## Usage
```bash
$ {{title}} [{{param1}}]
{{output}}
```
### Parameters
* {{param1}}: {{param1desc}}
