# Hypertext Markup Language

HTML is a ["markup language"](https://en.wikipedia.org/wiki/Markup_language) originally designed to describe structured documents for the web.

If you look at the pages of a book or the print out of your term paper, you will see a set of common conventions that we use to communicate structure and meaning.
Semantic document features such as headings, paragraphs, lists, or italics are represented on the page by distinctive styling such as font size, boldness, or font decoration.

HTML provides a way to formally mark those types of document elements, allowing you to record the semantic structure of the text.
This markup can then be translated by the web browser into visual styles for easy reading, or efficiently navigated by screen readers for non-visual users.

Of course, as web pages become ever more complicated, HTML has gone far beyond a simple document language!

## HTML Elements

HTML is made up of a set of standard **elements** used to structure a web page and introduce features such as images.
Elements are like annotations describing how chunks of page content should be interpreted by the browser.

HTML elements follow this pattern:

`<tag attribute="value">content annotated by the element</tag>`

- Elements are represented by **tags** enclosed by pointy brackets.
- Elements may have **attributes** inside the brackets that add additional data or qualifications to the tag.
- Elements may enclose content or other elements which are **nested** between the **opening** and **closing** tag. The content enclosed by the tags is described (marked up) by the element.

Note the elements themselves are not displayed, but are used as instructions for rendering the content they annotate.

For example, in HTML the heading above that says "HTML Elements" looks like:

`<h2>HTML Elements</h2>`

The `<h2>` tag encloses the text "HTML Elements", marking it semantically as a "second level heading" in the document.
The web browser displays "HTML Elements" differently than the main paragraph text and the `h1` header "Hypertext Markup Language" at the top of the page, to convey it's semantic meaning to readers.

There are hundreds of elements in the [HTML standard](https://html.spec.whatwg.org/).
However, you will only need to recognize a handful and understand the basic concept of tagging to understand most pages or write your own.

Keep in mind that on the live web you will see a lot of *badly written* HTML!
Although HTML is technically a strict standard, web browsers are very lenient. 
They will display markup that breaks all the rules.