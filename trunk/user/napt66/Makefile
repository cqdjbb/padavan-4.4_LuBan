SRC_NAME = napt66-v1.1
THISDIR = $(shell pwd)

all:
ifeq ($(CONFIG_WITHOUT_KERNEL),y)
	@echo "napt66 would not build!"
else
	@echo "------------------ build napt66!"
	$(MAKE) -C $(SRC_NAME)
endif

romfs:

clean:
	$(MAKE) -C $(SRC_NAME) clean
