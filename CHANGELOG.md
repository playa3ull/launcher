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
- Fixed and issue that would cause the application to not be able to reconnect to an existing session if the Master Node
  network was interrupted briefly.

## 0.5.1 (2025-03-27)

### 🩹 Fixes

- Post-build startup error preventing the application from
  launching ([7888bacdc](https://github.com/playa3ull/playa3ull-ecosystem/commit/7888bacdc))

## 0.5.0 (2025-03-27)

### 🚀 Features

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