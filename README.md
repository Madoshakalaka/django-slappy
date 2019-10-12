# django-slappy

run python in slack

## Installation

Need an already running django site

`pip install django-slappy`

1. Add "django_slappy" to your INSTALLED_APPS setting like this

    ```python
        INSTALLED_APPS = [
            ...
            'django_slappy',
        ]
    ```

2. Include the URLconf in your project urls.py like this

    path('slappy/', include('django_slappy.urls')),
