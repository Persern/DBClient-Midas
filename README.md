If you have a Delphi application using TClientDataSet and need to distribute the DBClient.dll and Midas.dll files in Windows 11, 
you might need to manually merge registry keys since RegSvr32 does not work well with these files.
Remember to change the path to all DLL files in the reg-file before merging it into your registry.
