# RCM Cooperative: Website repo

We use Roxo Hugo template, shared under the open source MIT License.

## Installation

1. Add the repository into your Hugo Project repository as a submodule, `git submodule add git@github.com:StaticMania/roxo-hugo.git themes/roxo-hugo`.
2. Copy the `data`, `content`, `static`, `resources` & `config.toml` files from the `exampleSite` directory and paste it on you Hugo Project repository/directory. From the site home directory:

    cp -a themes/roxo-hugo/exampleSite/* .

3. Build your site with `hugo serve` (make sure `hugo` is installed first) and see the result at `http://localhost:1313/`.
4. Set to build the github page using Actions (see [guide from Hugo](https://gohugo.io/hosting-and-deployment/hosting-on-github/))

## Add GitHub Actions

See guidance here: https://gohugo.io/hosting-and-deployment/hosting-on-github/

## Contact

Have questions for the RCM Cooperative team? [Email Us](mailto:cassandra.gouldvanpraag@rcmcooperative.com)

## Licensing

This Repository is licensed under the [MIT](https://github.com/StaticMania/roxo-hugo/blob/master/LICENSE) License
