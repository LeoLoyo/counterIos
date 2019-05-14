
# react-native-counter

## Getting started

`$ npm install react-native-counter --save`

### Mostly automatic installation

`$ react-native link react-native-counter`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-counter` and add `RNCounter.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNCounter.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNCounterPackage;` to the imports at the top of the file
  - Add `new RNCounterPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-counter'
  	project(':react-native-counter').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-counter/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-counter')
  	```


## Usage
```javascript
import RNCounter from 'react-native-counter';

// TODO: What to do with the module?
RNCounter;
```
  