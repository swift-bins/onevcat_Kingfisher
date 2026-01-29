# Kingfisher (Binary)

Pre-built binary xcframeworks for [Kingfisher](https://github.com/onevcat/Kingfisher).

## Usage

Update your package dependency in `Package.swift`:

```swift
// Before (builds from source)
.package(url: "https://github.com/onevcat/Kingfisher", from: "8.6.2")

// After (uses pre-built binaries)
.package(url: "https://github.com/swift-bins/Kingfisher", from: "8.6.2")
```

**Note:** You also need to update your target dependency (package name changes):

```swift
// Before
.product(name: "Kingfisher", package: "Kingfisher")

// After
.product(name: "Kingfisher", package: "onevcat_Kingfisher")
```

## License

See [LICENSE](LICENSE) - sourced from the original repository.

## Original Repository

For documentation and source code, visit the original repo:
- README: https://github.com/onevcat/Kingfisher#readme
- Source: https://github.com/onevcat/Kingfisher
