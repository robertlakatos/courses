# Prompt Engineering

## Colab

1.  [Introduction](https://colab.research.google.com/drive/1YQ_knmayDKmjcPlbNKf-YQ0jWhVUf4k3?usp=sharing)
2.  [Prompting](https://colab.research.google.com/drive/1PYxgrxd6rD7cn1jENHVkHWTbjnVN3EW-?usp=sharing), [(WR)](https://colab.research.google.com/drive/1tvi1Ua4VfkYN3jlrm8SjxGG1KiDDT9eC?usp=sharing)
3.  [Review Analyst](https://colab.research.google.com/drive/1NzrWdwNX-m0FLaHPqAdFSepIEQUrw856?usp=sharing), [(WR)](https://colab.research.google.com/drive/1eV3mpq4VE9j4RyiTUlgbgdMNLn3qtZF5?usp=sharing)
4.  [Marketing Generator](https://colab.research.google.com/drive/1YGMEnzPt3JuQrrWa6hjeK5Fb7YyhSXjC?usp=sharing), [(WR)](https://colab.research.google.com/drive/19sK3RIFlcqrHHPmjZ0oW3qgCMEaypcNM?usp=sharing)
5.  [Random-Personas](https://colab.research.google.com/drive/1omsHFzTKCSvWEL1kQkfaXB89CXMVGSpu?usp=sharing), [(WR)](https://colab.research.google.com/drive/1p0GaeR46ewrVhk2cctqBj3syV7Ym5-bH?usp=sharing)
6.  [Chatbot](https://colab.research.google.com/drive/17BSv8vPRQ8Wihts9kr5C9sVD306tVq_2?usp=sharing), [(WR)](https://colab.research.google.com/drive/14IOBAPzSYzWzlF0WYGpWxIPti25-MFXG?usp=sharing)
7.  [Car dealership AI Assistant](https://colab.research.google.com/drive/14PqyQjkSSI3nTVKMc_djmnGRMX_ItCUG?usp=sharing), [(WR)](https://colab.research.google.com/drive/1T59NZ0Ia1kWmYxuFIYQUZpP7kdeZzhKR?usp=sharing)
8.  [Coding](https://colab.research.google.com/drive/1Nc-Vcdn8UIWC4sBNmRdPyH8wyszkkCX-?usp=sharing), [(WR)](https://colab.research.google.com/drive/1W82dexmF65BANFW5xpHGH401SbTbUY_9?usp=sharing)
9.  [Lyrics and Music](https://colab.research.google.com/drive/1-fvTWO8IzKeQqkO5aVJrfLGoHwahXa2g?usp=sharing), [(WR)](https://colab.research.google.com/drive/1TTez3Lwti5dmTLzqKxUj7GFPfV93kF5o?usp=sharing)
10. [Object Detection with YOLO V8](https://colab.research.google.com/drive/1Ykj5QhoNTVAa6ECwpqU8TQ2H-uy_vG3L?usp=sharing), [(WR)](https://colab.research.google.com/drive/1scsdMcIYYGtD4Gun4l03_F8_pa6kzhkR?usp=sharing)
11. [YOLO v8 Training with Annotated Dataset](https://colab.research.google.com/drive/1no4_hqUyQRmeQY1Thi3mQayXFcF6vY1R?usp=sharing), [(WR)](https://colab.research.google.com/drive/1CXfmDSVruhHv6TB-AVaJJumgL07y3SKB?usp=sharing)
12. [Conclusion](https://colab.research.google.com/drive/1JO-b_GI96bWIDmwg81MMe_j2ppQnqoVa?usp=sharing)

## <FONT COLOR="red">The notebooks are licensed under the Creative [Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)](https://creativecommons.org/). This means that you can freely copy, distribute, and modify the notebook by authors ([Balázs Harangi](https://inf.unideb.hu/dr-harangi-balazs), [András Hajdu](https://inf.unideb.hu/munkatars/4250), and [Róbert Lakatos](https://inf.unideb.hu/lakatos-robert-tanarseged)), but not for commercial purposes. Additionally, if you modify the notebook, you must cite them as the original creators and share the modified version under the same terms.
</FONT>

# The Cayman theme

[![.github/workflows/ci.yaml](https://github.com/pages-themes/cayman/actions/workflows/ci.yaml/badge.svg)](https://github.com/pages-themes/cayman/actions/workflows/ci.yaml) [![Gem Version](https://badge.fury.io/rb/jekyll-theme-cayman.svg)](https://badge.fury.io/rb/jekyll-theme-cayman)

*Cayman is a Jekyll theme for GitHub Pages. You can [preview the theme to see what it looks like](http://pages-themes.github.io/cayman), or even [use it today](#usage).*

![Thumbnail of Cayman](thumbnail.png)

## Usage

To use the Cayman theme:

1. Add the following to your site's `_config.yml`:

    ```yml
    remote_theme: pages-themes/cayman@v0.2.0
    plugins:
    - jekyll-remote-theme # add this line to the plugins list if you already have one
    ```

2. Optionally, if you'd like to preview your site on your computer, add the following to your site's `Gemfile`:

    ```ruby
    gem "github-pages", group: :jekyll_plugins
    ```

## Customizing

### Configuration variables

Cayman will respect the following variables, if set in your site's `_config.yml`:

```yml
title: [The title of your site]
description: [A short description of your site's purpose]
```

Additionally, you may choose to set the following optional variables:

```yml
show_downloads: ["true" or "false" (unquoted) to indicate whether to provide a download URL]
google_analytics: [Your Google Analytics tracking ID]
```

### Stylesheet

If you'd like to add your own custom styles:

1. Create a file called `/assets/css/style.scss` in your site
2. Add the following content to the top of the file, exactly as shown:
    ```scss
    ---
    ---

    @import "{{ site.theme }}";
    ```
3. Add any custom CSS (or Sass, including imports) you'd like immediately after the `@import` line

*Note: If you'd like to change the theme's Sass variables, you must set new values before the `@import` line in your stylesheet.*

### Layouts

If you'd like to change the theme's HTML layout:

1. For some changes such as a custom `favicon`, you can add custom files in your local `_includes` folder. The files [provided with the theme](https://github.com/pages-themes/cayman/tree/master/_includes) provide a starting point and are included by the [original layout template](https://github.com/pages-themes/cayman/blob/master/_layouts/default.html).
2. For more extensive changes, [copy the original template](https://github.com/pages-themes/cayman/blob/master/_layouts/default.html) from the theme's repository<br />(*Pro-tip: click "raw" to make copying easier*)
3. Create a file called `/_layouts/default.html` in your site
4. Paste the default layout content copied in the first step
5. Customize the layout as you'd like

### Customizing Google Analytics code

Google has released several iterations to their Google Analytics code over the years since this theme was first created. If you would like to take advantage of the latest code, paste it into `_includes/head-custom-google-analytics.html` in your Jekyll site.

### Overriding GitHub-generated URLs

Templates often rely on URLs supplied by GitHub such as links to your repository or links to download your project. If you'd like to override one or more default URLs:

1. Look at [the template source](https://github.com/pages-themes/cayman/blob/master/_layouts/default.html) to determine the name of the variable. It will be in the form of `{{ site.github.zip_url }}`.
2. Specify the URL that you'd like the template to use in your site's `_config.yml`. For example, if the variable was `site.github.url`, you'd add the following:
    ```yml
    github:
      zip_url: http://example.com/download.zip
      another_url: another value
    ```
3. When your site is built, Jekyll will use the URL you specified, rather than the default one provided by GitHub.

*Note: You must remove the `site.` prefix, and each variable name (after the `github.`) should be indent with two space below `github:`.*

For more information, see [the Jekyll variables documentation](https://jekyllrb.com/docs/variables/).

## Roadmap

See the [open issues](https://github.com/pages-themes/cayman/issues) for a list of proposed features (and known issues).

## Project philosophy

The Cayman theme is intended to make it quick and easy for GitHub Pages users to create their first (or 100th) website. The theme should meet the vast majority of users' needs out of the box, erring on the side of simplicity rather than flexibility, and provide users the opportunity to opt-in to additional complexity if they have specific needs or wish to further customize their experience (such as adding custom CSS or modifying the default layout). It should also look great, but that goes without saying.

## Contributing

Interested in contributing to Cayman? We'd love your help. Cayman is an open source project, built one contribution at a time by users like you. See [the CONTRIBUTING file](docs/CONTRIBUTING.md) for instructions on how to contribute.

### Previewing the theme locally

If you'd like to preview the theme locally (for example, in the process of proposing a change):

1. Clone down the theme's repository (`git clone https://github.com/pages-themes/cayman`)
2. `cd` into the theme's directory
3. Run `script/bootstrap` to install the necessary dependencies
4. Run `bundle exec jekyll serve` to start the preview server
5. Visit [`localhost:4000`](http://localhost:4000) in your browser to preview the theme

### Running tests

The theme contains a minimal test suite, to ensure a site with the theme would build successfully. To run the tests, simply run `script/cibuild`. You'll need to run `script/bootstrap` once before the test script will work.
