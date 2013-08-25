# Viewer

Viewer is a small webapp for viewing slideshows that runs entirely off of a single static html file. The images to display are set via the URL, using the query and the fragment.

## URL options

### "structure"
The structure of the URL, can be a single image URL or a URL with underscores to be filled by the "number" option.

### "number"
If the structure has a blank space, the number or numbers here will fill it. Can be a single number, a series of numbers separated by single underscores, or a series of numbers.

### URL fragment
Sets the image Viewer starts off with.

## Example URLs

Show these images in the Screenshots folder: Image000010.png, Image000120.png, Image000013.png
`viewer.html?structure=Screenshots/Image______.png&number=10_120_13`

Show these images in the camera folder: pic1.jpg, pic2.jpg, pic3.jpg, ..etc.., pic15.jpg
`viewer.html?structure=camera/pic_.jpg&number=1__15`