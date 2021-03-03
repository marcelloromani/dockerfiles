.PHONY: build push help

IMAGE_NAME="marcelloromani1975/ubuntu-ssh-server:16.04-1"

help:
	@echo "Docker image:"
	@echo "  $(IMAGE_NAME)"
	@echo
	@echo "Commands:"
	@echo "  build      build the image"
	@echo "  push       push the image"
	@echo "  run-ssh    run a containerised ssh server from the image"

build:
	docker build -t $(IMAGE_NAME) .

push:
	docker push $(IMAGE_NAME)

run-ssh:
	./run_ssh_server.sh
