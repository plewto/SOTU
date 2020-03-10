# SOTU
 
## Simple OSC Test Utility

sotu is composed of two command line utilities

1. osc   a simple transmitter.
2. oscr  an OSC receiver.

Use command -h or --help to display usage details.

osc transmits a single message and terminates.

oscr enters an indefinite loop and displays each received message.  It
may be remotely terminated by transmitting the message /exit.

The heart of this code is not far removed from the python-osc examples.

Requirements:
    Python 3.7+
	python-osc
	


