include ../make/docker.mk
include ../make/help.mk

IMAGE_NAME=builder-shell

.PHONY: clean
clean: ## Clean up after the build process.

.PHONY: lint
lint: docker-lint ## Lint all of the files for this Action.

.PHONY: build
build: docker-build ## Build this Action.

.PHONY: test
test: ## Test the components of this Action.

.PHONY: publish
publish: docker-publish ## Publish this Action.
