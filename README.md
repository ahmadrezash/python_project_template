# Python Project Template (PPT)

I'm python developer for many years. I'm working with many frameworks and libraries. Always project structure is my
important point. After using Django and drf and Flask and FastAPI I'm trying to create a template for python project.
With all experience I'm trying to create a template for python project. You can use this template for your project and
suggest me what you can improve. Tnx a lot.

## Stages

* `dev` (development)
* `test`
* `prod` (production)

with split docker and requirements and config files

## Points to have better project structure

* `__init__`: just import in init file
* `services` is contain any external service (for microservices)
* using `semver` method with `bumb version` tools for versioning
* using `git strategy` for branches management system
* using commit message template e.g. `[type]:[module]-[desc]` for more readable commit messages
* using a standard linter for code quality and readability (pylint, flake8, pep8, black) -> suggest to use `pep8`
* using `Sphinx` documentation
* using `pytest` for tests

## Your Contribution:
* add new section
* improve existing section
* introduce new structure in a section

``` sh
/project
├── /src
│    ├── __init__.py
│    ├── __main__.py
│    ├── wsgi.py
│    ├── /migrations
│    ├── /main
│    │    ├── __init__.py
│    │    ├── /db
│    │    │    ├── connector.py
│    │    │    ├── session.py
│    │    │    └── base_model.py
│    │    ├── /utils
│    │    │    ├── encrypt
│    │    │    └── http
│    │    ├── /exceptions
│    │    ├── /templates
│    │    │    └── swagger.html
│    │    ├── /model
│    │    │    ├── models.py
│    │    │    ├── schemas.py
│    │    │    └── enums.py
│    │    ├── /views
│    │    │    └── swagger.py
│    │    ├── /services
│    │    │    ├── base_service.py
│    │    │    └── [service].py
│    │    ├── /translation
│    │    ├── /log
│    │    │    ├── handlers.py
│    │    │    └── helpers.py
│    │    ├── bootstrap.py
│    │    ├── urls
│    │    ├── settings.py
│    │    ├── deps
│    │    ├── celery-app.py
│    │    └── celery-conf.py
│    ├── /module1
│    │   ├── /exceptions  
│    │   ├── app.py
│    │   ├── /views
│    │   ├── /templates 
│    │   ├── /models
│    │   ├── /translation
│    │   ├── urls
│    │   ├── /services
│    └── /module2
│        └── ...
├── /logs
│   ├── app
│   ├── db
│   ├── celery
├── /statics
│   ├── css
│   ├── js
│   ├── img
├── /media
│   ├── img
├── /fixture
├── /tests
│   ├── pytest.ini
│   ├── conftest.py
│   ├── /test_api
│   ├── /test_model
│   ├── /logic
├── /docs
│   ├── docker-cmopose.yml
├── /config
│   ├── base
│   ├── dev
│   ├── prod
│   └── test
├── /docker
│   ├── /base
│   │   ├── Dodkerfile
│   │   └── docker-cmopose.yml
│   ├── /dev
│   │   ├── Dodkerfile
│   │   └── docker-cmopose.yml
│   ├── /prod
│   │   ├── Dodkerfile
│   │   └── docker-cmopose.yml
│   └── /test
│       ├── Dodkerfile
│       └── docker-cmopose.yml
├── /scripts
├── /requirements
│   ├── req-base.txt
│   ├── req-dev.txt
│   ├── req-prod.txt
│   └── req-test.txt
├── Readme.md
├── CHANGELOG.md
├── TODOLIST.md
├── AUTHORS.md
├── LICENSE
├── /.run
├── .gitignore
├── .dockerignore
├── .editorconfig
├── .bumpversion.cfg
├── .env
├── .coveraterc
└── .pre-commit-config.yaml

```