# An iOS document preview and open plugin

> it is though a bit experimental as it is coded in Swift.

This plugin will preview a document using UIDocumentInteractionController and allow to open it via the share sheet.

## Requirements

- iOS 3.2 and above (available since then)
- Cordova 4.0

## Installation

```
cordova plugin add cordova-ios-document-preview
```

## Usage

```
iOSDocumentPreview(file, type, () => { success }, () => { error });
```

## Examples

## Notes

## LICENSE

The MIT License (MIT)

Copyright (c) 2016 Sebastian Döll <sebastian@pixelmilk.com>

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.