##########################################################################
# User configuration and firmware specific object files	
##########################################################################

OBJS =

OBJS += nrf24l01p.o
OBJS += rftransfer.o
OBJS += filetransfer.o
OBJS += openbeacon.o
OBJS += mesh.o

LIBNAME=funk

##########################################################################
# GNU GCC compiler flags
##########################################################################
ROOT_PATH?= ..
INCLUDE_PATHS = -I$(ROOT_PATH) -I../core -I.

include $(ROOT_PATH)/Makefile.inc

##########################################################################
# Actual work
##########################################################################

include $(ROOT_PATH)/Makefile.util
