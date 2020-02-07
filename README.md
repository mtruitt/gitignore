# Base .gitignore for working out of root the on a WordPress site

Ideally, you would not work out of the root of a site. However, hosts like WP Engine/Pantheon map git this way.

### General notes

While this is mainly setup for WP Engine. It generally will work for any normal WordPress setup.

This .gitignore removes everything but wp-content, plugins and themes.

Yes, we are tracking plugins. This is because till recently WP Engine did not have an easy way (composer) to handle this and ideally we would rather use composer.

You will notice this is a bit cleaner/able to catch more than what is provided by [WP Engine](https://wpengine.com/wp-content/uploads/2020/02/recommended-gitignore-no-wp.txt).

* Left twentytwenty theme by default so there was a fallback
* .DS files are caught by the .*


*If you have any suggestions or modifications feel free to submit and issue or do a PR.*

*I cannot take credit for all of this as it was built up from trial/error and from others overtime.*