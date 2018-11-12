#INCLUDES = syspara.h

bin_PROGRAMS = TNNP06b
#ORd_CFLAGS = -O2 -Wall -axsse4.2 -mkl -parallel -par-report2 -Winline -inline-level=2 -ip -vec-report2 -opt-mem-layout-trans=3 -pg
TNNP06b_CFLAGS = -O2 -Wall -axsse4.2 -mkl -parallel -par-report2 -vec-report2 -pg
#HRd_CFLAGS = -O2 -axsse4.2 -parallel -Wall

TNNP06b_LDADD = -L/opt/intel/mkl/lib/intel64 -liomp5 -lmkl_intel_lp64 -lmkl_intel_thread -lmkl_core /home/tsumoto/lib/xhplot.o
#ORd_LDADD = /home/tsumoto/lib/xhplot.o

TNNP06b_SOURCES = ./src/tnnp06.c ./src/val_constants.c ./src/mem.c\
	./src/win_out.c ./src/eular.c ./src/runge.c ./src/input_para.c ./src/system.c ./src/currents.c\
	./src/eventloop.c ./src/exptable.c ./src/data_out.c ./src/syspara.h

