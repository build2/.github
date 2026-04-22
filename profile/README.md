`build2` is an open source (MIT), cross-platform build toolchain that aims to
approximate Rust Cargo's convenience for developing and packaging C/C++
projects while providing more depth and flexibility, especially in the build
system.

At the core of the `build2` project is a hierarchy of tools consisting of a
general-purpose [build system](https://github.com/build2/build2), [package
manager](https://github.com/build2/bpkg) (for package consumption), and
[project manager](https://github.com/build2/bpkg) (for project development).
Plus there is a number of additional components and services, such as
[cppget.org](https://cppget.org), the central repository/registry of open
source packages. See [_What is `build2`?_](https://build2.org/faq.xhtml#what)
for the more detailed picture.
