# Updatable Multi-Clipboard
This is an implementation of the **Extending the Multi-Clipboard** practice project from [Chapter 9 – Reading and Writing Files](https://automatetheboringstuff.com/2e/chapter9/) of the book [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/) by Al Sweigart.

## Project Description
The program will save each piece of clipboard text under a keyword. For example, when you run `python3 mcb.pyw save spam`, the current contents of the clipboard will be saved with the keyword *spam*. This text can later be loaded to the clipboard again by running `python3 mcb.pyw spam`. And if the user forgets what keywords they have, they can run `python3 mcb.pyw list` to copy a list of all keywords to the clipboard.

**Note**: This script uses `pyperclip`, a third-party module that you may have to install beforehand

## How to Use
1. Copy this repo to your local machine using `git clone` or download
2. Copy some text that you want to save to a shelf file
3. Run on of these commands:
    1. python3 mcb.pyw save <keyword> - Saves clipboard to keyword
    2. python3 mcb.pyw <keyword> - Loads keyword to clipboard
    3. python3 mcb.pyw list - Loads all keywords to clipboard
    4. python3 mcb.pyw delete <keyword> - Delete keyword from shelf file
    5. python3 mcb.pyw delete - Delete all keywords in the shelf file
4. Now you can save and load long texts from and onto your clipboard based on keywords on the shelf file
