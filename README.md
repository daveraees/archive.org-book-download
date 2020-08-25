# archive.org book download
 Automatically download entire book from the online library

## Usage:
Written in Jupyter notebook.
For use follow the example at the end of the notebook:
1) Find the book of you interrest, and find out its "Identifier" character string.
2) Start the automatic web browser at the first page of the book to download with function open_book_url_and_login.
3) Type in your login name and password in the automatic browser window and borrow the book using the web interface manually. It is usually enough to "Borrow for 1 hour".
4) Start downloading pages of your book with function download_book. You can specify the window size to optimize page resolution.
5) You can read your book localy from the page scans. Please be aware of the copyrights attached to the book.

## Requirements:
You should have an account at the archive.org website. At the time of publishing this code, it is open to all and free of charge.
Functions depend on 
* openCV library for image processing
* numpy for matrix evaluation
* selenium for automatic web interface usage

## TODO:
* optimization of the page resolution
* automatic PDF generation from the page image files


# Credits:
David Rais, 2020
