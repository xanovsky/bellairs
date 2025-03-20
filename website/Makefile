PYTHON=python3 -m

build:
	$(PYTHON) mkdocs build

preview:
	$(PYTHON) mkdocs serve

install:
	$(PYTHON) pip install mkdocs mkdocs-material pymdown-extensions

deploy:
	make build
	$(PYTHON) mkdocs gh-deploy
