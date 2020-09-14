CHANGELOG for 6.0.x
===================

This changelog references the relevant changes (bug and security fixes) done
in 6.0 versions.

### 6.0.0 (unreleased)

* Added Symfony 5 support.
* Added Elasticsearch 7 support.
* Dropped Symfony 3 support.
* Dropped Elasticsearch 5 and 6 support.
* Dropped PHP 7.1 support.
* [BC break] Signature of `FOS\ElasticaBundle\Persister\ObjectPersisterInterface::handlesObject()` was changed.
* [BC break] Signature of methods `getNbResults`, `getNbPages`, `getCurrentPage`, `setCurrentPage`, `getMaxPerPage` and `setMaxPerPage` from interface `FOS\ElasticaBundle\Provider\PagerInterface` were changed.
* [BC break] Signature of method `FOS\ElasticaBundle\Finder\FinderInterface::find()` was changed.
* [BC break] Signature of methods `findPaginated`, `createPaginatorAdapter` and `createRawPaginatorAdapter` from interface `FOS\ElasticaBundle\Finder\PaginatedFinderInterface` were changed.
* [BC break] Removed `Elastica\Type`.
* [BC break] Removed `_parent`.
* [BC Break] Removed `FOS\ElasticaBundle\Persister\Event\Events` class, use class events instead.