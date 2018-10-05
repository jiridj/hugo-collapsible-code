# Hugo collapsible code block

A [Hugo](https://gohugo.io) shortcode for collapsible code blocks in your web pages. 

## Example usage

This example creates a collapsible code block with the default height of 300px.

```
{{< more >}}
''' css

... lots of css code ...

'''
{{< /more >}}
```

This example overrides the default height and sets it to 500px.

```
{{< more 500 >}}
''' css

... lots of css code ...

'''
{{< /more >}}
```
