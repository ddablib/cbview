# Clipboard Viewer Component

## Description

_TPJCBView_ is a non-visual Delphi VCL component that notifies the user whenever the content of the clipboard changes.

Notification is by means of an event. By handling the event your application can respond to changes on the clipboard. The component can be used as the heart of a program that displays "live" information about the clipboard. Alternatively it can be used to enable and disable other components whose state depends on the available clipboard formats.

_TPJCBView_ provides an _Enabled_ property that is used to enable and disable the component and hence it's events. It also has a _TriggerOnCreation_ property that triggers an event when the control is created.

For more information see the component's [online documentation](https://delphidabbler.com/url/cbview-docs).

## Compatibility

The component must be compiled with Delphi 7 or later. It is 32 bit an 64 bit compatible.

The unit has dependencies on the VCL and on the Windows API, so cannot be used with the FireMonkey framework or with non-Windows targets.

## Installation

The _Clipboard Viewer Component_ and its associated files are supplied in a zip file. Before installing you need to extract all the files from the zip file, preserving the directory structure. The following files will be extracted:

* **`PJCBView.pas`** – component source code.
* **`PJCBView.dcr`** – component palette glyph.
* `README.md` – this file.
* `CHANGELOG.md` – project change log.
* `MPL-2.txt` – the Mozilla Public License v2.0.
* `Documentation.url` – short-cut to the component's online documentation.

In addition to the above files you will find the source code of a [demo project](#demo-program) in the `Demo` sub-directory.

The component can be installed into the Delphi IDE by including `PJCBView.pas` and `PJCBView.dcr` in some suitable package(s). If you need help doing this [see here](https://delphidabbler.com/url/install-comp).

## Demo Program

The source code of a program that demonstrates the component is included in the download.

This demo requires Delphi 7 as a minimum.

For more information about the demo see the file [`DemoReadMe.txt`](https://raw.githubusercontent.com/ddablib/cbview/main/Demo/DemoReadMe.txt) in the `Demo` directory.

## Update History

A complete change log is provided in [`CHANGELOG.md`](https://github.com/ddablib/cbview/blob/main/CHANGELOG.md) that is included in the download.

## License

The _Clipboard Viewer Component_ is released under the terms of the [Mozilla Public License v2.0](https://www.mozilla.org/MPL/2.0/).

All relevant trademarks are acknowledged.

## Bugs and Feature Requests

Bugs can be reported or new features requested via the project's [Issue Tracker](https://github.com/ddablib/cbview/issues). A GitHub account is required.

First check if any similar issue already exists. If so then please add a comment to it containing as much information as you can provide. If you've nothing to add, just add a :+1: (`:+1:`) comment.

If there is no relevant existing issue then please create a new one and give as much information as possible.

## About the Author

I'm Peter Johnson – a hobbyist programmer living in Ceredigion in West Wales, UK, writing mainly in Delphi. My programs and other library code are available from [https://delphidabbler.com/](https://delphidabbler.com/).

This document is copyright © 2008-2023, [P D Johnson](https://gravatar.com/delphidabbler).
