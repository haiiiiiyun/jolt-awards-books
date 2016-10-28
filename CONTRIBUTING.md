## Contributor License Agreement
By contributing you agree to the [LICENSE](https://github.com/vhf/free-programming-books/blob/master/LICENSE) of this repository.

## Contributor Code of Conduct
By contributing you agree to respect the [Code of Conduct](https://github.com/vhf/free-programming-books/blob/master/CODE_OF_CONDUCT.md) of this repository.

### Guidelines
- do not make a downloadable link, unless the book is free
- we don't accept files hosted on google drive, dropbox, mega, scribd, issuu and other similar file upload platforms
- insert your links in alphabetical order. If you see a misplaced link, please reorder it and submit a PR
- use the link with the most authoritative source (meaning author's website is better than editor's website is better than third party website)
    + no file hosting services (this includes (but is not limited to) Dropbox and Google Drive links)
- always prefer a `https` link over a `http` one -- as long as they are on the same domain and serve the same content
- on root domains, strip the trailing slash: `http://example.com` instead of `http://example.com/`
- always prefer the shortest link: `http://example.com/dir/` is better than `http://example.com/dir/index.html`
    + no URL shortener links
- usually prefer the "current" link over the "version" one: `http://example.com/dir/book/current/` is better than `http://example.com/dir/book/v1.0.0/index.html`

### Formatting
- All lists are `.md` files. Try to learn [Markdown](https://guides.github.com/features/mastering-markdown/) syntax. It's simple!
- All the lists start with an Index. The idea is to list and link all sections and subsections there. Keep it in alphabetical order.
- Sections are using level 3 headings (`###`), and subsections are level 4 headings (`####`).

The idea is to have
- `2` empty lines between last link and new section
- `1` empty line between heading & first link of its section
- `0` empty line between two links
- `1` empty line at the end of each `.md` file

Example:

    [...]
    * [An Awesome Book](http://example.com/example.html)
                                    (blank line)
                                    (blank line)
    ### Example
                                    (blank line)
    * [Another Awesome Book](http://example.com/book.html)
    * [Some Other Book](http://example.com/other.html)

- Don't put spaces between `]` and `(`

```
BAD : * [Another Awesome Book] (http://example.com/book.html)
GOOD: * [Another Awesome Book](http://example.com/book.html)
```

- If you wish to mention the author, use ` - ` (a dash surrounded by single spaces)

```
BAD : * [Another Awesome Book](http://example.com/book.html)- John Doe
GOOD: * [Another Awesome Book](http://example.com/book.html) - John Doe
```

- Put a single space between the link and its format

```
BAD : * [Another Awesome Book](http://example.com/book.pdf)(PDF)
GOOD: * [Another Awesome Book](http://example.com/book.pdf) (PDF)
```

- Author comes before format:

```
BAD : * [Another Awesome Book](http://example.com/book.pdf)- John Doe
GOOD: * [Another Awesome Book](http://example.com/book.pdf) - John Doe (PDF)
```

- Multiple formats:

```
BAD : * [Another Awesome Book](http://example.com/)- John Doe (HTML)
BAD : * [Another Awesome Book](https://downloads.example.org/book.html)- John Doe (download site)
GOOD: * [Another Awesome Book](http://example.com/) - John Doe (HTML) [(PDF, EPUB)](https://downloads.example.org/book.html)
```
