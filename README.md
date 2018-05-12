# EsteidShellext

 * License: LGPL 2.1
 * &copy; Estonian Information System Authority
 * [Architecture of ID-software](http://open-eid.github.io)

Windows shell extension for signing and encrypting with DigiDoc client.</br>
Extracted from [DigiDoc3 Client](https://github.com/open-eid/qdigidoc).


## Building

1. Install dependencies from

 * [Visual Studio Community 2015](https://www.visualstudio.com/downloads/)
 * [http://www.cmake.org](http://www.cmake.org)
 * [Wix toolset](http://wixtoolset.org/releases/)

2. Fetch the source

        git clone --recursive https://github.com/open-eid/EsteidShellext
        cd EsteidShellext

3. Configure

        mkdir build
        cd build
        cmake -G"NMake Makefiles" ..

4. Build

        nmake
