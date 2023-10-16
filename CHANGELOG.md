# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).



## [Unreleased]


### Changed 

- Renamed CHANGES.txt to CHANGELOG.md and using a changelog template.



## [0.1.28] - 2021-09-13

Fix for DC Release error that happened when calling pixel() after calling screenshot() on Windows.


## [0.1.22] - 2019-06-27

Added -z to scrot to silence the beep.


## [0.1.21] - 2019-05-17

Fix memory leak at pixel(). Fix to pixel function. Fix cropped image saving on Linux and Mac. Fix UnboundLocalError (img_cv won't be assigned) when img is a true-color array.


## [0.1.18] - 2018-07-19

Fixing MANIFEST.in to include readme, which cause installation failure.


## [0.1.17] - 2018-07-18

Adjusted setup.py to include the long description.


## [0.1.16] - 2018-07-18

Adjusted setup.py to include the long description.


## [0.1.15] - 2018-07-18

Fixed a bug involving the generator for locateAll().


## [0.1.14] - 2018-03-02

Added check for Pillow installation when calling screenshot() on Windows.


## [0.1.13] - 2017-06-13

Fixed RGB ordering bug for pixel() in 0.1.12


## [0.1.12] - 2017-06-12

Used the win32 GetPixel() function to speed up the pixel() function 2x.


## [0.1.11] - 2017-06-11

Have setup.py pull version info from file, which fixes several issues.


## [0.1.10] - 2017-06-11

Fixed Google App Engine failure, fix RGB/RGBA bug in pixelMatchesColor()


## [0.1.9] - 2017-01-19

Put imports into a try/except, to prevent errors if PIL is not present.


## [0.1.8] - 2015-06-02

Add more error handling for OpenCV


## [0.1.7] - 2015-05-29

Exposed confidence setting for OpenCV, added "min search time"


## [0.1.6] - 2015-01-10

OpenCV integration, fix for limit keyword argument


## [0.1.5] - 2014-12-15

Actual fix for the region issue.


## [0.1.4] - 2014-12-14

Updated features for region parameter to several functions.


## [0.1.3] - 2014-12-11

Fix for Linux issues from github.com/LauritzThaulow


## [0.1.2] - 2014-10-19

Fix for locateCenterOnScreen() bug.


## [0.1.1] - 2014-10-19

Fix for issue #3 on the PyAutoGUI project.


## [0.1.0] - 2014-09-16

Initial release.