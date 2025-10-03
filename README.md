## Customizations for this project
change home icon from double arrow to home icon: replace line 29 of icons.js with 
>      
>     <path d="M8.707 1.5a1 1 0 0 0-1.414 0L.646 8.146a.5.5 0 0 0 .708.708L2 8.207V13.5A1.5 1.5 0 0 0 3.5 15h9a1.5 1.5 0 0 0 1.5-1.5V8.207l.646.647a.5.5 0 0 0 .708-.708L13 5.793V2.5a.5.5 0 0 0-.5-.5h-1a.5.5 0 0 0-.5.5v1.293zM13 7.207V13.5a.5.5 0 0 1-.5.5h-9a.5.5 0 0 1-.5-.5V7.207l5-5z"/>"
>     

## Quire Eleventy
[![CircleCI](https://dl.circleci.com/status-badge/img/gh/thegetty/quire/tree/main.svg?style=shield)](https://dl.circleci.com/status-badge/redirect/gh/thegetty/quire/tree/main)

The [Quire Eleventy package](https://github.com/thegetty/quire/tree/main/packages/11ty) contains configuration and modules for the [Eleventy static site generator](https://11ty.dev). This package is published to npm as [`@thegetty/quire-11ty`](https://www.npmjs.com/package/@thegetty/quire-11ty) and installed by the [`@thegetty/quire-cli`](https://www.npmjs.com/package/@thegetty/quire-cli) to build [Quire](https://quire.getty.edu) projects.

### Quire Eleventy Features

#### Components and Shortcodes

Component-driven page templates using [shortcode components](https://github.com/thegetty/quire/tree/main/packages/11ty/_includes/components) and [universal template shortcodes](https://www.11ty.dev/docs/shortcodes/#universal-shortcodes) that support [JavaScript](https://www.11ty.dev/docs/languages/javascript/), [Liquid](https://www.11ty.dev/docs/languages/liquid/), [Nunjucks](https://www.11ty.dev/docs/languages/nunjucks/), and [WebC](https://www.11ty.dev/docs/languages/webc/) templates.

#### Image Processing

Automatic processing of images as [IIIF](https://iiif.io) assets.

#### PDF Output

Generates HTML output for generation of PDF books using [`Paged.js`](https://pagedjs.org)

#### EPUB Output

Generates HTML output for generation of EPUB book using [`EPUB.js`](http://futurepress.org)
