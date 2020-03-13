
GTK2 Builds
===========

NOTE
----
Github doesn't like files over 100 MB. That is why the wheel files are in 7zip format.
Use 7zip to extract/repack if necessary.

A *.whl is basically nothing more than a basic renamed *.zip file

The *.7z was compressed with
 * Archive format: 7z
 * Compression level: Ultra
 * Compression method: LZMA2
 * Dictionary size: 256 MB
 * Word size: 273
 * Solid Block size: Solid

or

The *.zip was compressed with
 * Archive format: zip
 * Compression level: Ultra
 * Compression method: LZMA
 * Dictionary size: 256 MB
 * Word size: 273

Any of these files might require 7zip to extract.

If you can get away with just renaming the extension to .whl and then pip installing it great!,
otherwise you might have to extract/repack it as a regular lowlevel zip, then rename the extension to .whl
