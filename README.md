# ip-theme
A custom Hugo theme for my website [Innermost Pixels](https://innermostpixels.com). It is based on my simple-as-possible [barebones theme](https://github.com/2altoids/hugo-barebones-theme) I wrote as a template for future themes.

## installation
```sh
hugo new site my-site
cd my-site
git clone https://github.com/2altoids/ip-theme themes/ip-theme
echo "theme = 'ip-theme'" >> config.toml
cp themes/ip-theme/static/* static/
```

## notes
- Front matter content can be added to a list page using a `_index.md` file in that page's directory.
