# react-native-mac-setup
Set up your React Native environment on a macOS

---

### Environment
```
$ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
$ brew install node
$ brew install watchman
$ brew tap AdoptOpenJDK/openjdk
$ brew install adoptopenjdk8
$ npm install -g react-native-cli
$ sudo chown -R $USER /usr/local/lib/node_modules
$ npm install -g react-native-cli
$ sudo gem install cocoapods
```

### Create App

```
$ react-native init first_app
$ cd first_app/
$ react-native run-ios
```

---

![Welcome to React Native](“https://perihelion.co.jp/assets/images/Welcome-to-React-Native.png”)