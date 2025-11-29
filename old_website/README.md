This webiste is based off of the [al-folio](https://github.com/alshedivat/al-folio/) Jekyll theme.

### Notes

To render the site to look at locally:

```bash
$ bundle install
$ bundle exec jekyll serve
```

Modify everything on `source` (preferably in PRs), then when finished run:

```bash
$ ./bin/deploy --user
```

This will merge `source` with `master` appropriately. You'll probably have to go into the settings of the repo each time to ensure that the custom domain points
to pocean23.github.io 