# PDF Tools
Command line PDF manipulation tool

### Tools
This tool offers five functions: merge, remove, swap, insert, and reorder. The merge tool combines two PDF files and saves the output. The remove tool removes pages or page ranges from a PDF. The swap tool can swap two pages in a single PDF. The insert tool puts pages or a page range from a source PDF into any location in a destination PDF. The reorder tool reorders the pages in a PDF and saves it as a different PDF. The options can be viewed by typing `pdftools -h` into the command line.

### Installation
1. Type `git clone https://github.com/danielkhain/pdftools.git` into the command line.
2. Enter the `pdftools` directory.
3. Type `./bin/install` into the command line.
4. Type `open ~/.bash_profile` into the command line.
5. Add `alias pdftools='/Users/[user]/bin/pdftools'` to the bottom of `~/.bash_profile`.
6. Close the terminal and open a new window.
7. Delete the cloned directory. The pdf tool can now be run by typing `pdftools -h` in the terminal.
