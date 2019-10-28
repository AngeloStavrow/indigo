# Indigo Theme

Indigo is a lightweight, responsive, typography-first theme for Hugo, marked up with [microformats2](http://microformats.org) for extra [IndieWeb](https://indieweb.org) goodness, including [IndieAuth](https://indieauth.com).

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for setup and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

This theme is built and tested against the latest version of Hugo and currently requires a minimum version of 0.58. You can check what version you're running with

```
$ hugo version
```

Follow the [upgrade instructions on the Hugo website](https://gohugo.io/getting-started/installing/#upgrade-hugo) if necessary.

### Installing

Follow the [Hugo Quickstart](https://gohugo.io/getting-started/quick-start/)'s instructions on how to add a theme; the URL you'll want to use is

```
https://github.com/AngeloStavrow/indigo.git
```

### Setup

There's a sample config.toml file in the root of the indigo theme directory (`config.toml.example`); copy it to the root of your Hugo site, and rename it to `config.toml` _after_ you've made a backup of your current config.toml file (if any).

Set up the parameters in the config file, especially those in the social and `params.indieWeb` section. Social identifiers that you leave out will not be added to the footer of the site. If you prefer to use a content type other than `post`, be sure to change the `mainSections` parameter in the config file as well. For example, if you want content of type `posts` and `updates` to show up in lists:

```toml
[params]
  ...
  mainSections = ["posts", "updates"]
```

You can configure the theme to show info about the author; by default, this information is shown; if you'd prefer to leave it out, set `ShowBio` to `false`.

### Customization

Indigo will look for custom CSS in `<YOUR_HUGO_SITE>/static/css/custom.css`. This will let you add/override styling to your heart's content, while making it easy to keep Indigo up-to-date. See it in action on [angelostavrow.com](https://angelostavrow.com).

## Deployment

You can add a line to your `config.toml` file to set this theme as the default:

```toml
theme = "indigo"
```

Or, if you use `config.yaml`:

```yaml
theme: indigo
```

## Support and Maintenance

### Support Committment

Support is provided for the latest stable release of the theme on the latest stable release of Hugo. If something doesn't seem to be working right, please make sure you're using the latest version of both.

You can check what version of Hugo you're using by running the `hugo version` command; visit [the Hugo website](https://gohugo.io) for upgrade instructions.

To ensure you're building the latest version of Indigo, do the following from the command line:

```bash
# Go to the /themes/indigo folder
cd /path/to/themes/indigo

# Make sure you're on the 'master' branch, then pull in any changes
git checkout master
git pull
```

If everything is up to date and things still don't seem to be working correctly, please [open an issue](https://github.com/AngeloStavrow/indigo/issues/) and describe what's not working as expected.

Going forward, this support committment will be enforced by the `minVersion` property in **theme.toml**.

### Maintenance Process

Authors whose themes are included in the [Hugo showcase gallery](https://themes.gohugo.io) will be required to keep their theme working with the latest version of Hugo. To prepare for this, the following process will be instituted:

1. With every new release of Hugo, _once the_ `brew`_/_`chocolatey` _package is available_, the development system will be updated, and the [demo site](https://hello-indigo.glitch.me/) and the [theme gallery](https://github.com/gohugoio/hugoThemes/blob/master/README.md#testing-a-theme-with-the-hugo-themes-website-build-script) will be built locally.
2. If everything looks good, a short update will be posted to the demo site to confirm compatibility, with links to the release announcements for those versions Indigo and Hugo, as well as a link to this maintenance process documentation.
3. If either site doesn't build successfully, the problem will be fixed.

There are a few definitions and open questions that need to be considered here.

- New releases of Hugo are [announced](https://gohugo.io/news/) and can be subscribed to via RSS. The release date _may_ be estimated by the due date of [Hugo milestones](https://github.com/gohugoio/hugo/milestones).
- "Build successfully" means that the demo site renders as intended, and that the theme works as expected in the theme gallery. The gallery builds a standard site that shows off some common features of Hugo, and the demo site is meant to test and showcase features of Indigo.

## Indigo IndieWeb Features

A thorough writeup of the theme has been graciously written by @infominer33.

- [Indigo IndieWeb Features](https://web-work.tools/indieweb/indigo-indieweb-features/)

## Contributing

Please read [CONTRIBUTING.md](https://github.com/AngeloStavrow/indigo/blob/master/CONTRIBUTING.md) for details on the code of conduct, and the process for submitting bug reports, feature requests, and having your changes merged into the project.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/AngeloStavrow/indigo/tags).

## Authors

- **Angelo Stavrow** - _Initial work_ - [AngeloStavrow](https://github.com/AngeloStavrow) on GitHub

See also the list of [contributors](https://github.com/AngeloStavrow/indigo/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

The following open fonts are used in this theme:

- [Fira Sans](https://bboxtype.com/typefaces/FiraSans/#!layout=specimen) for heading text
- [Charter](https://practicaltypography.com/charter.html) for body text
- [Fira Code](https://github.com/tonsky/FiraCode) for monospaced text

Licenses are included in the theme’s `static/fonts` folder.

Most icons in the social footer are from [Font Awesome](https://fontawesome.com/). Some come directly from the service itself (e.g., Micro.blog and Glitch).
