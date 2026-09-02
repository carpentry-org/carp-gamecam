# carp-gamecam
A high-performance 3D perspective camera for the Carp programming language.

## Features
- **Standardized**: Uses Carp's internal `Vector3` library for seamless integration with the ecosystem.
- **WGPU Ready**: Generates 4x4 matrices in column-major order, compatible with modern graphics APIs.
- **LookAt & Perspective**: Standard functions for generating View and Projection matrices.
- **FlyCam Support**: Integrated Yaw/Pitch orientation logic for easy 3D navigation.

## Installation
```clojure
(load "git@github.com:carpentry-org/carp-gamecam@master")
```


## Examples

See [examples.md](examples.md) for usage examples, and the
[API documentation](https://carpentry.dev/carp-gamecam) for the full reference.
## License
MIT
