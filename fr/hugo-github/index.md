# Building your Github page with Hugo


A quick and simple step-by-step guide on how to host your Hugo website on Github.  

<!--more-->
{{< admonition warning >}}
Sorry, this page is still under construction. Subscribe to the newsletter to stay updated. :innocent:

## 1 figure {#figure}

Example `figure` input:

```markdown
{{</* figure src="/images/theme-documentation-built-in-shortcodes/lighthouse.jpg" title="Lighthouse (figure)" */>}}
```

The rendered output looks like this:

{{< figure src="/images/theme-documentation-built-in-shortcodes/lighthouse.jpg" title="Lighthouse (figure)" >}}

The corresponding HTML code looks like this:

```html
<figure>
    <img src="/images/theme-documentation-built-in-shortcodes/lighthouse.jpg"/>
    <figcaption>
        <h4>Lighthouse (figure)</h4>
    </figcaption>
</figure>
```

