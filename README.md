# mruby interpreter that runs in your browser

Made possible thanks to [Webruby](https://github.com/xxuejie/webruby), a project that brings together llvm, emscripten and mruby.

# [Live Demo](http://joshnuss.github.io/mruby-web-irb)

# Prerequisites

- llvm
- emscripten

See [webruby](https://github.com/xxuejie/webruby) for installation instructions

# Installation

Run bundler to get webruby, sass etc..:

  > bundle

# Compiling

To compile `webruby.js`:

  > rake

# Stylesheets

Generate using compass:

  > compass compile

or

  > compass watch
