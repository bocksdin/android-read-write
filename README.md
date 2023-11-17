# android-read-write
Example project to get read/write working on Android with std::fs

## Steps to Reproduce
1. Connect Android phone via USB (Tested using S23+)
2. `cd executor-android`
3. `cargo-apk apk run --target=armv7-linux-androideabi`
4. Search terminal for `id.txt`

## Relevant code
https://github.com/bocksdin/android-read-write/blob/main/game/src/lib.rs#L33-L35
