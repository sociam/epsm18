# Website for the Ethics and Privacy for Social Machines, Social Groups and Aggreations workshop

## Acknowledgements
The site structure (including the basics of this README) was forked from https://mobilevis.github.io

## Configuring site properties

Site metadata is in [_config.yml](_config.yml)

## Editing the index and about pages

You can edit the front page, [index.md](index.md), call for papers, [cfp.md](cfp.md) and about [about.md](about.md) pages here and changes will be reflected on [sociam.github.io/epsm_workshop_18](https://sociam.github.io/epsm_workshop_18).

## Editing the style

Change the style in [assets/main.scss](assets/main.scss).

## Adding images and other assets

Add images to [assets](assets/). You can also add remote iframe content to a page or post by directly inserting an `<iframe />` tag.

## Local editing

To edit the site remotely, open a terminal where you want to work locally and follow these instructions:

0. Ensure that git and ruby are installed.
1. Clone the repository: `git clone https://github.com/sociam/epsm_workshop_18.git` and `cd epsm_workshop_18.git`.
2. Install bundler: `gem install bundler`.
3. Install the bundle: `bundle install`; Update as needed: `bundle update`.
4. Run locally at [localhost:4000](http://localhost:4000/): `bundle exec jekyll serve`
5. Make edits to the site (see above)
6. Add, commit, and push your changes: `git add *`, `git commit -m 'your commit message'`, `git push`.
