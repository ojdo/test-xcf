# test-xcf
Just a test to check whether GitHub supports displaying GIMP (XCF) image files, not only Photoshop (PSD).

File gimp.xcf is the unmodified, imported and saved file [`gimp.svg`](https://github.com/GNOME/gimp/blob/master/desktop/src/gimp.svg) desktop logo from the [official GIMP repository](https://github.com/GNOME/gimp) (GPLv3).

With imagemagick installed, a simple call can create a PNG image

    convert gimp.xcf gimp.png
    
which then could be used for visual diffing.
