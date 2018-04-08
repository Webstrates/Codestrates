# Codestrates

[Codestrates](http://codestrates.org) is a literate computing approach to developing interactive software inspired by interactive notebooks such as [Jupyter notebook](http://jupyter.org). However, in Codestrates, real-time collaboration is built in, it is possible to create stand-alone applications with persistent state, and to reprogram the functionality of the environment it self.

Codestrates builds on [Webstrates](http://webstrates.net). A web-page served from a Webstrates server is called a _webstrate_, and is a web-page where changes to the document object model (DOM) are persisted to the server and synchronized with other clients of the same page.

A codestrate is a webstrate that contains everything needed for developing new content, or reprogramming the codestrate it self. So, Codestrates provides a literate computing based development environment for Webstrates.
On [codestrates.org](http://codestrates.org) you can learn more about the Codestrates research project. Visit [webstrates.net](http://webstrates.net) to learn more about Webstrates.

## Installation

To use Codestrates you need access to a [Webstrates](http://webstrates.net) server. Refer to the [Webstrates documentation](http://webstrates.github.io) for instructions on how to set one up.
To create a new codestrate on a Webstrates server go to:

```
https://yourserver.com/new?prototypeUrl=https://github.com/Webstrates/Codestrates/archive/master.zip
```

You can also [click here](https://demo.webstrates.net/new?prototypeUrl=https://github.com/Webstrates/Codestrates/archive/master.zip) to create a new codestrate on the [demo.webstrates.net](demo.webstrates.net) server.

### Codestrate Packages

The codestrate prototype in this repository provides the basic functions to use Codestrates. For extended features like a drawing canvas or collaboration features Codestrates uses a package system: Features can be added and removed from a codestrate. See the [Codestrate Packages](https://github.com/Webstrates/Codestrate-Packages) repository for basic packages and more information.

## Disclaimer

Codestrates is a research prototype in active development. Many features are still experimental and yet to be properly documented.

---

<p align="center">&copy;&nbsp;2017&nbsp;Aarhus&nbsp;University</p>
