# JMS Serializer Strict JSON Bundle

> Symfony integration for [JustBlackBird\JmsSerializerStrictJson](https://github.com/JustBlackBird/jms-serializer-strict-json)

## Installation

Run in the command line:

```shell
composer require justblackbird/jms-serializer-strict-json-bundle
```

Enable the bundle

```php
// app/AppKernel.php
class AppKernel extends Kernel
{
    public function registerBundles()
    {
        $bundles = array(
            // ...
            new JustBlackBird\JmsSerializerStrictJsonBundle\JustBlackBirdJmsSerializerStrictJsonBundle(),
        );

        // ...
    }
}
```

Make sure you enable the bundle **after** `JmsSerializerBundle`.

## License

[Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0) (c) Dmitriy Simushev
