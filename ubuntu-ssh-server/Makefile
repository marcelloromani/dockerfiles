.PHONY: build push help

IMAGE_NAME="marcelloromani1975/ubuntu-ssh-server:16.04-1"

help:
	@echo "build      build $(IMAGE_NAME)"
	@echo "push       push $(IMAGE_NAME)"

build:
	docker build -t $(IMAGE_NAME) .

push:
	docker push $(IMAGE_NAME)
