# libplctag Allen Bradley

libplctag supports multiple languages, c, csharp, java, amongst other ones. Checkout the repo for more information.

## Repositories Credits:

- [libplctag](https://github.com/kyle-github/libplctag)
- [csharp wrapper](https://github.com/mesta1/libplctag-csharp)

Both repos have sample code.

## Notes on Building libplctag

The [guide](https://github.com/kyle-github/libplctag/blob/master/BUILD.md) on [libplctag repo](https://github.com/kyle-github/libplctag) is pretty good. I have copied it also inside the docs folder in this repo for good measure.

I've compiled on Windows 10 with Visual Studio 2017.

Things needed
- Visual Studio 2017
- CMake for Windows
- Git

I ran the cmake command for my version 2017:

```
cmake -G "Visual Studio 14 2015 Win64"
cmake -G "Visual Studio 15 2017 Win64"
```

[Full List of Generators](https://cmake.org/cmake/help/v3.7/manual/cmake-generators.7.html)

Then you can open the visual studio project by opening the libplctag_project.sln file, and building for your platform with visual studio.

The compiled DLLs are inside x64 and x86 folders respectively.

List of resources on this subject:

- [CMake Visual Studio Tutorial](https://www.codeproject.com/Articles/1181455/A-CMake-tutorial-for-Visual-Cplusplus-developers)
- [Microsoft Cmake Projects](https://docs.microsoft.com/en-us/cpp/build/cmake-projects-in-visual-studio?view=vs-2017)