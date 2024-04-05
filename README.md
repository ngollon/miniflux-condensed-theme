# miniflux-condensed-theme

This is a condensed theme for miniflux that I use forbetter overview on a smartphone.

Paste this into Settings -> Custom CSS

```
li.item-meta-icons-read,
li.item-meta-icons-star,
li.item-meta-info-reading-time,
span.category 
{
   display:none;
margin:0px;
}

/* Hide the Share list item */
.entry-actions ul li:has(> a[data-share-status="share"]) {
    display: none;
}

/* Hide the Download list item */
.entry-actions ul li:has(> button[data-fetch-content-entry="true"]) {
    display: none;
}

article.entry-item div,
article.entry-item ul
{
  display:inline;
}

.item {
  border-left: 0px;
  border-top: 1px;
  margin-bottom: 6px;
}
```
