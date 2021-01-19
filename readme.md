# Building SAAS Application with Flask

## The App's Architecture

- Gunicorn
- Flask
- Celery
- Redis (Backend Message Broker for Celery)
- PostgreSQL & SQLAlchemy
- Click (CLI)
- Stripe (Payment Gateway)
- Docker


## Flask Blueprint
Blueprint helps to organize all routes and structures
- Blueprint allows to break the app into components
- With blueprint, templates and routes are neatly contained
- Eveything becomes maintainable
- It is easy to share code between blueprints


## Jinja2
Jinja2 is a designer friendly templating language for Python. Jinja 2's main features are:

- Template Inheritance
- HTML escaping
- Speed and efficiency
- FLexibility and extensibility

It allows us to:

- Add programming constructs to HTML templates
- Transfer info from Flask to HTML templates
- lets us separate data from the presentation