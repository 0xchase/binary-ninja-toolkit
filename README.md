# binary-ninja-toolkit

### General
 - Hypervisor integration
 
### Malware Analysis Toolkit
 - Use binja tabbed dock plugin to organize all the different views
 - Automatically rename all functions
 - Create an importance rating based on syscalls, size, complexity, location in function call graph, etc
 - Visually iterate through functions based on importance, if syscalls are known, etc. Print function summary. Quickly rename each function.
 - Report editing system. Can add commands output to report like in r2report. 

### Tabbed dock plugin vews
 - New panel that show function name, xrefs, syscalls, importance level, location, and description of purpose
 - Report editing window
 - Report preview window
 - Trace: Summary of last run. Show all the funcitons called, with argument values, can expand to see each argument
 - Processes: Process monitor
 - Zara: zararules and other signatures
 - Searchable packet capture window
 - Hooks window for hooking various syscalls, memory locations, etc

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
