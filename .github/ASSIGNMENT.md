# 📄 Twitch Plays Pokémon

Practice the basics of HTML by turning plain text about Twitch Plays Pokémon into a
well-structured, meaningful web page.

## 🎯 Overview

In February 2014, more than a million people played a single game of Pokémon Red together
by typing commands into a Twitch chat. In this exercise, you will take the story of
**Twitch Plays Pokémon** from plain text and mark it up as an HTML web page.

The text in `content.txt` has no HTML in it. Your job is to decide what each piece of
content *is* (a heading, a paragraph, a list, a quote, a date, a term and its definition)
and choose the HTML element that describes it best.

There is no CSS in this exercise, so the page will look plain when you are finished.
**That is expected.** Right now, the focus is on structure and meaning. Later, CSS will
let you control colors, fonts, layout, and spacing.

## 🧠 What You Will Learn

By completing this exercise, you will practice how to:

- Build the basic structure of an HTML document
- Add a page `title` and a `meta` description in the `head`
- Organize a page with `header`, `main`, `section`, and `footer`
- Use headings (`h1`, `h2`, `h3`) to create a logical outline
- Mark up paragraphs, lists, and description lists
- Use inline elements such as `strong`, `em`, `abbr`, `time`, `del`, and `ins`
- Mark up a quotation with `blockquote` and credit its source
- Preview your page in a browser and check it with a validator

## 📂 Starter Files

| File | Purpose |
| --- | --- |
| `content.txt` | The plain text for the page. Either **rename it to `index.html`** and add your markup, or **create a new `index.html`** and copy the text into it. |

> [!IMPORTANT]
> Your finished page must be named exactly **`index.html`** and live in the root folder.
> GitHub Pages only serves `index.html` at your site's root URL; any other name gives you a 404. Windows users: turn on file extensions first so you can see the full file name and don't end up with `index.html.txt`.

The first two lines of `content.txt` are **not** visible page content:

```
Page title: Twitch Plays Pokémon: A Million Players, One Game
Page description: The story of Twitch Plays Pokémon, ...
```

They belong in the `head`. Use the first as the page's `title` and the second as the
`content` of a `<meta name="description">` element, then delete the labels.

## 📋 Requirements

### Document structure

- [ ] The page has a `DOCTYPE`, `html` (with `lang="en"`), `head`, and `body`
- [ ] The `head` includes `<meta charset="utf-8">` so the "é" in Pokémon displays correctly
- [ ] The `head` includes the page `title` and a `meta` description from `content.txt`
- [ ] All visible content is inside the `body`

### Page layout

- [ ] The main title and tagline are inside a `header`
- [ ] The article content is inside `main`
- [ ] Each major topic is its own `section`
- [ ] The trademark/copyright line at the end is inside a `footer`

### Headings and text

- [ ] *Twitch Plays Pokémon* is the page's only `h1`
- [ ] Each major topic (*A Social Experiment*, *How It Worked*, *Anarchy vs. Democracy*,
      *The Lore*, *Bloody Sunday*, *The Final Battle*, *By the Numbers*, *Timeline*,
      *What It Left Behind*) is an `h2`
- [ ] The three stories inside *The Lore* (*Lord Helix*, *Bird Jesus*, *The False Prophet*)
      are `h3` elements. Headings follow the page's outline, not how big you want the text
      to look
- [ ] Every paragraph of text is in its own `p` element

### Lists

- [ ] The eight chat commands (up, down, left, right, A, B, start, select) are a list
- [ ] *By the Numbers* is a list, with each statistic as its own item
- [ ] *Timeline* is an **ordered** list, since the events happen in order
- [ ] *Anarchy* and *Democracy* are marked up as a description list (`dl`, `dt`, `dd`):
      each mode is a term, and its explanation is the description

### Inline elements

- [ ] The abbreviations **RPG** and **TPP** use `abbr` with a `title` that spells them out
- [ ] The dates in the *Timeline* use the `time` element with a `datetime` attribute
      (for example, `<time datetime="2014-03-01">March 1, 2014</time>`)
- [ ] In *"the plan was to evolve Eevee into Vaporeon Flareon"*, **Vaporeon** is marked as
      deleted text (`del`) and **Flareon** as inserted text (`ins`)
- [ ] The chat phrase *Praise Helix* is emphasized with `em`, and at least one other
      important phrase uses `strong` where it makes sense

### Quotation

- [ ] The Guinness World Records title is in a `blockquote`, with its source credited
      using `cite`

## 🧮 Grading

| Criteria | What earns full credit | Points |
| --- | --- | --- |
| **Document structure** | Correct doctype, `html` with `lang`, `head`, and `body`; `meta charset`; meaningful `title` and `meta` description; all visible content in `body`. | 2 |
| **Page layout** | `header`, `main`, `section`, and `footer` are used for the content they describe. | 2 |
| **Headings and paragraphs** | One `h1`; `h2`/`h3` reflect the real outline of the page; all body text is in `p` elements. | 3 |
| **Lists** | Commands and statistics are lists; the timeline is an `ol`; Anarchy/Democracy is a `dl` with `dt` and `dd`. | 3 |
| **Inline elements** | `abbr` with `title`, `time` with `datetime`, `del`/`ins`, `strong`, and `em` are all present and used on the content they describe. | 3 |
| **Quotation** | The Guinness World Records quote is in a `blockquote` with its source in `cite`. | 1 |
| **Published and submitted** | GitHub Pages site is live and loads correctly; pull request into `main` is open with the live URL in the description; PR URL submitted in Canvas. | 1 |
| **Total** |  | **15** |

## ✅ Before You Submit

Check the following:

- [ ] Your page is named `index.html` (not `index.html.txt`) and is in the root folder
- [ ] The browser tab shows the page title from `content.txt`
- [ ] None of the "Page title:" or "Page description:" labels appear on the page
- [ ] All of the text from `content.txt` appears on the page, including the footer line
- [ ] Headings follow the outline of the page, with one `h1`
- [ ] Every requirement above is checked off
- [ ] The page passes the [W3C Markup Validator](https://validator.w3.org/#validate_by_input)
      with no errors
- [ ] You saved your file
- [ ] The page is live on GitHub Pages and the URL is in your pull request

## 🛠️ Troubleshooting

If something is not working, check these common issues first:

- Did you save the file?
- Is the file named exactly `index.html`, with no hidden `.txt` on the end?
- Does "Pokémon" show up as strange characters like "PokÃ©mon"? Add
  `<meta charset="utf-8">` to the `head`.
- Is your visible page content inside the `body` element?
- Are your opening and closing tags in the correct places, and nested properly?
- Are there quotation marks around your attribute values?
- Is every `li` inside a `ul` or `ol`, and every `dt`/`dd` inside a `dl`?

## 📚 Resources

- [MDN — HTML elements reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements)
- [MDN — Headings and paragraphs](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Headings_and_paragraphs)
- [MDN — Lists](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Lists)
- [MDN — Advanced text features](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Advanced_text_features)
  (description lists, quotations, abbreviations, and `time`)
- [MDN — Document and website structure](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Structuring_documents)
- [W3C Markup Validation Service](https://validator.w3.org/#validate_by_input): paste your
  HTML in to catch unclosed tags

---

The AI policy and submission instructions are in the [README](../README.md).
