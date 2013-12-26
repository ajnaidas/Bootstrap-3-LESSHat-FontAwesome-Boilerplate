Bootstrap-3-LESSHat-FontAwesome-Boilerplate
===========================================

[Bootstrap 3](http://getbootstrap.com) Boilerplate packed with [Font Awesome 4](http://fontawesome.io/) and [LESS Hat 2](http://lesshat.com/)

# [Bootstrap](http://getbootstrap.com) [![Build Status](https://secure.travis-ci.org/twbs/bootstrap.png)](http://travis-ci.org/twbs/bootstrap) [![devDependency Status](https://david-dm.org/twbs/bootstrap/dev-status.png)](https://david-dm.org/twbs/bootstrap#info=devDependencies)
[![Selenium Test Status](https://saucelabs.com/browser-matrix/bootstrap.svg)](https://saucelabs.com/u/bootstrap)

Bootstrap is a sleek, intuitive, and powerful front-end framework for faster and easier web development, created and maintained by [Mark Otto](http://twitter.com/mdo) and [Jacob Thornton](http://twitter.com/fat).

To get started, check out <http://getbootstrap.com>!

# [Font Awesome](http://fontawesome.io/)

Font Awesome gives you scalable vector icons that can instantly be customized — size, color, drop shadow, and anything that can be done with the power of CSS.

Check out <http://fontawesome.io/>!

# [LESS Hat](http://lesshat.com/)

A Kick-ass LESS Mixin Library for everyone.

Check out <http://lesshat.com/>!

## What's Included

This Boilerplate makes use of Bootstrap 3's uncompiled version which is written in [LESS](http://lesscss.org/), a dynamic stylesheet language that extends CSS. Bootstrap compiles the LESS files originally using [GruntJS](http://gruntjs.com/), but the choice of compiler is basically up to the user's preference. [LESS.app](http://incident57.com/less/) satisfies the most basic requirements for a decent compiler. 

The Boilerplate also makes use of the [LESS Hat](http://lesshat.com/) Mixin Library to extend LESS's capabilities. If you are familiar with [SASS](http://sass-lang.com/), LESS + LESS Hat is basically the counterpart of the SASS + [Compass](http://compass-style.org/) combo.

And lastly, it makes use of the [Font Awesome](http://fontawesome.io/) Icons, which is actually designed for Bootstrap use to widen up the options of the designer. It arms us with over 369 Optimized, Scalable vector icons.

------------------------------------------------------------------------------------------------------------------------

Files included in the boilerplate is organized for the most basic requirements for a website. It is originally tailored for my preference and is not designed to satisfy architectural requirements for a large web project. Thus, you may edit it according to your preference or what you think works best for your project and the size of your team if you're not going solo.

```
Bootstrap_3.0.2_Boilerplate/
├── public/
|   ├── css/                                        # This should be set as the Output path of your LESS Compiler
|        ├── style.css
|        └── vendor/
|             ├── bootstrap-theme.css
|             └── bootstrap-theme.min.css
|   ├── fonts/                                      # Font Awesome, Glyphicons and other Webfonts should be stored here
|        ├── fontawesome-webfont.eot
|        ├── fontawesome-webfont.svg
|        ├── fontawesome-webfont.ttf
|        ├── fontawesome-webfont.woff
|        ├── FontAwesome.otf
|        ├── glyphicons-halflings-regular.eot
|        ├── glyphicons-halflings-regular.svg
|        ├── glyphicons-halflings-regular.ttf
|        └── glyphicons-halflings-regular.woff
|   └── js/                                         # Javascript Files
|        ├── main.js
|        ├── plugins.js
|        └── vendor/
|             ├── bootstrap.js
|             ├── bootstrap.min.js
|             ├── jquery-1.10.2.min.js
|             ├── modernizr-2.6.2.min.js
└── src/
    └── less/
        ├── bootstrap/                              # Bootstrap LESS Files
        ├── fontawesome/                            # Fontawesome LESS Files
        ├── lesshat/                                # LESS HAT LESS Files
        ├── partials/                               # Your Project Styles
        └── style.less                              # Import everything here for compilation
```

## Credits & Thanks

+ [Twitter Bootstrap](http://getbootstrap.com)
+ [Font Awesome](http://fontawesome.io/)
+ [LESS Hat](http://lesshat.com/)


