# business-cards

Templates for business cards.

## Usage

Video tutorial:  https://youtu.be/zjPZocWxJP4

1. Prepare a table with data in CSV format in UTF-16 encoding. See example [src/Business Cards-1-UTF16.csv](src/Business Cards-1-UTF16.csv)
2. Open `src/idt-business-cards.indd` in InDesign
3. Go to `Window` → `Utilities` → `Data Merge`
4. In upper-right corver press “hamburger” menu and `Select Data Source…`
5. In Data Source Import Options check delimiter `Comma`, Encoding `Unicode`, Platform `Macintosh` or `PC` depending on where csv file was generated.
6. Check `Preview` and flip through all pages to check everything is fine.
7. Press “hamburger” → `Create Merged Document`
8. Set options, click `OK`.
9. Save generated document into `out` folder.
