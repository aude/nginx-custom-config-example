all: build

build:
	docker build -t delete_me .

run: build
	docker run --rm -p 8080:8080 delete_me

call:
	curl localhost:8080
