VERSION=2.2.0
PROJECT_ID=nirmata
PROJECT=registry-v2.nirmata.io/${PROJECT_ID}

all: build

build:
	docker build -t ${PROJECT}/kubernetes-zookeeper:${VERSION} .

push: build
	docker push ${PROJECT}/kubernetes-zookeeper:${VERSION}

.PHONY: all build push
