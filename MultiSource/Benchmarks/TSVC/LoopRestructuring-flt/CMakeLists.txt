list(APPEND LDFLAGS -lm)
list(APPEND CFLAGS -std=gnu99)
set(RUN_OPTIONS 4350 5)
llvm_multisource(LoopRestructuring-flt)
