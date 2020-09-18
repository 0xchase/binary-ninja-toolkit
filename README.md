# binary-ninja-toolkit

### General
 - Something here
 
### Malware Analysis Toolkit
 - Automatically rename all functions
 - New panel that show function name, xrefs, syscalls, importance level, location, and description of purpose
 - Create an importance rating based on syscalls, size, complexity, location in function call graph, etc
 - Visually iterate through functions based on importance, if syscalls are known, etc. Print function summary. Quickly rename each function.
 - Report editing system. Can add commands output to report like in r2report. 

### CLI
 - Create a new command structure, inspired by or **identical to** the radare2 commands
 
### Debugger extension
 - Control the debugger from the CLI
 - Create a GEF like view for it
 - Add all useful GEF commands

### Frida extension
 - Model off other frida integrations
 - Make command line like r2frida for controlling it
 
### Qiling integration
 - Extend the debugger to integrate with qiling

### Modality integration
 - Special GUI panel for bitvector values

### BAP Integration
 - Taint analysis
 - Create a debugger for BAP, integrate with this

### 3D visualizations
 - A new panel that visualizes in 3D various aspects of the binary
