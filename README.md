# Personal webpage of Oliver Butterley

This site is live at <https://oliver-butterley.github.io/> and <https://mat.uniroma2.it/butterley/>.

## Architecture

This is a  [Jekyll] site. It is built and published on [GitHub Pages][github-pages] using the [Jekyll workflow]. 
Style is provided by the [`minima`][minima] theme.

## Building and previewing the site locally

Assuming [Jekyll] and [Bundler] are installed:

1.  Change working directory to the project root.
2.  Run `bundle install`.
3.  Run `bundle exec jekyll serve` to build and preview the site.

## Deploy site to server by `rsync` over `ssh`

1. Create a key pair `ssh-keygen -m PEM -t rsa -b 4096`
2. Upload private key as `secrets.SERVER_SSH_KEY` on github
3. Copy public key to server using `ssh-copy-id` with username and host

[github-pages]: https://docs.github.com/en/pages
[Jekyll]: https://jekyllrb.com
[Bundler]: https://bundler.io
[Jekyll workflow]: https://github.com/actions/starter-workflows/blob/main/pages/jekyll.yml
[minima]: https://github.com/jekyll/minima

