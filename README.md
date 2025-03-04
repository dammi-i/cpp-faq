# C & C++ FAQ

An open source FAQ for C and C++, available at (temporary URL) [https://64.github.io/cpp-faq](https://64.github.io/cpp-faq).

The content of this repository (excluding software) is licensed under the [CC BY-SA 4.0 license](LICENSE.txt). The software itself is licensed under the [MIT license](LICENSE.txt). By contributing to this project, you agree to have your work licensed under these agreements.

⚠️ **This project is heavily WIP**: don't expect links here to work for long. Bugfixes and new FAQ entries are most welcome - see below.

## Contributing

First [install `hugo`](https://gohugo.io/getting-started/installing#readout).

Please read [`STYLE.md`](STYLE.md) to familiarize yourself with the style and tone in which articles should be written.

See [Projects/FAQ Articles](https://github.com/64/cpp-faq/projects/1) for a list of suggested topics to write about.

To create new articles - run `hugo new faq/my-faq-post.md`. This generates a file named `content/faq/my-faq-post.md` with the appropriate template. Add the content (in markdown format) below the bottom `---`. Hugo will be able to locate your content without any additional work.

## Building

1. [Install `hugo`](https://gohugo.io/getting-started/installing#readout).
2. Run `git submodules update --init` to download the theme if you haven't already
3. Run `hugo server -D` then navigate to [http://localhost:1313/cpp-faq/](http://localhost:1313/cpp-faq/) in your browser.
