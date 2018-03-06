# conan-paho-c

![conan-paho-c image](/images/conan-paho-c.png)

[![Download](https://api.bintray.com/packages/conan-community/conan/paho-c%3Aconan/images/download.svg)](https://bintray.com/conan-community/conan/paho-c%3Aconan/_latestVersion)
[![Build status](https://ci.appveyor.com/api/projects/status/jyeh443gn0l0f3bi/branch/stable/1.2.0?svg=true)](https://ci.appveyor.com/project/danimtb/conan-paho-c/branch/stable/1.2.0)

[Conan.io](https://conan.io) package for [paho-c](https://bitbucket.org/paho-c/paho-c) project

The packages generated with this **conanfile** can be found in [Bintray](https://bintray.com/conan-community/conan/paho-c%3Aconan).

## For Users: Use this package

### Basic setup

    $ conan install paho-c/1.2.0@conan/stable

### Project setup

If you handle multiple dependencies in your project is better to add a *conanfile.txt*

    [requires]
    paho-c/1.2.0@conan/stable

    [generators]
    txt
    cmake

## License

[MIT License](LICENSE)