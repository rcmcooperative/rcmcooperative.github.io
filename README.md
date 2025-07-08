# RCM Cooperatie website repository
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

This repository builds on the template created and maintained by *The Turing Way* team members and shared under CC-BY 4.0 for reuse: https://github.com/alan-turing-institute/reproducible-project-template.


## Vision and Mission
- **Vision:** A cooperative of community managers dedicated to creating equitable, resilient and collaborative research
- **Mission:** To empower research communities through capacity building, growing a network of community leaders and ecosystem facilitation.

## About

<!-- Motivation and background in a nutshell. -->

## Roadmap & Milestones

<!-- - **Goals:** Clear overview of overarching and short-term goals.
- **Outcomes:** Description of expected results and deliverables. -->

## The Team

<!-- - **Members:** List of team members and their roles in the project.
- **Roles & Responsibilities:** [Team Directory](link-to-directory) outlines roles, responsibilities and their ways of working. -->

## Contributing

<!-- - **Guidelines:** [Contribution Guidelines](link-to-guidelines) for contributors.
- **Code of Conduct:** [Code of Conduct](link-to-coc) ensures a respectful project environment.
- **Resource Plans:** Details on available resources and recommended practices for the project team. -->

## Licensing

Documentation is licensed under the CC-BY-4.0 License. 
Code is shared under an MIT license. 
See the LICENSE.md file for details.

## Citing & Acknowledgement

<!-- - **Citation Instructions:** How to cite the project.
- **Acknowledgment:** Recognising contributions by different members. -->

## Contact

- **Reach Out:** cassandra.gouldvanpraag@rcmcooperative.com

