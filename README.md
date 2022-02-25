# AR Driving Car

## Installation

1. `git clone
3. `npm install`
4. `npx pod-install` (iOS)
5. `npx react-native run-android` or `npx react-native run-ios`

NOTE: The variant arguments are not needed for debug or release.

## Issues

Mulit-touch is not working on Android, so you can't control the steering wheel and the pedals at the same time.

Also has a yellow console warning:
Warning: Cannot update during an existing state transition (such as within `render`). Render methods should be a pure function of props and state.
