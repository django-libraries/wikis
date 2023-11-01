# Django Template Wikis

A wiki based on Django template.

## Installation

Install the package via pip:

```bash
pip install django-wikis
```

## Configuration

After installing the package, add it to your `INSTALLED_APPS` in the `settings.py` file of your Django project:

```python
INSTALLED_APPS = [
    # ... other apps,
    'wikis',
]
```

Include the wiki urls in your project's `urls.py` file:

```python
from django.urls import include, path

urlpatterns = [
    # ... other urls,
    path('wikis/', include('wikis.urls')),
]
```

## Usage

Navigate to `/wikis/` in your browser to access the wiki.

## Development

To contribute or report issues, please visit
the [wikis](https://github.com/django-libraries/wikis).

## License

This project is licensed under the [MIT License](LICENSE).