## Editing this website
This site uses the [Agency jekyll theme](https://github.com/raviriley/agency-jekyll-theme), shared under an [MIT License](https://opensource.org/licenses/MIT).

### Things we might like to edit and where to find them
The below tree shows the layout of this repo and what the main files/directories contain. 
If a directory is not described or expended, you probably won't need to edit it when making changes to the website :) 

```

├── 404.html
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── Gemfile
├── Gemfile.lock
├── LICENSE.md
├── README.md
├── _config.yml         #<-- contains basic site description and the path to the logo
├── _data
│   ├── navigation.yml  #<-- defines the items on the top nav bar
│   ├── sitetext.yml    #<-- provides the header text (and icons) or each section on the home page
│   └── style.yml
├── _includes           #<-- contains the html layouts for each section
│   ├── about.html
│   ├── clients.html
│   ├── contact.html
│   ├── footer.html
│   ├── head.html
│   ├── join_grid.html
│   ├── modals.html
│   ├── nav.html
│   ├── navheader.html
│   ├── portfolio_grid.html
│   ├── services.html
│   ├── team_grid.html
│   └── timeline.html
├── _join_options       #<-- contains an .md file for each of the grid items in the "join" section
│   ├── leadership.md
│   ├── member.md
│   └── support.md
├── _layouts
│   ├── default.html
│   ├── home.html       #<-- defines which of the html layouts from _includes are used on the home page
│   └── page.html
├── _portfolio          #<-- contains an .md file for each of the projects to be displayed (grid items) in the "portfolio" section
│   ├── example.md   
│   ├── project1.md
│   └── project2.md
├── _sass
│   ├── base
│   ├── components
│   └── layout          #<-- the css styling for the different sections
│       ├── _contact.scss
│       ├── _footer.scss
│       ├── _join.scss
│       ├── _masthead.scss
│       ├── _portfolio.scss
│       ├── _services.scss
│       ├── _team.scss
│       └── _timeline.scss
├── _site               #<-- ignore everything in here. It is generated automatically when you build the site
├── _team               #<-- a .md file for each team member
│   ├── cassandra-gouldvanpraag.md
│   ├── emma-karoune.md
│   └── malvika-sharan.md
├── assets
│   ├── css
│   ├── img
│   │   ├── clients     #<-- all logo images, inc RCM Coop logo used on the nav bar
│   │   │   ├── creative-market.jpg
│   │   │   ├── designmodo.jpg
│   │   │   ├── envato.jpg
│   │   │   ├── header.png
│   │   │   ├── rcmcoop-peach.jpg
│   │   │   ├── rcmcoop-peach.png
│   │   │   ├── rcmcoop-peach.svg
│   │   │   └── themeforest.jpg
│   │   ├── contact.png #<-- the image behind the contact section
│   │   ├── emoji-rcm-coop.gif
│   │   ├── favicon-old.png
│   │   ├── favicon.png
│   │   ├── header.png  #<-- the background image at the top of the home page
│   │   ├── join        #<-- images used in the "join" grid items
│   │   │   ├── aaron-santelices-z03mWBdAq5I-unsplash.jpg
│   │   │   ├── johannes-plenio-voQ97kezCx0-unsplash.jpg
│   │   │   └── steven-kamenar-MMJx78V7xS8-unsplash.jpg
│   │   ├── logo-RCM-coop-dev.pptx  #<-- a .pptx file where you can play with logo images
│   │   ├── logo-black-square.png   #<-- a bunch of logo variations
│   │   ├── logo-footer-grey.png
│   │   ├── logo-footer-old.png
│   │   ├── logo-footer.png
│   │   ├── logo-old.png
│   │   ├── logo-tagline-black.png
│   │   ├── logo-tagline-grey-box.png
│   │   ├── logo-tagline-white.png
│   │   ├── logo-tagline.png
│   │   ├── logo.png
│   │   ├── portfolio
│   │   │   ├── 04-thumbnail.jpg
│   │   │   ├── 05-thumbnail.jpg
│   │   │   └── 06-thumbnail.jpg
│   │   ├── team     #<-- team member images
│   │   │   ├── 500x500.jpg
│   │   │   ├── cassandra-gouldvanpraag.jpg
│   │   │   ├── emma-karoune.jpg
│   │   │   └── malvika-sharan.jpg
│   │   └── timeline
│   ├── js
│   ├── tmp-old-webfonts
│   └── webfonts
├── index.md      #<-- defines the layout to be used in the home page (currently calls ~/_layouts/home.html)
├── jekyll-agency.gemspec
├── legal.md      #<-- privacy policy text

```


### Adding a new member
1. Add a photo of the new member to ~/assets/img/team. The photo should be 500 x 500 px
2. Copy an existing member .md file from ~/_team. Rename it with the new members name, seperating first and last name with a hyphen (no spaces)
3. Edit the .md file front matter to refer to the new member. Note the value `modalID` must be unique. We suggest you use `team[Theirnamewithnospaces]`
4. Edit the body text with their bio. Note this uses standard markdown syntax

### Testing your changes locally
After you have edited the website, it is useful to build it locally to see if it looks/works as expected before pushing changes or submitting a PR. 
To set up your environment to develop this website locally theme, clone this repo or your own fork of it.

```sh
$ git clone https://github.com/rcmcooperative/rcmcooperative.github.io.git
$ cd rcmcooperative.github.io
```

Then run:

```sh
$ bundle install
```

To make a local build, run this. (Using the `--trace` flag for verbose errors.)

```sh
$ bundle exec jekyll serve --trace
```

Then open your browser at:

- http://127.0.0.1:4000/

Add pages, documents, data, etc. like normal to test the theme's contents. As you make modifications, your site will regenerate and you should see the changes in the browser after a refresh.


## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="http://malvikasharan.github.io/"><img src="https://avatars.githubusercontent.com/u/5370471?v=4?s=100" width="100px;" alt="Malvika Sharan"/><br /><sub><b>Malvika Sharan</b></sub></a><br /><a href="#content-malvikasharan" title="Content">🖋</a> <a href="#doc-malvikasharan" title="Documentation">📖</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!



### Checklist for setting an online repository 

- [x] Add a README file
- [x] Add a [CONTRIBUTING](CONTRIBUTING.md) file
- [x] Add a [LICENSE](LICENSE.md)
- [x] Add a [Code of Conduct](CODE_OF_CONDUCT.md)
- [ ] Install [all-contributors](https://allcontributors.org/) bot
- [ ] .gitignore file (choose from a template)
- [ ] Issue templates
    - [ ] Optionally Install [Welcome/behavior](https://github.com/behaviorbot/welcome) bot (see The Turing Way [config](https://github.com/alan-turing-institute/the-turing-way/blob/main/.github/config.yml))
- [ ] Connect repo with Zenodo
- [ ] Add cff file for citation
- [ ] Add badges