## URL examples

Location of viewer.html:
`example.com/folder/viewer.html`

Get images "Images/Screenshot100.png" and "Images/Screenshots101.png"
`viewer.html#structure="Images/Screenshot_.png"&numbers="100_101"` 

Get spaaaacce2/scr00010.png, spaaaacce2/scr00011.png, ...etc..., spaaaacce2/scr00020.png
`viewer.html#structure="spaaaacce2/scr_____.png"&numbers="10__20"`

## URL structure

### structure
Regular URLs are valid, for example "folder/image.png", however underscores can be used as "blanks" to be filled by the number value

### number
The value of number fills the blanks in the structure. It can be a number, like "30", or a series of numbers, like "10__20" for 10, 11, ...etc..., 20, or it could be multiple numbers, like "4_8_9" for 4, 8, and 9.