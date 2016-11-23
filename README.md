# data-pacifique-nea
Data portal website for the IRD center of Nouméa (Institute for Research and Development)

The website is built with the static website engine [Hugo](http://gohugo.io/) using the [material-docs theme](http://github.com/digitalcraftsman/hugo-material-docs).

## Quick start

Install with `git`:

    git clone https://github.com/acheype/data-pacifique-nea.git data-pacifique-nea
    
There are 2 options to serve the data portal website.

* you can serve the website by using the development server included in Hugo :
``` sh
hugo server
```
And go to [localhost:1313](http://localhost:1313) to see the website.

* you can generate the website to the `public/` directory, ready to be deployed to your webserver :
``` sh
hugo
```
