# Calculator

![Appnail](https://github.com/user-attachments/assets/3cc3cd5f-eb25-42a1-9301-c329fb114d11)


Projetinho humilde para testar o aprendizado em React Native.

Após acompanhar umas aulas e criar uns apps seguindo elas, decidi criar um appzinho básico para ver se conseguia desenrolar sozinho. Seguindo as recomendações de projetos para iniciantes do site [InterviewbBit](https://www.interviewbit.com/blog/react-native-projects/), decidi fazer uma calculadora hehehe ;)

Sendo limitado em prototipar interfaces bonitas, segui um protótipo feito pelo Nikolay_melnik, disponibilizado no [Figma](https://www.figma.com/design/nxPTLl9M3umJR3r3teTt7S/Daily-UI-Challenge--004.-Calculator--Community-?node-id=1-599&p=f&t=1iZunDqywSeYY9BK-0).

![CalculatorThumbnail](https://github.com/user-attachments/assets/992c8548-b4a1-4c3c-9a80-ad98751c5882)

> Detalhe: o app possui apenas o tema claro!

# Getting Started

This is a [**React Native**](https://reactnative.dev) project, bootstrapped using [`@react-native-community/cli`](https://github.com/react-native-community/cli).

> **Note**: Make sure you have completed the [Set Up Your Environment](https://reactnative.dev/docs/set-up-your-environment) guide before proceeding.

## Step 0: Dependências do projeto

No diretório raiz do projeto, execute:

```sh
yarn add
```

## Step 1: Start Metro

First, you will need to run **Metro**, the JavaScript build tool for React Native.

To start the Metro dev server, run the following command from the root of your React Native project:

```sh
# using Yarn
yarn start
```

## Step 2: Build and run your app

With Metro running, open a new terminal window/pane from the root of your React Native project, and use one of the following commands to build and run your Android or iOS app:

### Android

```sh
# using Yarn
yarn android
```

### iOS | Eu não testei em ambiente IOS

For iOS, remember to install CocoaPods dependencies (this only needs to be run on first clone or after updating native deps).

The first time you create a new project, run the Ruby bundler to install CocoaPods itself:

```sh
bundle install
```

Then, and every time you update your native dependencies, run:

```sh
bundle exec pod install
```

For more information, please visit [CocoaPods Getting Started guide](https://guides.cocoapods.org/using/getting-started.html).

```sh
# using Yarn
yarn ios
```

If everything is set up correctly, you should see your new app running in the Android Emulator, iOS Simulator, or your connected device.

This is one way to run your app — you can also build it directly from Android Studio or Xcode.
