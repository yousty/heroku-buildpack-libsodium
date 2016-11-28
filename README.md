# Heroku buildpack: libsodium

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for the `libsodium` library.

See [Using Multiple Buildpacks for an App](https://devcenter.heroku.com/articles/using-multiple-buildpacks-for-an-app) In brief:

    heroku buildpacks:add --index 1 https://github.com/<user>/heroku-buildpack-libsodium.git

If you use the `RbNaCl` Ruby library, make sure to check out the [rbnacl-libsodium](https://github.com/cryptosphere/rbnacl-libsodium) Ruby Gem to compile `libsodium`.
