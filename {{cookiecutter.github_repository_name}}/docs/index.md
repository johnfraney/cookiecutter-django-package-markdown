## Quickstart

Install {{ cookiecutter.project_name }}:

```bash
pip install {{ cookiecutter.github_repository_name }}
```

Add it to your `INSTALLED_APPS`:

```python
INSTALLED_APPS = (
    ...
    '{{ cookiecutter.django_app_name }}',
    ...
)
```

Add URL patterns:

```python
from {{ cookiecutter.django_app_name }} import urls as {{ cookiecutter.django_app_name }}_urls


urlpatterns = [
    ...
    url(r'^', include({{ cookiecutter.django_app_name }}_urls)),
    ...
]
```

## Running Tests

Does the code actually work?

```bash
source <YOURVIRTUALENV>/bin/activate
(myenv) $ pip install tox
(myenv) $ tox
```
