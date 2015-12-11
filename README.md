# Standard Event Interface for PHP

PSR is cool, but they kept a 2 years old ticket to define a standard eventing system.

https://github.com/php-fig/fig-standards/issues/44

Let s just make it happen..

## Dependencies

All the work of this repo is from symfony repository. It s their code,
it s just they implements the wrong namespace
to let a standard occur.

## Install

The recommended way to install Component is through composer.

```json
{

  "minimum-stability": "dev",
  "require": {
    "php": ">=5.5.0",
    "st/event-dispatcher": "1.0.5"
  },
  "repositories": [
    {
      "type": "git",
      "url": "git@github.com:maboiteaspam/st-event-dispatcher.git"
    }
  ]
}

```

# see also

The original repo that i basically repackaged.

- https://github.com/symfony/event-dispatcher

A concrete standard implementation to consume in your projects

- https://github.com/maboiteaspam/im-event-dispatcher
