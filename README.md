Here's a few tools, lua scripts and lensfun files for photographers who dabble!

DOF calculator - a visual DOF Calculator with help embedded in various elements.

LCP Lens Correction - I spent sometime developing this with Claude, and man, did it take sometime to coerce the AI...
anyhow I've tested this with quite a few LCP files and it worked for a number of lenses and sensor formats. e.g Hasselblad, FF and APSC etc. This produces distortion and vignetting xml snippets that can be placed in lensfun files
fo use in Darktable.

Two xml files, one for new XCD lenses and the other for the Sigma 17-40 f1.8 on Fuji X systems.

Hasselblad Baseline Exposure - this Darktable lua script reads the baselineExposure (0xC62A SRATIONAL) directly from the 3FR binary and adds it (via a button) to the default exposure. 
This is necessary for images that are taken using HDR mode in the X2DII, as they show underexposure when imported into Darktable.

Leica Q3 Digital Zoom - this Darktable lua script reads the .dng file for "in camera" digital zoom (crop) and applies it (via a button).

All are offered "as-is", I hope you find them useful!
