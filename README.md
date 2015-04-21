Victoire CMS Form Bundle
============

Need to add a form in a victoire cms website ?
Get this form bundle and so on

First you need to have a valid Symfony2 Victoire edition.
Then you just have to run the following composer command :

    php composer.phar require friendsofvictoire/form-widget

Do not forget to add the bundle in your AppKernel !

```php
    class AppKernel extends Kernel
    {
        public function registerBundles()
        {
            $bundles = array(
                ...
                new Victoire\Widget\FormBundle\VictoireWidgetFormBundle(),
            );

            return $bundles;
        }
    }
```
