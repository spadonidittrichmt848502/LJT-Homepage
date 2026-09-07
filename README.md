# LJT-Homepage

Personal academic homepage of **Junteng Liu**, first-year PhD candidate at the [HKUST NLP Group](https://github.com/hkust-nlp), Hong Kong University of Science and Technology.

## About

The site contains:

- **About** (`_pages/about.md`) — biography, research interests, education, research experience, publications, honors, and contact information.
- **Publications** (`_pages/publications.html`, `_publications/`) — full publication list grouped into preprints and conference papers.

## Contact

- Email: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- GitHub: [Vicent0205](https://github.com/Vicent0205)
- Google Scholar: [Junteng Liu](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- X (Twitter): [@junteng88716710](https://twitter.com/junteng88716710)

## Running locally

Site-wide configuration lives in `_config.yml`; the header menu is configured in `_data/navigation.yml`.

1. Install `ruby-dev`, `bundler`, and `nodejs`.

   On most Linux distributions and Windows Subsystem for Linux:

   ```bash
   sudo apt install ruby-dev ruby-bundler nodejs
   ```

   On macOS:

   ```bash
   brew install ruby
   brew install node
   gem install bundler
   ```

2. Install the Ruby dependencies:

   ```bash
   bundle install
   ```

3. Serve the site at `localhost:4000`:

   ```bash
   bundle exec jekyll serve -l -H localhost
   ```

Alternatively, with [Docker](https://www.docker.com/) installed:

```bash
chmod -R 777 .
docker compose up
```

## Credits

Built with [Jekyll](https://jekyllrb.com) using the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template, itself a fork of the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme (© 2016 Michael Rose, MIT License — see `LICENSE`).
