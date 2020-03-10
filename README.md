# SOTU
 
## Simple OSC Test Utility

sotu is composed of two command line utilities

1. osc   a simple transmitter.
2. oscr  an OSC receiver.

Both commands take the command line argument -u to display usage
information.

osc transmits a single message, by default /ping, and then terminates.

oscr enters an indefinite loop and displays each received message.  You may
remotely terminate oscr by transmitting the message /exit

The heart of this code is not far removed from the python-osc examples.

Requirements:
    Python 3.7+
	python-osc
	


