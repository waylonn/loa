
# Name of the testbench without extenstion
TESTBENCH = toplevel_tb

# VHDL files
FILES =  \
	../toplevel.vhd \
	../../../modules/utils/hdl/*.vhd \
	../../../modules/fsmcslave/hdl/*.vhd \
	../../../modules/spislave/hdl/bus_pkg.vhd

# Default settings for gtkwave (visable signal etc.)
#  use gtkwave > File > Write Save File (Strg + S) to generate the file
WAVEFORM_SETTINGS = $(TESTBENCH).sav

# Simulation break condition
#GHDL_SIM_OPT = --assert-level=error
GHDL_SIM_OPT = --stop-time=15us

# Load default options for GHDL.
# Defines make [all|compile|run|view|clean]
include ../../../modules/makefile.ghdl.mk

