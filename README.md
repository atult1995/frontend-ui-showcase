# WebDesign

A collection of small, reusable HTML, CSS, and JavaScript examples for common web design patterns. Each example is a standalone page that can be opened directly in a browser or adapted for another project, including Angular applications.

## Examples

| Page                                                           | Description                                                                           | Assets or dependencies                                 |
| -------------------------------------------------------------- | ------------------------------------------------------------------------------------- | ------------------------------------------------------ |
| [ImageGallery.html](ImageGallery.html)                         | Responsive-style image grid with hover rotation/zoom and a full-screen image preview. | Images in `img/img1.jpg` through `img/img8.jpg`        |
| [Login.html](Login.html)                                       | Glass-style login form with floating labels for email and password fields.            | Font Awesome CDN                                       |
| [RegistrationForm.html](RegistrationForm.html)                 | Registration form with name, mobile, email, and message fields.                       | `img/module-1.jpg`, Font Awesome CDN                   |
| [RegistrationForm2.html](RegistrationForm2.html)               | Feedback form with floating labels and a full-page background image.                  | `img/module-5.jpg`, Font Awesome CDN                   |
| [SliderWithNextPrevButton.html](SliderWithNextPrevButton.html) | Image slider with captions and previous/next controls.                                | `img/slider/s1.jpg` through `s3.jpg`, Font Awesome CDN |

## Project Structure

Each HTML page has a matching external stylesheet:

```text
WebDesign/
├── ImageGallery.html
├── ImageGallery.css
├── Login.html
├── Login.css
├── RegistrationForm.html
├── RegistrationForm.css
├── RegistrationForm2.html
├── RegistrationForm2.css
├── SliderWithNextPrevButton.html
└── SliderWithNextPrevButton.css
```

Image assets are expected under an `img/` directory. The HTML files use relative paths, so keep that directory beside the example files or update the paths when moving a page.

## Getting Started

1. Clone or download this repository.
2. Open the `WebDesign` folder in VS Code.
3. Open any `.html` file in a browser. A local web server extension such as Live Server is optional.
4. Add your own images to the expected `img/` paths, or replace the image paths in the HTML and CSS files.

## Notes

- The forms are front-end demonstrations only; they do not submit data to a backend.
- The gallery preview and slider controls use the JavaScript included in their HTML files.
- Login, registration, and slider icons are loaded from Font Awesome's CDN, so an internet connection is required for those icons.
- Customize the external `.css` files to change each example without editing the page structure.

## License

No license is currently specified for this collection. Add a license file before distributing the code as a library or template.
