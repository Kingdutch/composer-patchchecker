# Patchchecker

This is an unsupported proof of concept.

The patchchecker can look at a composer.json's `extra.patches` field and
detects GitHub URLs for patches as well as specifically formatted patch
names for Drupal.org.

The downside to this method is that GitHub PR URLs shouldn't be used for
patches because they are not static. Additionally people adding patches
for Drupal.org often don't correctly use the right formatting for the
patch name.

With those constraints in mind the patchchecker has never been developed
into a fully usable tool.
