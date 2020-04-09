# OCDS Show for Public Private Partnerships

A tool for displaying OCDS releases and records, that conform to the [OCDS for Public Private Partnerships](https://standard.open-contracting.org/profiles/ppp/) profile. [Try it now!](https://open-contracting.github.io/ocds-show-ppp/)

The OCDS for PPPs profile makes major changes to the OCDS schema; this tool is a tailored version of [OCDS Show](https://github.com/open-contracting/ocds-show), which works with OCDS data in general, to take those changes into account.

For complete documentation of this tool, visit [OCDS Show](https://github.com/open-contracting/ocds-show)'s repository.

## Maintenance

This repository should be the same as [OCDS Show](https://github.com/open-contracting/ocds-show), except for:

* `css/custom.css`: `#release-tabs .tab-pane` background-color. Uncommented styles.
* `index.html`: Change "OCDS Show" to "OCDS Show for Public Private Partnerships", "Input a valid OCDS record/release" to "Input a valid OCDS for PPPs record/release", `record_release.html` to `record_release_ppp.html`, `release.html` to `release_ppp.html`. Uncomment social witness code.

If you run (assuming you have a local copy of the `ocds-show` repository in a parallel directory):

```shell
diff -q --exclude=.git --exclude=node_modules --exclude=package-lock.json --exclude=README.md -ru ../ocds-show .
```

It should only return:

```
Files ../ocds-show/css/custom.css and ./css/custom.css differ
Files ../ocds-show/index.html and ./index.html differ
```

If you remove the `-q` option, there should only be the differences above.

## Issues

Report issues for this extension in the [ocds-show](https://github.com/open-contracting/ocds-show/issues) repository.
