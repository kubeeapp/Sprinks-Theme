# Sprinks-Theme

[![Version](https://img.shields.io/badge/version-0.0.1-green.svg?style=flat-square&labelColor=2a2139&color=f92aad)](#)

[![maintained](https://img.shields.io/maintenance/yes/2019.svg?style=flat-square&labelColor=2a2139&color=f92aad)](#)

> Do you remember that endless summer back in '84? Cruising down the ocean-highway with the top down, the wind in our hair and heads buzzing with neon dreams?
> No, I don't remember it either, but with this experimental theme we can go there.
> <https://github.com/robb0wen/synthwave-vscode>

## Installation

* Find your homeassistant directory containing your configuration (let's say `~/.homeassistant/`)
* Change into `~/.homeassistant/themes` (create the `themes` directory, if it does not exist, you then might have to restart HA)
* `$ wget https://raw.githubusercontent.com/kubeeapp/sprinks-theme/master/themes/sprinks.yaml` downloads the `.yaml` file directly where it should reside

* Make sure Home Assistant knows about your new theme file by adding the following to your `configuration.yaml`

``` yaml
frontend:
  themes: !include_dir_merge_named themes
```

* Finally enable the theme from your profile page or `configuration.yaml`

**Extras**
Optionally you can install [sprinks-theme-js](https://github.com/kubeeapp/sprinks-theme-js) which adds some additional styling not possible using the a .yaml theme file.

### Screenshots

![1](https://i.imgur.com/DHbEScs9.png)

![2](https://i.imgur.com/bLhZFHsy.png)

![3](https://i.imgur.com/BcyjeJsz.png)

![3](https://i.imgur.com/WXg241s7.png)
