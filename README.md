# tl;dr

- 🌱 Ecologist 
- 🕸 WebAssembly polyglot 
- 🦀 Rust nerd
-  👾 Hacker
-  🎓 PhD Computer Scientist
-  🤲 Open source lover 
- 🙈 Parser, compiler, low-level, binding, VM/runtime, Web, home automation, embedded…
-  🚀 R&D [Element](https://element.io/)/[Matrix](https://matrix.org/), the decentralized, end-to-end encrypted, open source network
-  📜 Formerly [Wasmer](https://github.com/wasmerio) (WebAssembly runtime), [Automattic](https://github.com/automattic), [fruux](https://fruux.com/), [Mozilla](https://mozilla.org) (Firefox)… I like the change and new challenges
- 🏠 Living in the stack, in a weird ABI, lost in FFI land
- Mastodon: <a rel="me" href="https://fosstodon.org/@hywan">@hywan</a>

## Serious projects at work

### 💬 [Matrix](https://github.com/matrix-org)

A new basis for open, interoperable, decentralised, end-to-end encrypted, real-time communication.

I currently work on the [Matrix Rust SDK](https://github.com/matrix-org/matrix-rust-sdk) 🦀.

### 🕸 [Wasmer](https://github.com/wasmerio)

[Wasmer](https://github.com/wasmerio/wasmer) is one of the major and leading WebAssembly runtime out there.

I have co-founded this project, and [sadly left it](https://mnt.io/2021/10/04/i-leave-wasmer/).
I've greatly contributed to the runtime itself:

* Worked on 3 compilers: Singlepass, Cranelift and LLVM,
* Worked on the 3 engines: JIT, shared object file, static object file, and the VM core,
* Worked on the public API, documentation, examples, well… everything!

In addition to the runtime, I have created many bindings:

* [`wasmer-c-api`](https://github.com/wasmerio/wasmer/tree/master/lib/c-api) is the C embedding for Wasmer,
* [`wasmer-python`](https://github.com/wasmerio/wasmer-python) for Python,
* [`wasmer-go`](https://github.com/wasmerio/wasmer-go/) for Go with its post: _[Announcing the fastest WebAssembly runtime for Go: wasmer](https://mnt.io/2019/05/29/announcing-the-fastest-webassembly-runtime-for-go-wasmer/)_,
* [`wasmer-ruby`](https://github.com/wasmerio/wasmer-ruby/) for Ruby,
* [`wasmer-php`](https://github.com/wasmerio/wasmer-php) for PHP with its post: _[🐘+🦀+🕸 php-ext-wasm: Migrating from wasmi to Wasmer](https://mnt.io/2019/04/03/%f0%9f%90%98%f0%9f%a6%80%f0%9f%95%b8-php-ext-wasm-migrating-from-wasmi-to-wasmer/)_,
* [`wasmer-java`](https://github.com/wasmerio/wasmer-java) for Java with its post: _[Announcing the first Java library to run WebAssembly: Wasmer JNI](https://mnt.io/2020/05/13/announcing-the-first-java-library-to-run-webassembly-wasmer-jni/)_,
* [`wasmer-postgres`](https://github.com/wasmerio/wasmer-postgres) for PostgreSQL with its post: _[Announcing the first Postgres extension to run WebAssembly](https://mnt.io/2019/08/29/announcing-the-first-postgres-extension-to-run-webassembly/)_.

Notable fun projects I did there:

* [`sonde-rs`](https://github.com/wasmerio/sonde-rs) is a library to compile USDT probes into a Rust library,
* [`llvm-custom-builds`](https://github.com/wasmerio/llvm-custom-builds) is a sandbox to product custom LLVM builds for various platforms,
* [`loupe`](https://github.com/wasmerio/loupe) is a set of tools to analyse and to profile Rust code,
* [`inline-c-rs`](https://github.com/Hywan/inline-c-rs/), to write and to execute C code inside Rust,
* and much more.

### [Automattic](https://github.com/automattic)

[Automattic](https://automattic.com) is the company behind WordPress.com,
Tumblr, WooCommerce, JetPack, Akismet, Simplenote, Longreads, Gravatar etc.

One notable open source project I have worked on is [a parser for Gutenberg](https://github.com/Hywan/gutenberg-parser-rs),
in Rust, that compiles to many targets: WebAssembly, C, PHP, Node.js etc. It
led to a blog post series:
[From Rust to beyond](https://mnt.io/2018/08/21/from-rust-to-beyond-prelude/).

### Research

* [_Contract-based testing for PHP with Praspel_](https://doi.org/10.1016/j.jss.2017.06.017),
  Dadeau, Giorgetti, Bouquet, Enderlin; Journal of Systems and Software, Volume 136, 2018.
* My PhD thesis: [_Automatic generation of unit tests with Praspel, a specification langauge for PHP](https://hal.inria.fr/tel-01093355v2/document),
  Enderlin, 2014.
* [_A Constraint Solver for PHP Arrays_](https://hal.archives-ouvertes.fr/hal-00935308/document),
  Enderlin, Giorgetti, Bouquet; ICST Workshops, 2013.
* [_Grammar-Based Testing using Realistic Domains in PHP_](https://hal.archives-ouvertes.fr/hal-00931662/document),
  Enderlin, Dadeau, Giorgetti, Bouquet; A-MOST 2012, 8th Workshop on
  Advances in Model Based Testing, joint to the ICST'12 IEEE, Software Testing,
  Verification and Validation, 2012.
* [_Praspel: A Specification Language for Contract-Driven Testing in PHP_](https://link.springer.com/content/pdf/10.1007/978-3-642-24580-0_6.pdf),
  Enderlin, Dadeau, Giorgetti, Ben Othman, International Conference on Testing Software and Systems, 2011.

## Pet projects

### [Hoa](https://github.com/hoaproject)

It is a set of modular, extensible and structured set of PHP libraries; aiming at
being a bridge between industrial and research worlds. More than 165 millions
installations, but projects are archived after 15 years of joy.

### [La Maison Vivante](https://github.com/Hywan/LaMaisonVivante)

My wife and I have built a self-sufficient house, made of straw, wood
and earth. This repository contains all the program I'm using for
the home automation. But the most important readings are at
[https:// lamaisonvivante.blog](https://lamaisonvivante.blog), our blog describing our
adventure!

### [Atlasr](https://github.com/atlasr-org/atlasr)

It is a truly open-source and free map browser.
