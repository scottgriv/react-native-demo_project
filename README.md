<!-- Begin README -->

<div align="center">
    <a href="https://github.com/scottgriv/react-native-demo_project" target="_blank">
        <img src="./docs/images/icon.png" width="150" height="150" /> <br />
        <img src="./docs/images/ios.png" width="150" height="150" /><img src="./docs/images/android.png" width="125" height="125" />
    </a>
</div>
<br>
<p align="center">
    <a href="https://reactnative.dev"><img src="https://img.shields.io/badge/React Native-0.74.3-61DAFB?style=for-the-badge&logo=react" alt="React Badge" /></a>
    <br>
    <a href="https://github.com/scottgriv"><img src="https://img.shields.io/badge/github-follow_me-181717?style=for-the-badge&logo=github&color=181717" alt="GitHub Badge" /></a>
    <a href="mailto:scott.grivner@gmail.com"><img src="https://img.shields.io/badge/gmail-contact_me-EA4335?style=for-the-badge&logo=gmail" alt="Email Badge" /></a>
    <a href="https://www.buymeacoffee.com/scottgriv"><img src="https://img.shields.io/badge/buy_me_a_coffee-support_me-FFDD00?style=for-the-badge&logo=buymeacoffee&color=FFDD00" alt="BuyMeACoffee Badge" /></a>
    <br>
    <a href="https://prgportfolio.com" target="_blank"><img src="https://img.shields.io/badge/PRG-Bronze Project-CD7F32?style=for-the-badge&logo=data:image/svg%2bxml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI/Pgo8IURPQ1RZUEUgc3ZnIFBVQkxJQyAiLS8vVzNDLy9EVEQgU1ZHIDIwMDEwOTA0Ly9FTiIKICJodHRwOi8vd3d3LnczLm9yZy9UUi8yMDAxL1JFQy1TVkctMjAwMTA5MDQvRFREL3N2ZzEwLmR0ZCI+CjxzdmcgdmVyc2lvbj0iMS4wIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciCiB3aWR0aD0iMjYuMDAwMDAwcHQiIGhlaWdodD0iMzQuMDAwMDAwcHQiIHZpZXdCb3g9IjAgMCAyNi4wMDAwMDAgMzQuMDAwMDAwIgogcHJlc2VydmVBc3BlY3RSYXRpbz0ieE1pZFlNaWQgbWVldCI+Cgo8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjAwMDAwMCwzNC4wMDAwMDApIHNjYWxlKDAuMTAwMDAwLC0wLjEwMDAwMCkiCmZpbGw9IiNDRDdGMzIiIHN0cm9rZT0ibm9uZSI+CjxwYXRoIGQ9Ik0xMiAzMjggYy04IC04IC0xMiAtNTEgLTEyIC0xMzUgMCAtMTA5IDIgLTEyNSAxOSAtMTQwIDQyIC0zOCA0OAotNDIgNTkgLTMxIDcgNyAxNyA2IDMxIC0xIDEzIC03IDIxIC04IDIxIC0yIDAgNiAyOCAxMSA2MyAxMyBsNjIgMyAwIDE1MCAwCjE1MCAtMTE1IDMgYy04MSAyIC0xMTkgLTEgLTEyOCAtMTB6IG0xMDIgLTc0IGMtNiAtMzMgLTUgLTM2IDE3IC0zMiAxOCAyIDIzCjggMjEgMjUgLTMgMjQgMTUgNDAgMzAgMjUgMTQgLTE0IC0xNyAtNTkgLTQ4IC02NiAtMjAgLTUgLTIzIC0xMSAtMTggLTMyIDYKLTIxIDMgLTI1IC0xMSAtMjIgLTE2IDIgLTE4IDEzIC0xOCA2NiAxIDc3IDAgNzIgMTggNzIgMTMgMCAxNSAtNyA5IC0zNnoKbTExNiAtMTY5IGMwIC0yMyAtMyAtMjUgLTQ5IC0yNSAtNDAgMCAtNTAgMyAtNTQgMjAgLTMgMTQgLTE0IDIwIC0zMiAyMCAtMTgKMCAtMjkgLTYgLTMyIC0yMCAtNyAtMjUgLTIzIC0yNiAtMjMgLTIgMCAyOSA4IDMyIDEwMiAzMiA4NyAwIDg4IDAgODggLTI1eiIvPgo8L2c+Cjwvc3ZnPgo=" alt="Bronze" /></a>
