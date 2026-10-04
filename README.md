# ZEVEX Cashier

Companion app for zevex.in UPI gateway. Google Pay Business aur PhonePe Business
notifications ko padh kar server ko payment events push karta hai (auto-verify).

## Build

Ye repo GitHub pe push karo, `.github/workflows/build.yml` khud APK bana dega.
APK milega: Actions tab -> latest run -> Artifacts -> `zevex-cashier`.

## Install

1. APK download karo
2. "Unknown sources" allow karo, install karo
3. App kholo:
   - API base = `https://zevex.in`
   - App = Google Pay ya PhonePe
   - Server code (website se) daalo -> Register
4. App Code copy karke website modal me paste -> Verify
5. App me "Notification access" aur "Battery optimization off" dono ON karo