RUSTC=rustc
RFLAGS=
RLIBS=
SRC=./src/a.rs
BIN=./bin/a
$(BIN):$(SRC)
	mkdir -p $(@D)
	$(RUSTC)\
		$(RFLAGS)\
		$(SRC)\
		$(RLIBS)\
		-o $(BIN)
.phony:\
	run\
	clean
run:
	$(BIN)
clean:
	rm $(BIN)
