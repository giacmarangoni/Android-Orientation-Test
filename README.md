# Android-Orientation-Test
An android orientation problem.

### GOAL: Disable landscape mode only on Android smartphones

Clone this project, build and run. Turn your device (simulated or physical smartphone) into landscape mode and then open a new activity.
You will notice that orientation will turn automatically into landscape mode (even though landscape it's disabled on smartphones thanks to  ```portrait_only``` property contained in bool.xml) and, after a while, It will come back into portrait mode.

## Additional notes

```
android:screenOrientation
```

This property cannot be used in order to preserve portrait or landscape orientation on tablets.

### A short gif about this kind of issue  ###

![alt tag](https://github.com/giacmarangoni/Android-Orientation-Test/blob/master/sample/sample.gif)
