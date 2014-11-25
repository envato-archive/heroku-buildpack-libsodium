# Heroku buildpack: libsodium

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for the `libsodium` library.

Use the [heroku-buildpack-multi](https://github.com/ddollar/heroku-buildpack-multi) buildpack and add this buildpack to your `.buildpacks` file.

If you use the `RbNaCl` Ruby library, make sure to check out the [rbnacl-libsodium](https://github.com/cryptosphere/rbnacl-libsodium) Ruby Gem to compile `libsodium`.
