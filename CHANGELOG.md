# Change Log for Clipboard Viewer Component

## v2.0.0 of 10 August 2014

+ Updated to use modern Clipboard Format Listener API functions when running on OSs that support them, while still supporting the original Clipboard Viewer API on older OSs. ~~This fixes issue #30.~~
+ Removed obsolete WinHelp files from project. Documentation is now online only.
+ "private" and "protected" class sections are now strict on supporting Delphis.
+ A little refactoring.
+ XMLDoc commented unit.
+ Updated documentation re changes.

## v1.4.1 of 06 February 2014

+ Fixed problem with compiler directives in component and demo source files that was causing compilation to fail on Delphi XE5.
+ References to unit names in the component demo and source files are now qualified with their namespaces when compiled with Delphi XE2 and later.
+ Demo program appearance modified with form scaling switched off, change to Arial font and positioning of the window at desktop centre. Delphi 7 or later is now required to compile the demo.
+ WinHelp help file regenerated with updated copyright date.
+ License changes:
  + Component source license changed to Mozilla Public License v2.0, which is also now applied to main documentation.
  + Demo source code and documentation placed in public domain (Creative Commons CC0 1.0 Universal).
+ Documentation revised:
  + Read-me and demo read-me files revised re changes.
  + MPL license file renamed and now contains Mozilla Public License v2.0 instead of v1.1.
  + Online documentation short-cut now renamed and its URL changed.

## v1.4 of 13 October 2010

+ Updated compiler directives used to detect and act on compiler in use.
+ Added new demo project.
+ Revised help file and updated example code to match demo project.
+ Updated and corrected documentation and included short-cut file that links to component Wiki.

## v1.3 of 17 August 2008

+ Fixed a conditional compilation bug.
+ Re-factored main window procedure in line with MSDN clipboard viewer documentation.
+ Removed 16 bit support.
+ Made minor changes to help file.

## v1.2 of 11 May 2004

+ Prevented compiler warnings when compiling the component under Delphi 6 and 7.
+ Updated copyright information in help file.
+ Changed to Mozilla public license.

## v1.1 of 27 July 2003

+ Changed to install into "DelphiDabbler" component palette rather than PJ Stuff.
+ Altered code slightly to make easier to subclass.
+ Rewrote help file to integrate into Delphi 3 and later IDE - help file's backwards compatibility with Delphi 1 and 2 was lost.
+ Updated documentation to reflect changes and to cover installation from Delphi 1 to Delphi 7.

## v1.0.1 of 28 November 1999

+ Updated HTML documentation to include installation notes for Delphi 3/4 and added update history.

## v1.0 of 01 August 1999

+ Original version.
