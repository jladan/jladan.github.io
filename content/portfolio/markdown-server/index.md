+++
title = "Markdown server (Rust)"
description = "Filesystem webserver for notes"
date = "2023-11-06"
jobDate = 2023
work = []
techs = ["Rust", "Javascript"]
designs = []
thumbnail = "markdown-server/screenshot.png"
projectUrl = ""
# testimonial =""
#   name = ""
#   role = ""
#   image = ""
#   text = ""
+++

In a quest to take better notes, and organize my life, I've begun using a
[Zettelkasten method](https://zettelkasten.de/introduction/).
The most common tool for this is [Obsidian](https://obsidian.md/), which is
quite good, but doesn't integrate well with my preferred workflow. Notably:
- using [neovim](https://neovim.io/) to edit and create files
- storing everything on my local server over VPN

To get closer to that goal, I wrote a webserver to browse files, and render
markdown. This also provided a good project to learn how to program in
[Rust](https://www.rust-lang.org/).

There are two implementations:
- [Simple markdown server](https://github.com/jladan/simple-markdown-server)
  (archived) --
  very simple, implemented with a synchronous runtime and threadpool
- [Hyper markdown server](https://github.com/jladan/hyper-markdown-server) --
  implemented with an async runtime ([tokio](https://tokio.rs/)), and the
  [hyper](https://crates.io/crates/hyper) library for http requests.

The server provides:
- a full directory listing and browser
- rendering of markdown files
- support for images and pdf files

Because it was a learning exercise, I chose to use lower-level libraries rather
than frameworks like Axum or Actix.
The downside of not using a higher-level framework is that I don't get easy
access to middleware like authorization or tracing. However, this is intended to
run locally with only get requests, so that's fine for my purposes.
