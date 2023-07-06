
# react-native-g-toast

## Getting started

`$ npm install react-native-g-toast --save`

### Mostly automatic installation

`$ react-native link react-native-g-toast`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-g-toast` and add `RNGToast.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNGToast.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNGToastPackage;` to the imports at the top of the file
  - Add `new RNGToastPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-g-toast'
  	project(':react-native-g-toast').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-g-toast/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-g-toast')
  	```


## Usage
```javascript
import RNGToast from 'react-native-g-toast';

// TODO: What to do with the module?
RNGToast;
```
  