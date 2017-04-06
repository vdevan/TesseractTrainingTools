[![Build status](https://ci.appveyor.com/api/projects/status/nli486fa8syrwb0g?svg=true)](https://ci.appveyor.com/project/peirick/vs2015-tesseract)

# Visual Studio 2015 Projects for Tessearct and dependencies.
Training tools for Tesseract compilable under VS2015. This repository in addition to a copy of Tesseract sources, I have added projects & Solution for Visual Studio 2015. Training tools are now compilable under VS2015 for Windows. For those of you who need quick access to tools (and not a developer), I have provided binary files compiled from sources for Windows. I will maintain and add more tools for Version 4.0 soon.

## Note:
Goes without saying, All binaries are supplied AS-IS basis. No warranties or responsibilities borne by author. This is a community service and as such, any help would be limited and at the discretion of the author.

All Tesseract sources are supplied under Apache license-2.0. However this software depends on other packages that may be licensed under different open source licenses. Users are encouraged to read the licenses before distributing or using in their commercial products

## License:
The code in this repository is licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

## Used Repositories
* https://github.com/tesseract-ocr/tesseract Main Tesseract files
* https://github.com/tesseract-ocr/tesseract/tree/master/training Training Tools directory
* https://github.com/peirick/VS2015_Tesseract VS2015 Project Files related to libtesseract and leptonica project
* https://github.com/DanBloomberg/leptonica Source Files for Leptonica
* http://download.icu-project.org/files/icu4c/58.2/icu4c-58_2-src.zip International Components for Unicode (ICU) from IBM

## Used Libraries
* [Giflib 5.1.4](http://giflib.sourceforge.net/)
* [libtiff 4.0.7](http://simplesystems.org/libtiff/)
* [zlib 1.2.11](http://www.zlib.net/)
* [libpng 1.6.28]( http://www.libpng.org/pub/png/libpng.html)
* [libjpeg 9b](http://ijg.org/)
* [OpenJPEG 2.1.2](http://www.openjpeg.org/)
* [webp master](https://chromium.googlesource.com/webm/libwebp)
* [icuuc.dll] (http://download.icu-project.org/files/icu4c/58.2/icu4c-58_2-src.zip)
* [icuin58.dll] (http://download.icu-project.org/files/icu4c/58.2/icu4c-58_2-src.zip)
* [icudt58.dll] (http://download.icu-project.org/files/icu4c/58.2/icu4c-58_2-src.zip) - Contains the unicode related data package
