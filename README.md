# Alfred Shlink

[![Latest Version on GitHub][ico-version]][link-releases]
[![Software License][ico-license]](LICENSE.md)

Shorten URLs with Shlink in Alfred

## Install

> **NOTE**  
> This workflow requires Alfred 5 or later.

**Via Alfred**

Download the Alfred file from the [Releases](https://github.com/owenvoke/alfred-shlink/releases).

Then configure the environment variables in the Alfred configuration.

> **Note**  
> This workflow requires PHP to be installed, consider using Brew.  
> ```shell
> brew install php
> ```

## Usage

This workflow provides a single command to generate a short URL with your Shlink instance:

```shell
shlink {url}
```

### Available Environment Variables

- `SHLINK_DOMAIN` (**REQUIRED**) - The URL of your Shlink instance (e.g. `https://s.example.org`)
- `SHLINK_API_KEY` (**REQUIRED**) - The [API key](https://shlink.io/documentation/api-docs/authentication) for your Shlink instance
- `SHLINK_CODE_LENGTH` - The length of short URL codes (default: `6`)
- `SHLINK_EXISTING` - Whether to use existing short URLs if they are found (default: `false`)
- `SHLINK_VALIDATE_URL` - Whether to validate the provided URL (default: `false`)
- `SHLINK_TAGS` - A comma-separated list of tags to apply to your short URLs

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## Security

If you discover any security related issues, please email security@voke.dev instead of using the issue tracker.

## Credits

- [Owen Voke][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

## Treeware

You're free to use this package, but if it makes it to your production environment you are required to buy the world a tree.

It’s now common knowledge that one of the best tools to tackle the climate crisis and keep our temperatures from rising above 1.5C is to plant trees. If you support this package and contribute to the Treeware forest you’ll be creating employment for local families and restoring wildlife habitats.

You can buy trees [here][link-treeware-gifting].

Read more about Treeware at [treeware.earth][link-treeware].

[ico-version]: https://img.shields.io/github/v/tag/owenvoke/alfred-shlink.svg?sort=semver&style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square

[link-releases]: https://github.com/owenvoke/alfred-shlink/releases
[link-treeware]: https://treeware.earth
[link-treeware-gifting]: https://ecologi.com/owenvoke?gift-trees
[link-author]: https://github.com/owenvoke
[link-contributors]: ../../contributors
