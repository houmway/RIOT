include ../Makefile.tests_common

# exclude boards with insufficient memory
BOARD_INSUFFICIENT_MEMORY := arduino-duemilanove arduino-nano arduino-uno \
                             nucleo-f031k6

USEMODULE += sdcard_spi
USEMODULE += auto_init_storage
USEMODULE += fmt
USEMODULE += shell

include $(RIOTBASE)/Makefile.include
