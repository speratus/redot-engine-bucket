# Redot Engine Scoop Bucket

<!-- Uncomment the following line after replacing placeholders -->
[![Tests](https://github.com/speratus/redot-engine-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/speratus/redot-engine-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/speratus/redot-engine-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/speratus/redot-engine-bucket/actions/workflows/excavator.yml)

Redot is a community-driven 2D and 3D game engine based on Godot. This
repository is a [Scoop](https://scoop.sh) bucket for installing Redot and other
related tools.

## How do I install these manifests?

Once you have Scoop installed, installing Redot is easy:

```pwsh
scoop bucket add redot https://github.com/speratus/redot-engine-bucket
scoop install redot/redot-engine
```

## A Note on Supported Architectures

This bucket currently does not provide arm64 or 32-bit architecture support.
The Redot maintainers have opted not to provide pre-built binaries for 32-bit
and arm64 architectures because these architectures accounted for very low
percentages of the total downloads of Redot.

The Redot mainteners informed me that those architectures for Windows are
supported, but that users wishing to use them will have to build Redot
from source for those architectures.

If you would like to use Redot on an arm64 or 32-bit Windows machine, you
can find the documentation for building from source
[here](https://docs.redotengine.org/en/stable/contributing/development/compiling/compiling_for_windows).

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
