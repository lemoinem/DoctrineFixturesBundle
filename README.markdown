WMC's DoctrineFixturesBundle
============================

This bundle integrates the [Doctrine2 Data Fixtures library](https://github.com/doctrine/data-fixtures)
into Symfony so that you can load data fixtures programmatically into the Doctrine ORM or ODM.

Documentation on how to install and use this bundle is available in the
Symfony2 [documentation](http://symfony.com/doc/current/bundles/DoctrineFixturesBundle/index.html).

Fork
----

This fork supports an additional structure to automatically find Fixtures. In
addition to support Fixtures in `@Bundle/DataFixtures`, we also look for
Fixtures in `@Bundle/src/DataFixtures`.

To use this fork, add the repository to your `composer.json`:

```
php composer.phar config repositories.wmc-doctrine-fixtures vcs https://github.com/wemakecustom/DoctrineFixturesBundle.git
```

The rest is **exactly** as using the standard bundle.
