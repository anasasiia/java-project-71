.DEFAULT-GOAL := build-run

clean:
	./gradlew clean

build:
	./gradlew clean build

install:
	./gradlew clean install

run-dist:
	app/build/install/app/bin/app

run:
	./gradlew run

test:
	./gradlew test

lint:
	./gradlew checkstyleMain checkstyleTest

update-deps:
	./gradlew useLatestVersions

report:
	./gradlew jacocoTestReport

build-run: build run

.PHONY: build
