## README

This iOS app displays information on all the apps installed on the device.It makes use of
private classes and, as such, will be rejected if submitted to Apple's App Store. I find
looking at this info interesting/educational; I hope you do as well.

## Future Development

There will most likely be little or no future development of this project, although I will
attempt to address bug reports, pull requests, etc. promptly. I am particularly interested
in hearing suggestions on how I can improve my Swift coding.

The little bit of Objective-C that exists in this project is there because I couldn't
figure out a Swift equivalent---particularly a work-around for `performSelector`. Note
the existance of the `AppInfo` class is almost entirely dut to the repeated segfaults when
trying to use `LSApplicationProxy` more directly.

## License

Copyright (c) 2014 Matthew M. Burke
 
Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:
 
The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.
 
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
