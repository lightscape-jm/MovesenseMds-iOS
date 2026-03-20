# MovesenseMds-iOS (Fork)

Movesense Device Service (MDS) is an Objective-C API for communicating with Movesense sensors via Bluetooth LE.

This is a fork of [mikkojeronen/MovesenseMds-iOS](https://github.com/mikkojeronen/MovesenseMds-iOS), used by the [Movesense Dive Telemetry](https://github.com/lightscape-jm/Movesense-Dive-Telemetry) project — a scuba diving sensor data recording and analysis system.

This version is distributed via Swift Package Manager and wraps the pre-compiled MDS C++ binary framework (`MdsLib.xcframework`).

## Changes from Upstream

- **Updated `MdsLib.xcframework`** binary (reduced from ~50MB to ~24MB) to a newer version of the Movesense MDS library

## Original Source

The upstream versioning follows the Movesense CocoaPod from https://bitbucket.org/movesense/movesense-mobile-lib/src/master/.

## Integration

Add as a Swift Package dependency:
```
https://github.com/lightscape-jm/MovesenseMds-iOS.git
```
Branch: `main`
