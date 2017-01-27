.DEFAULT_GOAL := build

all: install

install: build
	idris --install $name;format="lower"$.ipkg

build:
	idris --build $name;format="lower"$.ipkg

test: build
	idris --testpkg $name;format="lower"$.ipkg

clean:
	idris --clean $name;format="lower"$.ipkg
