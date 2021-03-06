## LTFinderButtons
My Finder buttons collection for macOS.

![ltfinderbuttons 2x](https://cloud.githubusercontent.com/assets/219689/20527688/43dea28e-b104-11e6-8c39-64747c10b232.png)

## Buttons
- [x] Terminal
- [x] iTerm2 (2.9+)
- [x] TextMate
- [x] Sublime Text 3
- [x] Atom
- [x] Brackets
- [x] CotEditor
- [x] BBEdit
- [x] TextWrangler

## Usage
Download or `git clone` the buttons in a proper place. Hold on command button and drag each one into your Finder toolbar.

## Contribute a button
0. Fork this repo.
1. Duplicate TextMateFinderButton.app and rename it to MyShinnyFinderButton.app.
2. Open `MyShinnyFinderButton.app/Contents/Resources/Scripts/main.scpt` with Script Editor then you gonna know what to do.
3. Open LTFinderButtons.sketch and draw your button.
4. Export the `iconset` folders from Sketch.
5. Convert images into icns files one by one (e.g. `iconutil -c icns MyShinnyFinderButton.iconset`)
6. Replace `MyShinnyFinderButton.app/Contents/Resources/droplet.icns` with your icns.
7. Send a pull request.


## Contacts
[Lex Tang](https://github.com/lexrus/) ([@lexrus on Twitter](https://twitter.com/lexrus/))

## License
This project is distributed under the terms and conditions of the MIT license.
