# jnitrace Change Log

## 1.3.0
- Added a command argument to get the version of jnitrace
- jnitrace now intercepts calls to GetJavaVM, returning a shadowJavaVM
- Added support for extracting arguments stored in jvalue arrays

## 1.2.1
- Bug fix - CallStaticObjectMethod was the only va args method intercepted

## 1.2.0
- Added arm64 architecture support
- Modified how dlopen is intercepted to support Android 7 and above