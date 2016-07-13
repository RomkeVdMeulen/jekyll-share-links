# Social Media Share Buttons for Jekyll Templates

This is a snippet of [Liquid](https://shopify.github.io/liquid/) that you can
include in your [Jekyll](https://jekyllrb.com/) templates. It will show a
number of buttons using SVG social media icons from the Font Awesome iconset,
taken from [here](https://github.com/encharm/Font-Awesome-SVG-PNG). It uses
static links, no JavaScript required.

Example of how it'll look:

![example screenshot](https://raw.githubusercontent.com/RomkeVdMeulen/jekyll-share-links/master/example.png)

Example SASS styling:

```scss

#share {
    margin: 50px 0;

    h2 {
        font-size: 1.2em;
    }

    ul {
        list-style: none;

        li {
            display: inline;

            a {
                &:hover {
                    text-decoration: none;
                }

                svg {
                    width: 50px;
                    height: 50px;
                    fill: #333;
                }
            }
        }
    }
}
```
