VERSION=3.5.4-beta
PROJECT_ID=nirmata
REGISTRY=docker.io
PROJECT=${REGISTRY}/${PROJECT_ID}

all: build

build:
	docker build -t ${PROJECT}/kubernetes-zookeeper:${VERSION} .

push: build
	docker push ${PROJECT}/kubernetes-zookeeper:${VERSION}

.PHONY: all build push
