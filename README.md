``` sh
/project
├── /src
│    ├── __init__.py
│    ├── __main__.py
│    ├── wsgi.py
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
├── /migrations
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
├── /.run
├── .gitignore
├── .dockerignore
├── .editorconfig
├── .bumpversion.cfg
├── .env
├── .coveraterc
└── .pre-commit-config.yaml

```