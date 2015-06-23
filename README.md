---
permalink: /
layout: main
---

# browser-mock

Display your screencaps in a mock browser window for presentations and UX mockups

1. Download the [css][dl-link]
2. Include it in your project
3. Wrap any `<img/>` tag with a `.browser-mock` class to generate the browser styling

### Example:

```HTML
<img src="image1.png"/>
```
![plain](./img/goog_plain.png)



```HTML
<div class="browser-mock">
  <img src="image1.png"/>
</div>
```

![mock](./img/goog_mock.png)

[dl-link]: https://raw.githubusercontent.com/coltontb/browser-mock/master/dist/style.css