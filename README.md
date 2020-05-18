# Network-Machine-Monitor

machinemonitor - Checks a list of machines with ping and feeds an output to a printer script. Location of the printer script and config file is hardcoded and will need to be adjusted accordingly.

machinemonitor.cfg - List of machines to be checked. Contains the address of the machines, human readable names and machines'  last status. One machine per line in the format:
[IP/domain] [Human readable name] [last status]

printer - Simple interface for a USB line printer. Has options for 8 text sizes, underline, 4 rotation values, inverted colour.
Useage: printer -s [0-7] -u [0/1] -r [0-3] -i [0/1] "Your text Here"
