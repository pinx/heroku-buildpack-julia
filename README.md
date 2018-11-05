# Julia buildpack for Heroku

This is a [Heroku buildpack][0] for adding a [Julia binary][1] to your environment.


## Versions

* Buildpack: `0.3`
* Julia: `1.0.0`


## Usage

Add this line to the .buildpacks file in your project:

`https://github.com/pinx/heroku-buildpack-julia.git`

or use the command `heroku buildpacks:set`

In your project, create a file `package.jl` with any
Julia code you want to run after installation.


## Thanks

Inspiration for this buildpack was taken from:

* <https://github.com/dscout/wkhtmltopdf-buildpack>
* <https://github.com/HashNuke/heroku-buildpack-elixir>

I use these buildpacks on my [dokku][2] host.


## License

[MIT License](https://github.com/pinx/heroku-buildpack-julia/blob/master/LICENSE)


[0]: http://devcenter.heroku.com/articles/buildpacks
[1]: http://julialang.org
[2]: http://dokku.viewdocs.io/dokku/

