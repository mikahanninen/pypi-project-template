# pypi-project-template

## Minimal steps to create new PyPi project

1. create folder structure / clone this project
2. edit _PROJECT_NAME_ in `pyproject.toml` and rename folder `PROJECT_NAME` to match
3. edit _AUTHOR_EMAIL_ and _AUTHOR_FULLNAME_ ("firstname lastname") in `pyproject.toml`
4. edit _VERSION_NUMBER_ in `pyproject.toml` and `__init__.py` to match (eg. "0.1.0")
5. edit `README.md`, this represents README on project homepage in PyPi
6. (OPTIONAL) edit `pyproject.toml` dependencies, license and other specifics if needed
7. `poetry build`
8. `poetry publish -u PYPI_USERNAME -p PYPI_PASSWORD`

After project has been created all information about the project can be changed.

Extra information: https://johnfraney.ca/posts/2019/05/28/create-publish-python-package-poetry/
