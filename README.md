# Hugo collapsible code block

A [Hugo](https://gohugo.io) shortcode for collapsible code blocks in your web pages.

The solution wraps the out of the box highlight feature of hugo in additional divs with attached javascript logic. This solution does not require jquery.

## Example usage

This example creates a collapsible code block for CSS code.

```
{{< code css >}}

... lots of css code ...

{{< /code >}}
```

## Usage tips

1. This shortcode accepts the same parameters as the default [highlight shortcode](https://gohugo.io/content-management/syntax-highlighting/#highlight-shortcode) does.
2. Be sure to include the CSS and Javascript files from the static folder into your site, or the shortcode will not work as expected. 
