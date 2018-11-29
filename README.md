# Hugo Serif Theme

Serif is a beautiful small business theme for Hugo. It contains content types for the archetypical small business website. The theme is fully responsive, blazing fast and artfully illustrated.

![Hugo Serif Theme screenshot](/images/screenshot.png)

## Theme features

- Services (Content Type)
- Team (Content Type)
- Testimonials (Content Type)
- Features (Data)
- SCSS (Hugo Pipelines)
- Responsive design
- Bootstrap 4 grid and media queries only
- Responsive menu managed in `config.toml`
- 100/100 Google Lighthouse speed score
- Under 30KB without images or 80KB with images and illustrations ⚡
- Robust example content included
- Royalty free illustrations included

## Installation

Inside the folder of your Hugo site run:

    $ cd themes
    $ git clone https://github.com/jugglerx/hugo-serif-theme.git

For more information read the official [setup guide](//gohugo.io/overview/installing/) of Hugo.

## Getting started

After installing the Serif theme successfully it requires a just a few more steps to get your site finally running.

### Adding example content

The fastest way to get started is to copy the example content. Copy the contents of the `exampleSite` folder to the root folder of your Hugo site. This theme comes with content for the following content types: `services`, `team`, `testimonials` and includes JSON data for `features` and `contact`. It also includes the `config.toml` file which has an example menu.

## Running Hugo

After installing the theme, generate the Hugo site.

```
hugo
```

Hugo's built-in local server.

```
hugo server
```

Now enter [`localhost:1313`](http://localhost:1313) in the address bar of your browser.
