# Alt Kindle EPUB Fix

This is a fork of the great https://github.com/innocenat/kindle-epub-fix

Amazon Send-to-Kindle service now accepts EPUB, however for historical reasons it still assumes ISO-8859-1 encoding if no encoding is specified. 
This creates weird formatting errors for special characters.
This tool will try to fix your EPUB by adding the UTF-8 specification to your EPUB.
It currently does not fix other errors.

This alternate version will simply do the following things in addition to the existing fixes:
 - Removes a certain pesky keyword with a 'Z' in brackets at the end of an epubs filename.
 - Removes the '(fixed)' and '(repacked)' prefixes in existing filenames.
 - The processed files will not be prefixed with '(fixed)' or '(repacked)'.

You can access this alternate tool at https://epubsfix.netlify.app/

**Warning:** No guarantees are made, please always keep your original EPUB.

