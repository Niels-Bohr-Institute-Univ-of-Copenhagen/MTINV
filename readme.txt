Sun Dec 19 14:17:28 PST 2021

MTINV Version 3.0.6 (executables and libs recompiled for Apple's m1-macs)

My Computer: MacOS Big Sur 11.4
/usr/bin/uname -a
	Darwin beno.local 20.5.0 Darwin Kernel Version 20.5.0: Sat May  8 05:10:31 PDT 2021;
	root:xnu-7195.121.3~9/RELEASE_ARM64_T8101 arm64

Requires: GCC and GFortran compilers (see http://hpc.sourceforge.net/)
	gcc (GCC) 11.0.0 20201128 (experimental)
	GNU Fortran (GCC) 11.0.0 20201128 (experimental)

Requires: GMT version 5.x.x up to version 6.2.0
		(see https://www.generic-mapping-tools.org/download/)

Optional: Java SDK and Java RTE

Tested Systems: Mac OS and Linux Redhat, Fedora Core

Instructions: Goto top-level directory ./mtinv.v3.0.6, type make clean; make all

Executables:
-----------------------------------------------------------------------------------------------
/usr/bin/file ./mtinv.v3.0.6/bin/*

./mtinv.v3.0.6/bin/FlinnEngdahl:         Mach-O 64-bit executable arm64
./mtinv.v3.0.6/bin/clean.csh:            C shell script text executable, ASCII text
./mtinv.v3.0.6/bin/ellipse:              Mach-O 64-bit executable arm64
./mtinv.v3.0.6/bin/glib2inv:             Mach-O 64-bit executable arm64
./mtinv.v3.0.6/bin/grn2Mxy:              Mach-O 64-bit executable arm64
./mtinv.v3.0.6/bin/grn2db:               Mach-O 64-bit executable arm64
./mtinv.v3.0.6/bin/grnlib2sac:           Mach-O 64-bit executable arm64
./mtinv.v3.0.6/bin/hist:                 Mach-O 64-bit executable arm64
./mtinv.v3.0.6/bin/hudson:               Mach-O 64-bit executable arm64
./mtinv.v3.0.6/bin/list_MTdb.csh:        C shell script text executable, ASCII text
./mtinv.v3.0.6/bin/makehudson:           Mach-O 64-bit executable arm64
./mtinv.v3.0.6/bin/makepar:              Mach-O 64-bit executable arm64
./mtinv.v3.0.6/bin/mergepdf.csh:         C shell script text executable, ASCII text
./mtinv.v3.0.6/bin/mkgrnlib:             Mach-O 64-bit executable arm64
./mtinv.v3.0.6/bin/mtbestfit:            Mach-O 64-bit executable arm64
./mtinv.v3.0.6/bin/mtinv:                Mach-O 64-bit executable arm64
./mtinv.v3.0.6/bin/multithread_mkgrnlib: Mach-O 64-bit executable arm64
./mtinv.v3.0.6/bin/pltmod:               Mach-O 64-bit executable arm64
./mtinv.v3.0.6/bin/print_MTdb.csh:       C shell script text executable, ASCII text
./mtinv.v3.0.6/bin/remove_MTdb.csh:      C shell script text executable, ASCII text
./mtinv.v3.0.6/bin/renamesac:            Mach-O 64-bit executable arm64
./mtinv.v3.0.6/bin/sac2gmtmap:           Mach-O 64-bit executable arm64
./mtinv.v3.0.6/bin/sac2xy:               Mach-O 64-bit executable arm64
./mtinv.v3.0.6/bin/sacdata2inv:          Mach-O 64-bit executable arm64
./mtinv.v3.0.6/bin/sacmerge:             Mach-O 64-bit executable arm64
./mtinv.v3.0.6/bin/sacqc:                Mach-O 64-bit executable arm64
./mtinv.v3.0.6/bin/sacswapbytes:         Mach-O 64-bit executable arm64
./mtinv.v3.0.6/bin/scripts_original:     directory
./mtinv.v3.0.6/bin/setupMT:              Mach-O 64-bit executable arm64
./mtinv.v3.0.6/bin/stats:                Mach-O 64-bit executable arm64
./mtinv.v3.0.6/bin/switch_color:         Mach-O 64-bit executable arm64
./mtinv.v3.0.6/bin/unpack.csh:           C shell script text executable, ASCII text
./mtinv.v3.0.6/bin/updateMTdb:           Mach-O 64-bit executable arm64
./mtinv.v3.0.6/bin/whatshere:            Mach-O 64-bit executable arm64
./mtinv.v3.0.6/bin/yoffset:              Mach-O 64-bit executable arm64
-----------------------------------------------------------------------------------------------

Dependencies:
-----------------------------------------------------------------------------------------------
/usr/bin/otool -L mtinv.v3.0.6/bin/*

mtinv.v3.0.6/bin/FlinnEngdahl:
	/usr/lib/libSystem.B.dylib (compatibility version 1.0.0, current version 1292.100.5)
mtinv.v3.0.6/bin/ellipse:
	/usr/lib/libSystem.B.dylib (compatibility version 1.0.0, current version 1292.100.5)
mtinv.v3.0.6/bin/glib2inv:
	/usr/lib/libSystem.B.dylib (compatibility version 1.0.0, current version 1292.100.5)
mtinv.v3.0.6/bin/grn2Mxy:
	/usr/lib/libSystem.B.dylib (compatibility version 1.0.0, current version 1292.100.5)
mtinv.v3.0.6/bin/grn2db:
	/usr/lib/libSystem.B.dylib (compatibility version 1.0.0, current version 1292.100.5)
mtinv.v3.0.6/bin/grnlib2sac:
	/usr/lib/libSystem.B.dylib (compatibility version 1.0.0, current version 1292.100.5)
mtinv.v3.0.6/bin/hist:
	/usr/lib/libSystem.B.dylib (compatibility version 1.0.0, current version 1292.100.5)
mtinv.v3.0.6/bin/hudson:
	/usr/lib/libSystem.B.dylib (compatibility version 1.0.0, current version 1292.100.5)
mtinv.v3.0.6/bin/makehudson:
	/usr/lib/libSystem.B.dylib (compatibility version 1.0.0, current version 1292.100.5)
mtinv.v3.0.6/bin/makepar:
	/usr/lib/libSystem.B.dylib (compatibility version 1.0.0, current version 1292.100.5)
mtinv.v3.0.6/bin/mkgrnlib:
	/usr/local/lib/libgfortran.5.dylib (compatibility version 6.0.0, current version 6.0.0)
	/usr/lib/libSystem.B.dylib (compatibility version 1.0.0, current version 1292.100.5)
mtinv.v3.0.6/bin/mtbestfit:
	/usr/lib/libSystem.B.dylib (compatibility version 1.0.0, current version 1292.100.5)
mtinv.v3.0.6/bin/mtinv:
	/usr/lib/libSystem.B.dylib (compatibility version 1.0.0, current version 1292.100.5)
mtinv.v3.0.6/bin/multithread_mkgrnlib:
	/usr/lib/libSystem.B.dylib (compatibility version 1.0.0, current version 1292.100.5)
mtinv.v3.0.6/bin/pltmod:
	/usr/lib/libSystem.B.dylib (compatibility version 1.0.0, current version 1292.100.5)
mtinv.v3.0.6/bin/renamesac:
	/usr/lib/libSystem.B.dylib (compatibility version 1.0.0, current version 1292.100.5)
mtinv.v3.0.6/bin/sac2gmtmap:
	/usr/lib/libSystem.B.dylib (compatibility version 1.0.0, current version 1292.100.5)
mtinv.v3.0.6/bin/sac2xy:
	/usr/lib/libSystem.B.dylib (compatibility version 1.0.0, current version 1292.100.5)
mtinv.v3.0.6/bin/sacdata2inv:
	/usr/lib/libSystem.B.dylib (compatibility version 1.0.0, current version 1292.100.5)
mtinv.v3.0.6/bin/sacmerge:
	/usr/lib/libSystem.B.dylib (compatibility version 1.0.0, current version 1292.100.5)
mtinv.v3.0.6/bin/sacqc:
	/usr/lib/libSystem.B.dylib (compatibility version 1.0.0, current version 1292.100.5)
mtinv.v3.0.6/bin/sacswapbytes:
	/usr/lib/libSystem.B.dylib (compatibility version 1.0.0, current version 1292.100.5)
mtinv.v3.0.6/bin/setupMT:
	/usr/lib/libSystem.B.dylib (compatibility version 1.0.0, current version 1292.100.5)
mtinv.v3.0.6/bin/stats:
	/usr/lib/libSystem.B.dylib (compatibility version 1.0.0, current version 1292.100.5)
mtinv.v3.0.6/bin/switch_color:
	/usr/lib/libSystem.B.dylib (compatibility version 1.0.0, current version 1292.100.5)
mtinv.v3.0.6/bin/updateMTdb:
	/usr/lib/libSystem.B.dylib (compatibility version 1.0.0, current version 1292.100.5)
mtinv.v3.0.6/bin/whatshere:
	/usr/lib/libSystem.B.dylib (compatibility version 1.0.0, current version 1292.100.5)
mtinv.v3.0.6/bin/yoffset:
	/usr/lib/libSystem.B.dylib (compatibility version 1.0.0, current version 1292.100.5)
-----------------------------------------------------------------------------------------------

Do not forget to set ./mtinv.3.x.x/bin directory to your executable PATH 
shell variables.  See file environmental_variables.csh for additional 
required and optional environmental variables.

-- Gene Ichinose (email: geneichinose@yahoo.com) https://people.llnl.gov/ichinose1
