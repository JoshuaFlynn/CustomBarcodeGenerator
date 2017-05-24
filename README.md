# CustomBarcodeGenerator
A custom barcode generator that is cross-platform, can be installed anywhere regardless of admin permissions, and is very compact.

# How to use
Simply download a .zip, extract to literally anywhere, and open the index.html file in any modern browser (CBG very rarely works in Internet Explorer). If Internet Explorer is default, right-click and 'open with' the appropriate browser. It might work in an upgraded version of IE, possibly.

Once open, press the button to generate a barcode. A few notes:
1) The custom barcode generator can only generate valid EVEN numbered alphanumeric codes. Odd numbered did not get picked up on scanners in testing. So 1234 would be valid, but 12345 wouldn't. ABCD would be valid, but ABCDE wouldn't.
2) Spaces are represented by explanation marks in the barcode standard. So "A SPACE1" would be written as "A!SPACE1"
3) Normally you would have to append asterisks either side to 'enclose' the barcode. This is done for you automatically.

You can add as many barcodes as you like, however you cannot, at present, edit them.

Once done, press 'Ctrl + P' and print.
