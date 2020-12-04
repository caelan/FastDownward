# FastDownward

A slightly modified version of Fast Downward.

## Information

Fast Downward is a domain-independent planning system.

For documentation and contact information see http://www.fast-downward.org/.

The following directories are not part of Fast Downward as covered by this
license:

* ./src/search/ext

For the rest, the following license applies:

```
Fast Downward is free software: you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

Fast Downward is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with
this program. If not, see <http://www.gnu.org/licenses/>.
```

## Installation

Run the following commands:
```
$ git clone https://github.com/caelan/FastDownward.git
$ cd FastDownward
$ python ./build.py
```

Many development systems already satisfy FastDownward's dependencies. If `./build.py` fails, install FastDownward's dependencies using your package manager:
* APT (Linux): `$ sudo apt-get install cmake g++ g++-multilib make python`
* Homebrew (OS X): TBD
* MacPorts (OS X): TBD
* Windows:
    1. Install VS Studio Build Tools by downloading and running the executable from [here](https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=BuildTools&rel=16). Select the `C++ Build Tools` option in the installer.
    2. Install [CMake](https://cmake.org/) in your python environment by `pip install cmake`.
    3. Search for `Developer Command Prompt for VS 2017` in your search bar and run it.
    4. In the Developer Command Prompt for VS 2017, issue:
        ```
        cd /d "<path to FastDownward>"
        python ./build.py
        ```

If necessary, see FastDownward's documentation for more detailed installation instructions:

http://www.fast-downward.org/ObtainingAndRunningFastDownward

## Citation

Malte Helmert.
The Fast Downward Planning System.
Journal of Artificial Intelligence Research 26, pp. 191-246. 2006. 