</p>

---

<h1 align="center">React Native Demo Project</img></h1>

This is a React Native application designed to run on both iOS and Android platforms. The app leverages React Native's components and ecosystem to provide a seamless mobile experience.

---

## Table of Contents

- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Scripts](#scripts)
- [Resources](#resources)
- [License](#license)
- [Credits](#credits)

## Getting Started

### Installation

To get started with this project, follow these steps:

1. Clone the repository:

```shell
https://github.com/scottgriv/react-native-demo_project.git
```

2. Navigate to the project directory:

```shell
cd react-native-demo_project/DemoProject

```
3. Install the dependencies:

```shell
npm install
```

4. Install CocoaPods (for iOS):

Navigate to the ios directory and install the pods:

```shell
cd ios
pod install
cd ..
```

5. Install Xcode (for iOS):

Ensure you have Xcode installed from the [Mac App Store](https://apps.apple.com/us/app/xcode/id497799835?mt=12).

6. Install Android Studio (for Android):

Download and install [Android Studio](https://developer.android.com/studio). Make sure to set up the Android SDK and add it to your `PATH`.

7. Diagnose Potential Issues:

Use `npm doctor` to check your environment for any potential issues:

```shell
npm doctor
```

> [!IMPORTANT]
> The `DemoProject` is the root project directory.

### Usage

To run the app, use the following commands:

- For iOS:

```shell
npm run ios
```

- For Android:

```shell
npm run android
```

### Scripts

The available scripts in this project are:

* `npm start`: Starts the Metro bundler.
* `npm run ios`: Runs the app on an iOS simulator.
* `npm run android`: Runs the app on an Android emulator.
* `npm run lint`: Lints the code for potential issues.

## Resources

**React Native**

- [React Native Official Site](https://reactnative.dev)
- [React Native Official Documentation](https://reactnative.dev/docs/getting-started)
- [Expo Documentation](https://docs.expo.dev/)
- [React Navigation](https://reactnavigation.org/)
- [React Native Elements](https://reactnativeelements.com/)
- [Awesome React Native](https://github.com/jondot/awesome-react-native)

**Other**

- [JavaScript ES6 Features](https://www.w3schools.com/js/js_es6.asp)
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)
- [Styled Components](https://styled-components.com/docs)
- [Mac App Store - Xcode](https://apps.apple.com/us/app/xcode/id497799835?mt=12)
- [Android Studio](https://developer.android.com/studio)

## License

This project is released under the terms of **The Unlicense**, which allows you to use, modify, and distribute the code as you see fit.

- [The Unlicense](https://choosealicense.com/licenses/unlicense/) removes traditional copyright restrictions, giving you the freedom to use the code in any way you choose.
- For more details and to understand all requirements and conditions, see the [LICENSE](docs/LICENSE/Unlicense/LICENSE) file in this repository.

## Credits

**Author:** [Scott Grivner](https://github.com/scottgriv) <br>
**Email:** [scott.grivner@gmail.com](mailto:scott.grivner@gmail.com) <br>
**Website:** [scottgrivner.dev](https://www.scottgrivner.dev) <br>
**Reference:** [Main Branch](https://github.com/scottgriv/react-native-demo_project) <br>

---

<div align="center">
    <a href="https://github.com/scottgriv" target="_blank">
        <img src="./docs/images/footer.png" width="100" height="100"/>
    </a>
</div>

<!-- End README -->
