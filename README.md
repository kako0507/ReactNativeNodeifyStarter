# ReactNativeNodeifyStarter
a React Native starter allow you to use node core modules, and npm modules that use them

## Installation

  ```sh
  # install node modules
  yarn install
  # install node core shims and recursively hack package.json files
  # in ./node_modules to add/update the "browser"/"react-native" field with relevant mappings
  ./node_modules/.bin/rn-nodeify --hack --install --yarn
  ```
