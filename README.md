# Usage

## Add a new article

Copy writing template and update `permalink` and `id`.

Add link on `./index.md`

Do a local build test (see below).

Check spelling
```
cspell lint "**/*.md"
```

### Build locally

```sh
bundle install
bundle exec jekyll serve --watch
```

### Structure

https://jekyllrb.com/docs/structure/

### Syntax & Formatting

setting URL
use permalink in each page
.html is optional

## Links

[{{Display Text}}]({{URL}})
[Reading in the Original](https://xkcd.com/2168/)
Or just have links be themselves, rather than plaintext: https://kramdown.gettalong.org/syntax.html#automatic-links

Use H6 for footnotes, like:

###### footnotes:

### Dev

Prettier in .prettierrc based on Collabswarm
Are changes? 
```
yarn prettier --check .
```
Dry run 
```
yarn prettier --write .
```
Execute 
```
yarn prettier --write .
```


### Hosting setup
[Cloudflare SSL strict + GH Pages HTTPS](https://community.cloudflare.com/t/github-pages-require-disabling-cfs-http-proxy/147401/27)