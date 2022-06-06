# Clipboard Viewer Component

## Description

_TPJCBView_ is a non-visual Delphi component that notifies the user whenever the content of the clipboard changes.

Notification is by means of an event. By handling the event your application can respond to changes on the clipboard. The component can be used as the heart of a program that displays "live" information about the clipboard. Alternatively it can be used to enable and disable other components whose state depends on the available clipboard formats.

_TPJCBView_ provides an _Enabled_ property that is used to enable and disable the component and hence it's events. It also has a _TriggerOnCreation_ property that triggers an event when the control is created.

For more information see the component's has [online documentation](https://delphidabbler.com/url/cbview-docs).

## Compatibility

The component has been tested with the 32-bit Windows compiler of Delphi 7 and Delphi 2006 to XE4 and the the 64-bit Windows compiler of Delphi XE2 to XE4.

The unit has dependencies on the VCL and on Windows so cannot be used with the FireMonkey framework or with non-Windows targets.

## Installation

The _Clipboard Viewer Component_ and its associated files are supplied in a zip file. Before installing you need to extract all the files from the zip file, preserving the directory structure. The following files will be extracted:

* **`PJCBView.pas`** – component source code.
* **`PJCBView.dcr`** – component palette glyph.
* `README.md` – this file.
* `CHANGELOG.md` – project change log.
* `MPL-2.txt` – the Mozilla Public License v2.0.
* `Documentation.url` – short-cut to the component's online documentation.

In addition to the above files you will find the source code of a [demo project](#demo-program) the `Demo` sub-directory.

You can now install the components into the Delphi IDE. To do this, the files `PJCBView.pas` and `PJCBView.dcr` should be added to a design time package. If you need help doing this [see here](https://delphidabbler.com/url/install-comp).

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

Please check if an issue has already been created for a similar report or request. If so then please add a comment containing as much information as you can to the existing issue, or if you've nothing to add, just add a :+1: (`:+1:`) comment. If there is no suitable existing issue then please add a new issue and give as much information as possible.

## About the Author

I'm Peter Johnson – a hobbyist programmer living in Ceredigion in West Wales, UK, writing mainly in Delphi. My programs and other library code are available from: [https://delphidabbler.com/](https://delphidabbler.com/).

This document is copyright © 2008-2022, [P D Johnson](https://gravatar.com/delphidabbler).
