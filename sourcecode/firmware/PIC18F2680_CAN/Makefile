# MPLAB IDE generated this makefile for use with GNU make.
# Project: SPIMaster.mcp
# Date: Wed Jun 24 17:33:48 2009

AS = mpasmwin.exe
CC = mcc18.exe
LD = mplink.exe
AR = mplib.exe
RM = rm

SPIMaster.cof : SPI_Master.o spi_open.o spi_read.o spi_writ.o
	$(LD) /l"C:\MCC18\3_20\lib" "18f2680.lkr" "SPI_Master.o" "spi_open.o" "spi_read.o" "spi_writ.o" /u_CRUNTIME /z__MPLAB_BUILD=1 /o"SPIMaster.cof" /M"SPIMaster.map" /W

SPI_Master.o : SPI_Master.c spi.h SPI_Master.c p18f2680.h C:/MCC18/3_20/h/pconfig.h
	$(CC) -p=18F2680 /i"C:\MCC18\3_10\h" "SPI_Master.c" -fo="SPI_Master.o" -w3 -O-

spi_open.o : spi_open.c C:/MCC18/3_20/h/spi.h spi_open.c C:/MCC18/3_20/h/p18cxxx.h C:/MCC18/3_20/h/p18f2680.h C:/MCC18/3_20/h/pconfig.h
	$(CC) -p=18F2680 /i"C:\MCC18\3_10\h" "spi_open.c" -fo="spi_open.o" -w3 -O-

spi_read.o : spi_read.c C:/MCC18/3_20/h/spi.h spi_read.c C:/MCC18/3_20/h/p18cxxx.h C:/MCC18/3_20/h/p18f2680.h C:/MCC18/3_20/h/pconfig.h
	$(CC) -p=18F2680 /i"C:\MCC18\3_10\h" "spi_read.c" -fo="spi_read.o" -w3 -O-

spi_writ.o : spi_writ.c C:/MCC18/3_20/h/spi.h spi_writ.c C:/MCC18/3_20/h/p18cxxx.h C:/MCC18/3_20/h/p18f2680.h C:/MCC18/3_20/h/pconfig.h
	$(CC) -p=18F2680 /i"C:\MCC18\3_10\h" "spi_writ.c" -fo="spi_writ.o" -w3 -O-

clean : 
	$(RM) "SPI_Master.o" "spi_open.o" "spi_read.o" "spi_writ.o" "SPIMaster.cof" "SPIMaster.hex"

