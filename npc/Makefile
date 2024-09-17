all:
	@echo "Write this Makefile by your self."

sim:
	$(call git_commit, "sim RTL") # DO NOT REMOVE THIS LINE!!!
test:
	verilator --cc --exe --build -j 0 -Wall -Mdir ./build csrc/main.cpp vsrc/example.v


include ../Makefile