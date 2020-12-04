# Kusama Tips Widget

## Install

Using CDN: Add the following script to the end of your `<head>` section.

```html
<script src="https://unpkg.com/kusama-tips-widget/dist/bundle.min.js"></script>
```

## Usage

Binding the widget

```html
<script>
  kusamaTipsWidget.bind(document.body, {
    beneficiary: "5EhR5PRsX...",
  });
</script>
```

Use custom button element

```html
<script>
  kusamaTipsWidget.bind(document.body, {
    beneficiary: "5EhR5PRsX...",
    element: document.getElementById("my-button"),
  });
</script>
```