# Libert 📖
Get ebooks for free, easily.

## Set up
Clone, Go into the directory and run `npm start "search query"`

## Current Usage
Right now, it allows you to search for a book.
- Run `npm start "search query"`
- It looks up the book on google books.
- When you're asked `Download`, enter `y` and press enter to get a list of results for downloading the book.
- When aked `which_one`, enter one of the numbers formatted as `|||"number"|||`.
- When asked `action`, enter `k` for downloading on your kindle, or leave blank for downloading it to your computer. 

## To-Do
- Front end interface with express.js
- Full Google API usage, with
  1. User Data
  2. Recommendations
  3. Previews
- Conversion from and to different ebook formats

## Disclaimer
All libert does is fetch books from particular sources, with a different UI. It is designed to make using these sources easier, and does not host anything itself. I, Samarth Jajoo claim no responsibility for any illegal actions performed through libert.
