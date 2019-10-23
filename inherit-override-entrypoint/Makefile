all: build

build:
	docker build -t delete_me .

run: build
	docker run --rm -p 80:80 delete_me

call:
	curl localhost
