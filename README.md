# Personal Portfolio Website

## Construction Notes

*13/03/2024
- OnClick events will require JavaScript.
- JavaScript will require a live server environment.
- **HTML, CSS and JavaScript first implemented.**
- _git push -u origin main_

*14/03/2024
- Set the main 16 colours to the original ms-dos colour pallette. This might end up ugly. 

*15/03/2024
- Researching fonts used in MS-DOS and CMD = ROM and Consolas font.

*17/03/2024
- Found old style fonts package
- Created asset folder

*18/03/2024
- Set path to new font family (First IMB font seen) = Success
- Tried to add another font family but overwites the first. = had to create a seperate "@font-family" instance
- Settled with fonts "Ac437_IBM_DOS_ISO8.ttf" for console text and "Ac437_IBM_3270pc.ttf" for headers. Might change later.
- _git push -u origin main_

*20/03/2024
- Messed around with font sizes
- Changed around the REM to 62.5% = 10px. Easier to proportion for screen resizing.
- Tried changing the "console" font to Ac437_Cordata_PPC-21.ttf

*25/03/2024
- Found a website that emulates the fallout 4 terminals
- [[https://codepen.io/mackorichardson/pen/vNMRpK]]
- "*" selector just let me get rid of that padding and the bloat around the menu selections.
- Changed the navbar to "sticky" to margin more accurately
- changed nav-bar to a retro solid border

*17/04/2024
- Tried to justify nav content left and right, won't leave space in the middle and treat left and right ul as seperate elements.

*08/05/2024
- Fixed Nav bar positioning with "float" attribute.
- Seperated the padding for the nav bar elements and the rest of the text elements into two seperate attribute modifiers.
- Start next section. Need to get this done for the online course material.
- Added the id tags to each section and added them as hrefs on the nav bar links. Will need to add smooth scroll to those.