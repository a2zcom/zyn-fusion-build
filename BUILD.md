PARALLEL=1 make -f Makefile.linux.fltk.mk zynaddsubfx 2>&1 | tee b.log

PARALLEL=1 make -f Makefile.mingw64.fltk.mk zynaddsubfx 2>&1 | tee b.log

PARALLEL=1 make -f Makefile.windows.fltk.mk zynaddsubfx 2>&1 | tee b.log
