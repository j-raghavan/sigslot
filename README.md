# sigslot

This package implements a simple signal/slot mechanism for communication between objects.
Signals and slots is a language construct introduced in Qt[1] for communication between 
objects which makes it easy to implement the observer pattern while avoiding boilerplate 
code. A python object can send signals containing event information which can be received by other objects using special member functions known as slots.