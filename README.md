yagi-vm
=======

Basic virtual machine implementation for the YAGI language specification.
(See https://code.google.com/p/yagi/ for more information)
Important: This VM is a proof of concept implementation for a rather small subset of the YAGI language,
'e.g.' the provided 'elevator.y' file does not work at the moment due to the incomplete state
of this vm implementation.

How-To Dev Hints
=======

All generated ANTLR files must be placed in the de.fhac.ti.yagi.gen package.

Configuration for ANTLRworks:
  File -> Preferences -> General (Tab) -> Output path
    
The antlr grammar file should placed in the project's root folder.

Important: Do not forget to generate the lexer/parser code after changing yagi's grammar file.
