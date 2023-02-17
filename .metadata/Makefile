# This file is generated automatically from .metadata.org
# File edits may be overwritten!

MAKEFILE_PATH := $(abspath $(lastword $(MAKEFILE_LIST)))
MAKEFILE_DIR := $(notdir $(patsubst %/,%,$(dir $(MAKEFILE_PATH))))
GUIX-TIME-MACHINE = guix time-machine -C $(MAKEFILE_DIR)/guix/channels.scm
GUIX-SHELL = $(GUIX-TIME-MACHINE) -- shell -m $(MAKEFILE_DIR)/guix/manifest.scm
CONTAINER = --container -E "^DISPLAY$$" -E "^XAUTHORITY$$" --expose="$$XAUTHORITY" --expose=/tmp/.X11-unix/ --expose=$$HOME/.Xauthority --expose=/etc/machine-id
GUIX-CONTAINER = $(GUIX-SHELL) $(CONTAINER)

.PHONY: metadata-edits
metadata-edits:
	$(GUIX-CONTAINER) -- sh -c "emacs -q --no-site-file --no-site-lisp --no-splash -l $(MAKEFILE_DIR)/emacs/init.el --file $(MAKEFILE_DIR)/metadata.org"

.PHONY: metadata
metadata:
	$(GUIX-CONTAINER) -- sh -c "emacs --batch -Q  -l $(MAKEFILE_DIR)/emacs/init.el --eval '(process-org \"$(MAKEFILE_DIR)/metadata.org\")'"

project-edits:
	$(GUIX-SHELL) -- kicad
