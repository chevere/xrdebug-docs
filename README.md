---
home: true
heroImage: /logo.svg
heroText: XR Debug
tagline: Lightweight debug utility for PHP.
actionText: Introduction →
actionLink: /introduction/
features:
- title: 😌 Easy to use
  details: Full-featured with a gorgeous user interface.
- title: 🍒 Portable & HTML based
  details: One-click server run. No extra dependencies.
- title: 🦄 Beautiful
  details: Yet another debugger, but it looks danky!
footer: Made by Rodolfo Berrios
---

# Quick start

* Install using [Composer](https://getcomposer.org/)

```sh
composer require --dev chevere/xr
```

* Once installed the XR Debug [helpers](helpers/README.md) will be ready to use
* Run the XR Debug [server](server/README.md)

```sh
docker run -t --init --rm ghcr.io/chevere/xr-server
```

* Open [localhost:27420](http://localhost:27420) and profit!

<video width="100%" poster="./src/social/github.jpg" controls>
    <source src="./src/video/cremino.mp4" type="video/mp4">
</video>
