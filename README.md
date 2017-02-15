# cargo-template

Collection of my own templates for use with cargo.

Cargo, the Rust package manager and build tool, can use templates to build to scaffold projects.
I tend to modify the default `bin` and `lib` tempaltes after creation to include additional information, links and badges anyway.

With the included templates I can save this step and do it on `cargo new` now.

## Usage

For a library project:

```
cargo new myproj --template https://github.com/badboy/cargo-template --template-subdir lib
```

For a binary project:

```
cargo new myproj --template https://github.com/badboy/cargo-template --template-subdir bin
```

## Included templates

* `bin`: The default binary template, extended with links to documentation, repository, homepage, a MIT license and badges in the README.
* `lib`: The default library template, extended with links to documentation, repository, homepage, a MIT license and badges in the README.
