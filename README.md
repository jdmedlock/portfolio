# Portfolio

<a href="https://zenhub.com"><img src="https://raw.githubusercontent.com/ZenHubIO/support/master/zenhub-badge.png"></a>

[Portfolio](https://jdmedlock.github.io/portfolio/) was developed as
part of the
[Grow With Google Front-End Nanodegree Scholarship](https://www.udacity.com/grow-with-google)
sponsored by [Google](https://grow.google/) and offered through
[Udacity](https://www.udacity.com/course/front-end-web-developer-nanodegree--nd001).

The objective of this application is to showcase my projects, contributions to
the Open Source community, and to demonstrate my developer skills.

[Features](#features) | [Development](#development) | [Runtime](#runtime) |
[Authors](#authors) | [License](#license) | [Release Notes](releasenotes.md)


## Features

Portfolio is a single-page web app that provides users with a convenient,
clickable list of the major applications I've developed and the articles I've
contributed to the Open Source community.

### Roadmap

TBD

## Development

### Project Organization

Several key subdirectories exist under the main `pixelartmaker` app directory
including:

- `portfolio`

  The application root directory contains support files including this
  `readme.md`, `LICENSE`, and `.gitignore`. It also contains `index.html`
  which, although a source file, is located here since the app is hosted on
  GitHub Pages.

- `src`

  Other than the `index.html` file containing the home page all source files
  are maintained in the following subdirectories of the `src` directory.
  * `css` contains the primary styling specification (`index.css`) as well as
  a supplemental specification (`responsive.css`) containing overrides for
  various breakpoints so the app renders correctly across a variety of devices.
  * `img` contains the images used in the portfolio page.

  Source files for any future pages added to the app should be created in
  their own subdirectories under `src`.

### Built With

The main technologies and libraries used in the development of this Portfolio
are shown in the following table. It's significant to note that at this time
there's no Javascript employed since the site is static.

| Technology/Library                             | Purpose                    |
|:-----------------------------------------------|:---------------------------|
| [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) | Web page styling & RWD  |
| [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) | Web page markup |

### Git Branches

- `master`: Only updated from PR's from the development branch for release. This
branch always reflects the current production release.
- `development`: Reflects the candidate code for the next release. Since this is
a personal project with only a single developer no feature branches are used
at this time. If any are used in the future they will be pulled into this
branch for testing and peer review as part of the PR process.
- `feature branches`: These aren't used at this time (see above), but are
documented here so their relationship to the `development` branch will be
understood. These are individual branches created for new features and
bug fixes. There are 4 basic types of branches:
bug, feature, refactor and style, after the type comes the name, it should
specify on top of the branch type. For example `feature/course-review`.

## Runtime

[Portfolio](https://jdmedlock.github.io/portfolio/) is deployed to
GitHub Pages. Changes moved into the `master` branch is
automatically promoted to the GitHub Pages site for this app.

## Authors

- [Jim Medlock](https://github.com/jdmedlock)

## License

[MIT](https://tldrlegal.com/license/mit-license)

## Release Notes

- Initial release (5/6/2018)
