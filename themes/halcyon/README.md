# Halcyon Theme for Grav

![Halcyon](assets/readme_1.png)

Halcyon Days is a modern and stylish HTML5/CSS3 template with a pixel-perfect design and smooth effects. It’s especially fitting for a portfolio or start-up website, but it’s also very versatile and can be used for many other projects. Template is designed by [Peter Finlan](http://peterfinlan.com/) exclusively for Codrops.

# Built on:

* Bootstrap
* FlexSlider
* Smooth Scroll
* jQuery Waypoints
* Animate.css

# Features:

* HTML5 and CSS3
* Fully Responsive
* Attractive and modern design
* Various templates for presenting your content

# Installation

Installing the Halcyon theme can be done in one of two ways. Our GPM (Grav Package Manager) installation method enables you to quickly and easily install the theme with a simple terminal command, while the manual method enables you to do so via a zip file.

The theme by itself is useful, but you may have an easier time getting up and running by installing a skeleton. The [Halcyon Site Skeleton](https://github.com/getgrav/grav-skeleton-halcyon-site) is a self-contained repository for a complete sites which includes: sample content, configuration, theme, and plugins.

## GPM Installation (Preferred)

The simplest way to install this theme is via the [Grav Package Manager (GPM)](http://learn.getgrav.org/advanced/grav-gpm) through your system's Terminal (also called the command line).  From the root of your Grav install type:

    bin/gpm install halcyon

This will install the Halcyon theme into your `/user/themes` directory within Grav. Its files can be found under `/your/site/grav/user/themes/halcyon`.

## Manual Installation

To install this theme, just download the zip version of this repository and unzip it under `/your/site/grav/user/themes`. Then, rename the folder to `halcyon`. You can find these files either on [GitHub](https://github.com/getgrav/grav-theme-halcyon) or via [GetGrav.org](http://getgrav.org/downloads/themes).

You should now have all the theme files under

    /your/site/grav/user/themes/halcyon

>> NOTE: This theme is a modular component for Grav which requires the [Grav](http://github.com/getgrav/grav), [Error](https://github.com/getgrav/grav-theme-error) and [Problems](https://github.com/getgrav/grav-plugin-problems) plugins.

# Updating

As development for the Halcyon theme continues, new versions may become available that add additional features and functionality, improve compatibility with newer Grav releases, and generally provide a better user experience. Updating Halcyon is easy, and can be done through Grav's GPM system, as well as manually.

## GPM Update (Preferred)

The simplest way to update this theme is via the [Grav Package Manager (GPM)](http://learn.getgrav.org/advanced/grav-gpm). You can do this with this by navigating to the root directory of your Grav install using your system's Terminal (also called command line) and typing the following:

    bin/gpm update halcyon

This command will check your Grav install to see if your Halcyon theme is due for an update. If a newer release is found, you will be asked whether or not you wish to update. To continue, type `y` and hit enter. The theme will automatically update and clear Grav's cache.

## Manual Update

Manually updating Halcyon is pretty simple. Here is what you will need to do to get this done:

* Delete the `your/site/user/themes/halcyon` directory.
* Download the new version of the Halcyon theme from either [GitHub](https://github.com/getgrav/grav-theme-halcyon) or [GetGrav.org](http://getgrav.org/downloads/themes).
* Unzip the zip file in `your/site/user/themes` and rename the resulting folder to `halcyon`.
* Clear the Grav cache. The simplest way to do this is by going to the root Grav directory in terminal and typing `bin/grav clear-cache`.

> Note: Any changes you have made to any of the files listed under this directory will also be removed and replaced by the new set. Any files located elsewhere (for example a YAML settings file placed in `user/config/themes`) will remain intact.

# Setup

If you want to set Halcyon as the default theme, you can do so by following these steps:

* Navigate to `/your/site/grav/user/config`.
* Open the **system.yaml** file.
* Change the `theme:` setting to `theme: halcyon`.
* Save your changes.
* Clear the Grav cache. The simplest way to do this is by going to the root Grav directory in Terminal and typing `bin/grav clear-cache`.

Once this is done, you should be able to see the new theme on the frontend. Keep in mind any customizations made to the previous theme will not be reflected as all of the theme and templating information is now being pulled from the **halcyon** folder.


# Configuration
Configuration of Halcyon theme consist of two parts:
* configuration file (from [skeleton](https://github.com/getgrav/grav-skeleton-halcyon-site/commits?author=hexplor)): "user/config/site.yaml"
* header variables (inside markdown files)

In configuration file you can set basic values for header, footer and general.
In markdown files, you can manage page content and overall look of the separate section. For example, below is a portfolio.md header section:

```markdown
portfolio:
  - title: "Creative Minds"
    img: portfolio-01.jpg
    img_text: View More
    img_url: "#"
    content: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc ultricies nulla non metus pulvinar imperdiet. Praesent non adipiscing libero."
```

In above example you can specify title, image, roll over text, url and content for each separate portfolio element.

Rest of the sections is made in similar approach. Remember to preserve original idenation to avoid issues.


# Credits

### Bootstrap

[Bootstrap](http://getbootstrap.com/) by Twitter. Licensed under [MIT](https://github.com/twbs/bootstrap/blob/master/LICENSE)

### FancyBox

[FancyBox](http://fancyapps.com/fancybox/) by fancyApps. Licensed under [CC BY-NC 3.0](http://creativecommons.org/licenses/by-nc/3.0/)

### FlexSlider

[FlexSlider](http://www.woothemes.com/flexslider/) by WooThemes. Licensed under [GNU GENERAL PUBLIC LICENSE](https://github.com/woothemes/FlexSlider/blob/master/LICENSE.md)

### Waypoints

[Waypoints](https://github.com/imakewebthings/waypoints) by Caleb Troughton. Licensed under [MIT](https://github.com/imakewebthings/waypoints/blog/master/licenses.txt)

### Animate.css

[Animate.css](https://daneden.github.io/animate.css/) by Dan Eden

### Font Awesome Icons

[Font Awesome](http://fortawesome.github.io/Font-Awesome/) by Dave Gandy. Licensed under [MIT](http://opensource.org/licenses/mit-license.html)

## Misc

Follow Pete: [Twitter](https://twitter.com/peterfinlan), [Dribbble](http://www.dribbble.com/peterfinlan), [GitHub](https://github.com/peterfinlan)

Follow Codrops: [Twitter](http://www.twitter.com/codrops), [Facebook](http://www.facebook.com/pages/Codrops/159107397912), [Google+](https://plus.google.com/101095823814290637419), [GitHub](https://github.com/codrops), [Pinterest](http://www.pinterest.com/codrops/)
