# About

Version controlled, CI built CV based on template original by Adrien Friggeri.  Font type switched from Helvetica to Nimbus based fonts because I'm not consistently on Apple devices anymore.

## To Do

- Find a better way to source the Ultra Light variant of the Nimbus font. 
- Refactor any supporting Docker images into faster builds with fewer layers.
- Figure out why font names appear to vary between Manjaro (Arch) and Alpine (docker) distributions, it's a real nuisance having to re figure stuff out multiple times.
- Review biber, see if we can drop it completely
- Review build output and see if we can get it to a point where we can remove the continue when failed parameter in the build action.
- Review the GitHub actions for creating releases: find out why tags are a) required and b) blocking a release from being updated.


# License

Copyright (C) 2012, Adrien Friggeri

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.