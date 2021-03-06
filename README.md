# PDFST

PDFST is a command line tool for stamping pdf files using png images build with GO. You can configure position, size and opacity.

## Installation

Tool is just a single binary file. You can download it from latest [release](https://github.com/lol2x/pdfst/releases)

## Usage

```
pdfst <source> <stamp> <output> [options...] # <source> and <output> should be path to a pdf file and <stamp> can be a path of an image.

# Available Options: 
-p, --img-pos int # Image position: 1-9 (just like the phone's keyboard layout) (default 1)
-w, --img-w float # Target image width [mm] (can be omitted if height is)
-h, --img-h float # Target image height [mm] (can be omitted if width is)
-x, --offset-x float # Horizontal shift [mm] depending on the image position. (default 10)
-y, --offset-y float # Vertical shift [mm] depending on the image position. (default 10)
-o, --opacity float # Opacity of stamp. Float between 0 to 1 (default 0.8)
-v, --verbose # Display debug information
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[GNU AGPLv3](https://choosealicense.com/licenses/agpl-3.0/)