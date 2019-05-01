# JARLReactApp

## Current Arduino API
* Use: https://github.com/adafruit/Adafruit_nRF8001/tree/1.1.1
* Each button has code corresponding to it (`f`, `b`, `l`, `r`, `u`, `d`, `s`)
* On pressIn sends `code`+`1`
* On pressOut sends `code`+`0`
* Example: `f1`, `f0`, `s1`, `s0`, etc.

## Tips and Tricks from many tears
* Use this guide if you want to debug UI: https://facebook.github.io/react-native/docs/debugging#react-developer-tools
* Use this site to edit UI: https://snack.expo.io/
* Use `react-native log-android` to read logs
* Use https://facebook.github.io/react-native/docs/getting-started with the native CLI + Windows + Android to install dependencies and run code (`react-native run-android`)
