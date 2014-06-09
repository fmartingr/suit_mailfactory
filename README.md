django-mail-factory support for django-suit
=======================================

Extra templates for [django-suit](https://github.com/darklow/django-suit) to support [django-mail-factory](https://github.com/novapost/django-mail-factory).

## Requirements

- [django-suit](https://github.com/darklow/django-suit) <= 0.2.8 (obviously)
- [django-mail-factory](https://github.com/novapost/django-mail-factory) <= 0.11

## Installation

```
pip install suit_mailfactory
```

Add to `INTALLED_APPS` before `django-mail-factory`:

```
INSTALLED_APPS = (
    'suit',
    'suit_mailfactory',  # <----
    'django.contrib.admin',
    # ...
    'mail_factory',
    # ...
)

```

## Modified templates

- templates
    - mail_factory
        - base.html
        - form.html
        - html_not_found.html
        - list.html
        - preview_message.html


## License

Same as [django-suit](https://github.com/darklow/django-suit).
