# galvometer-control

To run the program, open 'syncDAQ_main.vi'.

LabVIEW program for controlling a 2-D galvometer and reading data from microscope.
Avaliable version: after LabVIEW 13.0 (2013), including LabVIEW 2013, 2014, 2015.
Necessary package: basic LabVIEW packages, NI-DAQmx driver.
Collaborate with hardware NI-DAQ USB-6363.
Warning: errors caused by the PC CPU ability and data (USB) transfer rate could occur under some extreme parameters settings.

Update on Apr. 18, 2016:
 - Rearranged the dialogue window layout;
 - Modified the refreshing performance: in coutinuous sampling mode, last pixels are retained until the next refresh;
 - Revised the bug with visualizeTDMS.vi.
 
Update on Apr. 10, 2016:
 - Initial upload.

