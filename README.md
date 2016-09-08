# ActiveHashTag
[![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-ActiveHashTag-brightgreen.svg?style=flat)](http://android-arsenal.com/details/1/4303)

Android HashTag Lib.

Download
--------

Current version: [0.1.0]

Gradle:
```groovy
compile 'com.github.mugku:activehashtag:1.0.0'
```

###Test
![ScreenShot](pic/pic.gif)


## How to use

Test Start
```java
char[] additionalSymbols = new char[]{'_'};
ActiveHashTag editTextTag = ActiveHashTag.Factory.create(ResourcesCompat.getColor(this.getResources(), android.R.color.holo_blue_dark, null), null, additionalSymbols);
editTextTag.operate(editText);
``'
