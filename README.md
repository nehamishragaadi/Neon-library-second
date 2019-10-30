# react-native-neon-library-second

## Getting started

`$ npm install react-native-neon-library-second --save`

### Mostly automatic installation

`$ react-native link react-native-neon-library-second`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-neon-library-second` and add `NeonLibrarySecond.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libNeonLibrarySecond.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import com.reactlibrary.NeonLibrarySecondPackage;` to the imports at the top of the file
  - Add `new NeonLibrarySecondPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-neon-library-second'
  	project(':react-native-neon-library-second').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-neon-library-second/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-neon-library-second')
  	```


## Usage
```javascript
import NeonLibrarySecond from 'react-native-neon-library-second';

// TODO: What to do with the module?
NeonLibrarySecond;
```
