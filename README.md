# OCDS Show for PPPs

A tool for displaying [OCDS for PPPs](https://standard.open-contracting.org/profiles/ppp/) releases and records.

## Development

This repository should be the same as [OCDS Show](https://github.com/open-contracting/ocds-show), except for:

* `css/custom.css`: `#release-tabs .tab-pane` background-color. Uncommented styles.
* `index.html`: Change "OCDS Show" to "OCDS Show for Public Private Partnerships", "Input a valid OCDS record/release" to "Input a valid OCDS for PPPs record/release", `record_release.html` to `record_release_ppp.html`, `release.html` to `release_ppp.html`. Uncomment social witness code.

## Issues

Report issues for this extension in the [ocds-show](https://github.com/open-contracting/ocds-show/issues) repository.
