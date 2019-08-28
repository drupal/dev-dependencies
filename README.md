# drupal/dev-dependencies

This project is for use with a Composer-managed Drupal site. This project is
only needed to run the Drupal test suite on the site. Most sites probably do
not need to use this project.

## Updating

This project does not require `drupal/core`, nor does it have any conflict
statements for any version of `drupal/core`. These constraints were omitted
to avoid causing problems for sites trying to upgrade their version of
`drupal/core`. The consequence of this decision is that the version of
`drupal/dev-dependencies` might differ from the version of `drupal/core`
installed. Generally speaking, it should be okay to run a newer version of
`drupal/dev-dependencies` than `drupal/core`. Using a newer version of
`drupal/core` might not work, though, as it is possible that new test
dependencies may have been added.

## References

This project is derived from the original community project
[webflo/drupal-core-require-dev](https://github.com/webflo/drupal-core-require-dev).
It was generated from tools derived from [webflo/package-generator-drupal](https://github.com/webflo/package-generator-drupal)
and [webflo/package-generator](https://github.com/webflo/package-generator).
