
# Instructions
Fork and checkout the assignment repository. (The forking will happen for you automatically if your repo was made through GitHub Classroom.) Create files as described below. Commit and push your changes. Make AT LEAST three substantive commits.

In Canvas, submit a link to your GitHub repository.

# Requirements
* Repository should have at least three separate _**substantive**_ commits, showing different stages of progress. Each commit should have a useful message.

* Files are organized in a professional way. **You MUST use this folder structure.** All publicly visible files, including HTML files, exist in a folder named `/public`. CSS file(s) in a folder named 'css' (i.e., `/public/css`), Javascript files (if any) in a folder named 'js' (`/public/js`), image files in a folder named 'img' (`/public/img`), and all other files (if any, e.g., font files) in a folder named 'static' (`/public/static`).

* All files have web-appropriate names (no spaces; use dash or underscore), and appropriate extensions (`\*.htm`, `\*.html`, `\*.css`, etc.)

* Three separate HTML pages, including `index.html`. Home page MUST be named `index.htm` or `index.html` (Either extension is fine for HTML files.)

* All pages have a common nav bar (on the top or left) that links the three pages. You MUST use a Bootstrap-style navbar. Pages use the same base style sheet(s), and have a common look and feel.

* One page shows user information (should be fake), showing name, country or origin, birthdate, age, email address (clickable `mailto:` link that opens an email browser!), and a (fake) profile picture of the (fake) user. See https://randomuser.me for examples.

* One page includes a table of books. Table MUST have at the following columns (title, author(s), year published, publisher, page count, MSRP) and at four to eight rows of data.

* On the same page as your table of data, include a `<form>`suitable for adding rows to the table. (It doesn't need to *do* anything yet.) Include one input element for each column in the table. Use the appropriate input type. Format the form using an appropriate Bootstrap recipe.

* Use the current production version of [Bootstrap][bootstrap] on all pages. On all pages, also include a custom style sheet that overrides *at least* the following Bootstrap defaults: background color, text color, header color, link color.

* In your custom CSS file, also write at least one declaration for an element by CSS class and one declaration for an element by id. Use those elements in your pages.

* Do NOT use `<style>` tags or the `style=""` attribute to apply CSS. All CSS should be in your custom CSS file.

* Do NOT use deprecated HTML tags like `<center>` or `<font>`. This sort of styling information (and any `<b>bold</b>`, `<i>italics</i>`) should be accomplished via CSS instead. Use CSS margin or padding declarations instead of multiple `<br>` tags for vertical spacing.

* The pages should include at least two images (overall). Show the image thumbnails on the page. Link the thumbnails to larger versions of the same images. Include citation or attribution for each image. (This is _**NOT**_ `alt` text, and should be visible to anyone viewing the page.)

[bootstrap]:https://getbootstrap.com/docs/
