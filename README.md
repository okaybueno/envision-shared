# Envision-shared
Shared code for Envision frontend web apps

This repo holds:
* style (SCSS)
* fonts

Include this repo in your package.json, as follows:

    "dependencies": {
    ...
        "envision-shared": "github:okaybueno/envision-shared",
    }
    
The scss can be imported directly into your stylesheets like so:

    @import '~envision-shared/scss/main';
    
    
Fonts will have to be copied into a folder in your repo during the build process 
    