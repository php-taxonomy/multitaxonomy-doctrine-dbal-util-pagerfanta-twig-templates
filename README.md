# multitaxonomy-dbal-util-pagerfanta-twig-templates
Multitaxonomy for DBAL-Util persistence (Twig templates for pagerfanta objects)

These templates are used like a library.

```php
$c->loadFromExtension('twig', [
    'paths' => [
        '%kernel.project_dir%/vendor/php-taxonomy/multitaxonomy-dbal-util-pagerfanta-twig-templates' => 'MultiTaxonomyDbalUtilBundle',
        // templates is the new directory name in Symfony 4
        // '%kernel.project_dir%/vendor/php-taxonomy/multitaxonomy-dbal-util-bundle/Resources/views' => 'MultiTaxonomyDbalUtilBundle',
    ],
]);
```

* https://symfony.com/doc/current/templating/namespaced_paths.html
  * https://symfony.com/doc/3.3/templating/namespaced_paths.html
* https://symfony.com/blog/new-in-symfony-3-3-a-simpler-way-to-get-the-project-root-directory
* http://fabien.potencier.org/symfony4-directory-structure.html
