takes a mix of image types in one batch and converts them all to whichever output format you pick. In my tests, 10 input types (JPG, PNG, WebP, GIF, BMP, TIFF, HEIC, AVIF, ICO and SVG) all converted to every output format

Formats

Reads: HEIC/HEIF, JPG, PNG, WebP, AVIF, GIF, BMP, TIFF, ICO and SVG. Animated GIFs convert as their first frame only.
Writes: JPG, PNG, WebP, AVIF, GIF, BMP, TIFF and ICO. I tested every output except AVIF.
My suggestions:
JPG for photos and PNG when you need transparency or lossless.
WebP and AVIF if you want small files for the web.
TIFF for print or archiving.
ICO for icons.
BMP and GIF are in mostly for completeness, since BMP files are huge and GIF drops photos to 256 colours.
AVIF output: This depends on your browser being able to encode it. The page checks at startup and greys the button out if it can’t. It was greyed out in my test browser, so I couldn’t try it. Desktop Chrome and Firefox usually can.
Left out: PDF, JPEG 2000 and RAW camera files. PDF would be the one to add next, for example one image per page.
