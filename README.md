This repo contains files for a website. 

Website URL is `https://lillianmccallum.github.io/`.

## How to update the website:

1. Make all the changes so that it is ready to be updated.
2. In VS Code use the terminal at the bottom (if not there hit ctrl+`)
3. In the terminal type `git status` and hit enter, you should see some red and/or green text showing the names of the modified or added files.
4. In the terminal type `git add .` and hit enter.
5. In the terminal type `git commit -m "update"` and possibly replace update with a description of what changed.
6. In the terminal type `git push`
 
## Adding a new page:

1. Go to the category folder (e.g., \_blog, \_trips)
2. Add a new file named `<title>.md`
3. Add at the top:

```
---
layout: default
title: <title>
---
```
4. Go to the landing page for the category (e.g., \_trips>all-trip-reports.md)
5. Add the link in the table so it shows up as a link on the page

## How to add an image:
1. Add the image to the assets>images folder
2. In the page you want to add it, put the following:
```
<img src="./assets/images/<title>.<type>" alt="Picture of me hiking" width="600">
```

and replace `<title>.<type>` with the file name and type

### For PDFs:
1. Put the PDF in the assets>pdfs folder and use the following in the webpage:
```
<img src="./assets/pdfs/<title>.pdfs" alt="Picture of me hiking" width="600">
```
