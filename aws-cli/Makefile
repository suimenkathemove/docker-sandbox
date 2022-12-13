ifndef VERBOSE
.SILENT:
endif

.PHONY: build
build:
	docker compose build

.PHONY: run
run:
	docker compose run --rm run /bin/bash

.PHONY: version
version:
	docker compose run --rm run aws --version
