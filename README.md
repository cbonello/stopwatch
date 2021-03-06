# stopwatch

A simple stopwatch for a fitness app.

## Screenshots

Stopwatch Running | Stopwatch Stopped
--- | ---
![Running](/docs/running.png?raw=true "Running") | ![Stopped](/docs/stopped.png?raw=true "Stopped")

## Implementation

- [flutter_bloc](https://pub.dev/packages/flutter_bloc) for state management.

Code was tested on Android, Windows desktop and Flutter web.

The `stopwatch running in the background functionality` can be tested by doing a
hot restart (if running on an emulator).

## Testing

```bash
$ flutter test test
00:08 +7: All tests passed!
```
