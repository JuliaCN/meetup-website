# JuliaCN meetup website

This repository hosts the [landing page of JuliaCN meetup events](https://juliacn.github.io/meetup-website/).
The website is built with [Franklin.jl](https://github.com/tlienart/Franklin.jl), and the
master branch is automatically deployed by Github Actions.

## Deploy

To view the site locally, install `Franklin` and run `serve()` in the root of this repository.
A manifest is provided to exactly reproduce the package dependencies as used by CI.

### To serve
```bash
julia --project -e "using Franklin; serve()"
```

### To publish
```bash
julia --project -e "using Franklin; publish()"
```
