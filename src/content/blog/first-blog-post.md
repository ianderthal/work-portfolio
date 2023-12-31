---
title: "Individual posts, Axe Dev Tools"
excerpt: "Where does the excerpt start to get pulled in?"
publishDate: "2023-12-29T11:39:36.050Z"
image: "https://images.unsplash.com/photo-1618220179428-22790b461013?auto=format&fit=crop&w=927&h=927"
# category slug: choose from "./src/data/category.js"
category: "personal"
# remove this line to publish
# draft: true
# author slug: choose from "./src/data/authors.js"
author: "ian-gallardo"
tags: [accessibility, a11y, front-end, testing, limit of tags, you can also use spaces and special characters#*$#)]
---

# Surely your content here

[ ] Accessibility checks for the blog post
[ ] incorporate a spot for alt text in hero image
[ ] add label to dark/light mode switcher in the footer 

---

## Content Header h2

| Table Heading 1 | Table Heading 2 | Center align | Right align | Table Heading 5 |
| :-------------- | :-------------- | :----------: | ----------: | :-------------- |
| Item 1          | Item 2          |    Item 3    |      Item 4 | Item 5          |
| Item 1          | Item 2          |    Item 3    |      Item 4 | Item 5          |
| Item 1          | Item 2          |    Item 3    |      Item 4 | Item 5          |
| Item 1          | Item 2          |    Item 3    |      Item 4 | Item 5          |
| Item 1          | Item 2          |    Item 3    |      Item 4 | Item 5          |

Minim id consequat adipisicing cupidatat laborum culpa veniam non consectetur et duis pariatur reprehenderit eu ex consectetur. Sunt nisi qui eiusmod ut cillum laborum Lorem officia aliquip laboris ullamco nostrud laboris non irure laboris. Cillum dolore labore Lorem deserunt mollit voluptate esse incididunt ex dolor.

## Highlighted code

Et fugiat ad nisi amet magna labore do cillum fugiat occaecat cillum Lorem proident. In sint dolor ullamco ad do adipisicing amet id excepteur Lorem aliquip sit irure veniam laborum duis cillum. Aliqua occaecat minim cillum deserunt magna sunt laboris do do irure ea nostrud consequat ut voluptate ex.

```go
package main

import (
    "fmt"
    "net/http"
)

func handler(w http.ResponseWriter, r *http.Request) {
    fmt.Fprintf(w, "Hi there, I love %s!", r.URL.Path[1:])
}

func main() {
    http.HandleFunc("/", handler)
    http.ListenAndServe(":8080", nil)
}
```

Ex amet id ex aliquip id do laborum excepteur exercitation elit sint commodo occaecat nostrud est. Nostrud pariatur esse veniam laborum non sint magna sit laboris minim in id. Aliqua pariatur pariatur excepteur adipisicing irure culpa consequat commodo et ex id ad.

## Write Headings

Some content with [links](#) and more...
