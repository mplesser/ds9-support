# azcam-ds9

## Purpose

*azcam-ds9* is an *azcam extension* which supports SAO's ds9 display tool running under Windows. See https://sites.google.com/cfa.harvard.edu/saoimageds9.

See https://mplesser.github.io/azcam-ds9-winsupport for support code which may be helpful when displaying images on Windows computers

## Display Class
This class defines Azcam's image display interface to SAO's ds9 image display. 
It is usually instantiated as the *display* object for both server and clients.

Depending on system configuration, the *display* object may be available 
directly from the command line, e.g. `display.display("test.fits")`.

Usage Example:

    rois = azcam.api.display.get_rois(2, 'detector')  
    azcam.display.api.display(test.fits')

## Code Documentation
https://mplesser.github.io/azcam-ds9/

## Notes
It may be helpful to remove all associations of .fits files in the registry and then only
execute the above batch files.  Do not directly associate .fits files with ds9.exe.