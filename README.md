# NOTE

This project is a soft-fork of the `fourseven:scss`, simply replacing `node-sass` with the new, pure-JS implementation `sass` library. While we currently use the compatability methods in the `sass` library, they are stated deprecated and so we intend to migrate to their new methods in the future which may constitute a breaking change for the more heavy, advanced users of the library.

## Credit

All credit goes to the `fourseven:scss` library for the work to create this package. We are a very simply, very light fork of the project using a drop-in replacement for the deprecated `node-sass` library which causes many `node-gyp` headaches that are simply not worth solving.

## Installation

```bash
meteor add 67726e:scss
```
