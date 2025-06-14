## 0.5.7 (2025-06-14)

### Improvements

- Improved socket connection logic.

## 0.5.6 (2025-06-10)

### Features

- Added support for network pre-authorization which should improve the reliability of connections to the Master Node
  Network.

## 0.5.5 (2025-05-28)

### Improvements

- Added a toast notification to inform the user of a network error before the application closes itself.

### Fixes

- Fixed an issue that would prevent an already running instance of the application from being shown if the user
  attempted to start a new instance of the application while the first instance was already running.
    - Developer note: This would occur if the user had the "minimize to system tray" option enabled, and the user
      attempted to launch the application from the executable. Instead of bringing the original instance to the
      foreground, it would appear to do nothing at all.

## 0.5.4 (2025-05-27)

### Fixes

- Fixed an issue that would prevent the application from recognizing that it was disconnected from the network.

## 0.5.3 (2025-05-27)

### Fixes

- Fixed an issue that prevented authentication via wallet signature.
- Fixed an issue that caused inconsistent logout behavior.

## 0.5.2 (2025-05-27)

### Features

- Added the functionality to authenticate with a license key.
- Added a warning to notify if the current version is unsupported.

### Fixes

- Fixed an issue that would prevent the application from reconnecting to the Master Node Network after a disconnection.
- Fixed an issue that caused the displayed uptime to consistently be inconsistent with the actual uptime of the Master
  Node.
- Fixed an issue that prevented the application from revalidating its session if the session became invalid.
- Fixed an issue that prevented the application from righting itself after it had become disconnected from the Master
  Node Network.
    - Developer note: This was a separate issue from the first one mentioned in this list, where in some cases the
      application would disconnect from the network but not realize it had done so, and would be left in a state where
      it thought it was still connected but was not.
- Fixed an issue that would cause the application to not be able to reconnect to an existing session if the Master Node
  network was interrupted briefly.

## 0.5.1 (2025-03-27)

### Fixes


- Post-build startup error preventing the application from
  launching ([7888bacdc](https://github.com/playa3ull/playa3ull-ecosystem/commit/7888bacdc))

## 0.5.0 (2025-03-27)

### Features


- Minimize to system tray on close or on
  minimize ([e52f3ea55](https://github.com/playa3ull/playa3ull-ecosystem/commit/e52f3ea55))

- Run on startup by default and toggle in
  preferences ([bce81d1c6](https://github.com/playa3ull/playa3ull-ecosystem/commit/bce81d1c6))

- New options menu for saving/loading user
  preferences ([a04b0ad24](https://github.com/playa3ull/playa3ull-ecosystem/commit/a04b0ad24))

### ❤️ Thank You

- Jourdan Haines @jourdanhaines

## 0.4.3 (2025-03-18)

Initial public release of the PLAYA3ULL GAMES Master Node Software.

This version includes the following features:

- Authentication and connection to the PLAYA3ULL GAMES Master Node Network
- Monitor uptime and performance of your Master Node
- View and monitor network activity

This initial release only requires you to run a single Master Node for your account.

### ❤️ Thank You

- Jourdan Haines @jourdanhaines
- Sam Thompson-Kennedy @samthompsonkennedy