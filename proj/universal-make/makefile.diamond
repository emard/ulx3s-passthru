# ******* project, board and chip name *******
PROJECT = passthru
BOARD = ulx3s
# 12 25 45 85
FPGA_SIZE = 85

FPGA_PACKAGE = 6bg381c
# config flash: 1:SPI (standard), 4:QSPI (quad)
FLASH_SPI = 4
# chip: is25lp032d is25lp128f s25fl164k
FLASH_CHIP = is25lp128f

# ******* design files *******
CONSTRAINTS = ../../constraints/ulx3s_v20.lpf
TOP_MODULE = ulx3s_passthru_wifi
TOP_MODULE_FILE = ../../rtl/ulx3s_v20_passthru_wifi.vhd

VERILOG_FILES = 

# *.vhd those files will be converted to *.v files with vhdl2vl (warning overwriting/deleting)
VHDL_FILES = $(TOP_MODULE_FILE)

SCRIPTS = ../scripts
include $(SCRIPTS)/ulx3s_diamond.mk
