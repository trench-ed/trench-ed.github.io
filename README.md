# Trench-ED Website
[**Website**](trench-ed.github.io) | [**Theme**](https://html5up.net/) | [**TrEnCh Project**](https://trenchproject.github.io/)

### Adding a Page

To add a page to the website, create a Markdown file at the repository's root (i.e. top level in the `trench-ed.github.io` folder, not in any other deeper folder). Examples of this are `intro.md` or `elements.md`. At the top of the file, add the following YAML:

```
---
title: Page Title
---
```

Underneath that, add the page contents.

When you `git commit -am "message"` and `git push`, the main page will have a new button with the page title as the text of the button. Clicking on the button will open the page.

### Accordions

There are two elements required to create an accordion: a toggle button and the accordion content container. They appear as follows:

**Button**:
```
<button onclick="toggle('accordion1')">
Accordion 1</button>
```
**Content**:
```
<div id="accordion1" class="w3-container w3-hide">
  <p>Some text..</p>
</div>
```

The important thing here is that `toggle(<name>)` in the button must be equivalent to `id=<name>` in the content.
