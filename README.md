# min-content-max-content-bug

## Issue
The following style rules when applied to an img tag generate different outputs depending on the browser.

```css
img {
    max-height: 150px;
    min-height: min-content;
}
```

## Expected output

An image 150px x 150px

## Actual output

An image 850px x 850px

## Notes:
Versions and OS:
- OS: macOS Monterey
- Chrome: Version 106.0.5249.119 (Official Build) (arm64)
- Safari: Version 16.0 (17614.1.25.9.10, 17614)