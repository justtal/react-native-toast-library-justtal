
# react-native-toast-library-justtal

## Getting started

`$ npm install react-native-toast-library-justtal --save`

### Mostly automatic installation

`$ react-native link react-native-toast-library-justtal`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-toast-library-justtal` and add `RNReactNativeToastLibrary.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNReactNativeToastLibrary.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNReactNativeToastLibraryPackage;` to the imports at the top of the file
  - Add `new RNReactNativeToastLibraryPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-toast-library-justtal'
  	project(':react-native-toast-library-justtal').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-toast-library-justtal/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-toast-library-justtal')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNReactNativeToastLibrary.sln` in `node_modules/react-native-toast-library-justtal/windows/RNReactNativeToastLibrary.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using React.Native.Toast.Library.RNReactNativeToastLibrary;` to the usings at the top of the file
  - Add `new RNReactNativeToastLibraryPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNReactNativeToastLibrary from 'react-native-toast-library-justtal';

// TODO: What to do with the module?
RNReactNativeToastLibrary;
```
  