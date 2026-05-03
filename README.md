Life Signal v0.1 — Expo Router App Shell

This is a starter app shell for the Life Signal / Action Radar concept.

## Run

```bash
npx create-expo-app@latest life-signal --template default@sdk-55
cd life-signal
npx expo install expo-router react-native-safe-area-context react-native-screens expo-linking expo-constants expo-status-bar
npx expo install @expo/vector-icons
```

Then copy the `app/` and `src/` folders from this package into the created project and run:

```bash
npx expo start
```

For Android emulator press `a` in the Expo terminal.

## v0.1 scope

- Android-first Expo shell
- Expo Router tabs
- Inbox
- Radar
- Vault
- Item detail
- Context AI chat mock panel
- Mock data
- Shared TypeScript domain model


## Notes

Signal cards use `Link` + `Pressable` so card taps work correctly on Android.
