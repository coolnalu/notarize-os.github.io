# Notarize open source - https://notarize-os.github.io

Notarize's Open Source page is built with [Jekyll][] and
[jekyll-theme-hackcss][].

[Jekyll]: https://github.com/jekyll/jekyll
[jekyll-theme-hackcss]: https://github.com/wemake-services/jekyll-theme-hackcss

### If you want to run it locally
--
1. Clone the master branch or [download the zip][]
2. `bundle install` the gems from the Gemfile
3. `rake serve` and open a browser to `http://127.0.0.1:4000`

[download the zip]:
https://github.com/notarize-os/notarize-os.github.io/archive/master.zip

### Notes about local build
--
- use the rake task `rake serve` to run it locally at `http://127.0.0.1:4000/`
- you're automatically authenticated to see the public_repositories from
the notarize-os GitHub org
- all the Jekyll files are compiled and placed in the `_site` folder
- livereload is also enabled via the rake task

## License

MIT License. See [LICENSE][] for more information.

[LICENSE]: https://github.com/notarize-os/notarize-os.github.io/LICENSE

