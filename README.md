# Hugo collapsible code block

A [Hugo](https://gohugo.io) shortcode for collapsible code blocks in your web pages.

The solution wraps the out of the box highlight feature of hugo in additional divs with attached javascript logic. This solution does not require jquery.

## Example usage

This example creates a collapsible code block.

```
{{< more >}}
''' css

... lots of css code ...

'''
{{< /more >}}
```
